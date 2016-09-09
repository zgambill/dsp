# Install software on your computer


### Install [git](http://git-scm.com/).

You have it installed if you can run `git --version` at the command
line and get output like `git version 2.3.5`.


### Install [Anaconda](http://continuum.io/downloads).

There are two things you can verify to check your install.

First, from the command line, all of the following should start up
some kind of Python interpreter:

```bash
python
ipython
ipython notebook
spyder
```

Second, inside any of those Python interpreters, you should be able to
do all of these without error:

```python
import numpy
import scipy
import matplotlib
import pandas
import statsmodels
import sklearn
```

### Install [Homebrew](http://brew.sh/) on Mac

If you use a Mac, install Homebrew if you don't
have it yet. You could use Homebrew to manage your `git` and `python`
installs as well, but the methods given above are very good and more
cross-platform.

---

###Q1. Python Version 2 or 3

**Course material for the bootcamp is currently based on Python version 2.7. Students have the option of using either version 2 or 3 during the bootcamp, but should be aware of some differences in code between the two versions.**  

Did you install Python 2 or 3? Why?  

I installed Python 3, largely because  think it's the future-proof thing to do. Libraries are being made compatible, and new libraries are being made for Python 3. Plus it's still being updated and there is more support. Additionally, I was never really the kind of person to keep using XP when everybody else had moved to Windows 8, and now I'm even a Mac user.

###Q2. Which Python Version Installed   

How can you check the version of Python installed if you happen to be on an unfamiliar computer?

Open up terminal, and type in "python" to open a new interpreter instance and see the version, and Control + D to get out of the interpreter. Additionally, I would try "python3" in terminal. I don't know if this is standard, but I have both Python 2.7 and Python 3.5 installed, with "python" initiating 2.7, and "python3" initiating 3.5.

 


