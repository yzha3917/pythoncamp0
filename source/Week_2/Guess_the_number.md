##Guess the number

###The Project
Guess the number is a mini-project from a Coursera course: [An Introduction  to Interactive Programming in Python (Part 1)](https://class.coursera.org/interactivepython1-002). 


###The Game
According to [the assignment page](https://class.coursera.org/interactivepython1-002/human_grading/view/courses/974633/assessments/29/submissions):

> One of the simplest two-player games is “Guess the number”. The first player thinks of a secret number in some known range while the second player attempts to guess the number. After each guess, the first player answers either “Higher”, “Lower” or “Correct!” depending on whether the secret number is higher, lower or equal to the guess. In this project, you will build a simple interactive program in Python where the computer will take the role of the first player while you play as the second player.


###The code
Since it's requested to involve SimpleGUI for this project, both [codeskulptor code](http://www.codeskulptor.org/#user39_EcWw8kBKIX_1.py) and [GitHub code](https://github.com/yzha3917/omooc.py/blob/master/guess_the_number.py) are given. 

![codeskulptor code](https://github.com/yzha3917/pythoncamp0/blob/master/source/Week_2/Guess.png?raw=true)



###Future tweaks
* Local Python GUI module.
* Fonts and layouts of outcome.

### Raised issues
####the first line of code
It's been a while to write codes (not to say I was good at it though), I find the first line of code is particular hard to write, even though I've figured out the logic of the game. The syntax was so poor that I had to start it over by opening a new file. 

#### local vs. global variables
During coding, i find it's confusing for me to determine when I should add "Global Variable" on the line. Then, I realise, it's only necessary in a function to differentiate local and global variables, not in a loop or if statements. 

#### local GUI module
The [SimpleGUI](http://www.codeskulptor.org/docs.html#tabs-Python) is purely based on a online service called [CodeSculptor](http://www.codeskulptor.org/). You may say it's wise to setup a local GUI module instead, since it's an online service. 

However this local GUI module thing costs me a few solid hours unexpectedly, and most importantly, 

1. SimpleGUI has a local version, which is a perfect replacement, and CCQ has released a brief guide [here](https://github.com/OpenMindClub/OMOOC.py/wiki/codeskulptor_in_local). 
2. Apparently you need to install several Python modules by a tool named [pip](https://pypi.python.org/pypi/pip)
3. And you need to install [distribute](https://pypi.python.org/pypi/distribute/0.6#installation-instructions) to install pip, which, by the way, has been merged into [Setuptools](https://pypi.python.org/pypi/setuptools). 
4. According to this [page](http://stackoverflow.com/questions/11425106/python-pip-install-fails-invalid-command-egg-info), you need to use pip or easy_install to upgrade Setuptools. 
5. What should I do? I [install](http://stackoverflow.com/questions/17886647/cant-install-via-pip-because-of-egg-info-error) easy-install first. 
6. After finishing pip problems, my experience on installing these modules proved me as a man without any luck again. 
7. Unlike the brief guideline indicates, I could not install Mercurial via pip. According to a Stack Overflow page, Python 3.x has pre-packaged Mercurial itself. So I installed 3.x version and [pyenv](https://github.com/yyuu/pyenv) as the python version control (2.x version is important to OS X, which means you can't replace 3.x version with 2.x version), based on this [tutorial](http://amaral-lab.org/resources/guides/pyenv-tutorial).
8. And it's not working! I had to download Mercurial by it's [webpage](http://mercurial.selenic.com/wiki/Download#Mac_OS_X)
9. It's not over, yet. Mysteriously, i need to add "sudo" on every "pip" instruction, because of the permission deny issues. 

