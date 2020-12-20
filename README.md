# Programing on Windows 10
Tools and links to install when trying to code on Windows 10 machines

### Optional: Don't use windows, use linux. 🚀

# Git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
#### We use git a lot. share our code, make branches, tags, send to deploy pipelines

1. Install **Git** for windows: https://git-scm.com/.  
   It's up to you, but we recommend using the default install options.
   
#### Private / Public keys:

You will probably need to work with ssh keys to pull and push code to remote repos.
2. Install **Putty**: https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
3. In order to use private keys use **pageant** (from putty) and also add **GIT_SSH=PATH/TO/Plink.exe**  to your environment variables.    
Instructions: http://guides.beanstalkapp.com/version-control/git-on-windows.html
   


---
# Python
Python Programming Language

1. Install Python3: https://www.python.org/downloads/    
make sure to choose to install **py** launcher that comes with the python3 (3.3 or above) installation. we will use it to switch python versions when we will need them.
2. If you need python2, Install python (2.7.9 or above):https://www.python.org/downloads/release/python-2718/    
   they should also install pip for python2.

3. Run `py --list` to see which python versions you have installed.

#### Errors
If you are trying to install some random dependey using `pip install`, and you get this error:    
`error: Microsoft Visual C++ 9.0 is required. Get it from http://aka.ms/vcpython27`
You probably need to install **Microsoft Visual C++ Compiler for Python 2.7**: https://www.microsoft.com/en-us/download/details.aspx?id=44266 