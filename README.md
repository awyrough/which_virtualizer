# which_virtualizer
Linux-friendly bash script so you know which virtual environment is active

This bash script alters your bash prompt so that you are aware of the project directory
of the current virtual environment.

Typically, a python virtual environment will do this:
```
prompt$ source venv/bin/activate
(venv)prompt$ cd ../
(venv)$ echo "Where did this virtualenvironment even start?"
```
When you change directories, it is easy to lose track of what virtual environment you are in.

Here's what you do:

[set up] create a symlink wherever your virtualize
```
prompt$ source path/to/this/repo/set_me_up.sh
```
This will create a symlink in your local repo, which will be used as your virtualenv starter
```
prompt$ source virtualize
(venv)@project $prompt 
```
