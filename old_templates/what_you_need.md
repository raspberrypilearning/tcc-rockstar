[comment]: # (
Rather than a template, this is more of a structure and a set of useful snippets as it is likely each course will have slightly different requirements. The paragraphs in [] are instructions or guidance.

Principles:
+ Requirements are presented not solutions e.g. Python 3, not IDLE
+ Learners are supported in making a choice themselves about what to use
+ Instructions are provided for the most "common" solutions
+ Instructions are provided "just in time". e.g. If a python package isn't needed until week 2, instructions for installing it are provided for installing just before it is needed.

What is this step for?
+ To describe why they need more than just access to the FutureLearn site
+ To give learners a list of hardware and software they will need to complete the course
+ To present the options they have
+ To link out to "how to get help"
+ Acknowledge that this step is HARD!
)

## What you need
[In this section describe the requirements for completing the course, the "things" a learner will need. This should be a summary. 

If certain activities can only be completed on a desktop or laptop computer, not a mobile device, note it here

If you need to express further details or maybe constraints, do so in a specific section underneath.]

To complete the activities within this course you will need:

+ Access to [Scratch 3](https://scratch.mit.edu/) either [online](https://scratch.mit.edu/projects/editor) or [installed on your computer](https://scratch.mit.edu/download).
+ To be able to create and run [Python 3](https://python.org) programs.
+ A computer (macOS, PC with Windows or Linux, Raspberry Pi)
+ An internet connection for software installation
+ A Raspberry Pi Computer to … 
+ A microbit for ...
+ The following hardware components to ...
  + LED
  + Resistor
  + etc

All the resources required to complete this course can be used for free.

[If there are options on what a learner can use, describe what the course leader will be using and why]

During the course I will be using:

+ [Scratch 3 installed on my computer](https://scratch.mit.edu/download) so I do not have to be connected to the internet
+ the Python editor [Mu (Alpha)](https://codewith.mu) as the simple interface helps when presenting
+ [anything else]

**Note:** You do not have to use the same as me.

Getting ready to start can often be the hardest task. Take some time now to find a solution that works for you. 

### Python

To create Python programs, you need a text editor to write your code and a Python interpreter. You write the code into the text editor and the interpreter executes your code on the computer. 

An editor, interpreter, and other useful tools (e.g. a file browser) are often bundled together into an Integrated Development Environment (IDE). IDEs make creating programs much easier.

If you require advice about the options for using Python or instructions for installing Python, please review our guidance on [Applications for creating Python programs](https://projects.raspberrypi.org/en/projects/python-install-options).


[Any constraints 

e.g. 

In week 2 you will be using Python to create images and will need to [install the Python package](https://projects.raspberrypi.org/en/projects/install-python-packages) pillow. Instructions will be given at the time on how to do this.

or 

In week 4 you will be creating a GUI so will need either a [dedicated Python editor](https://projects.raspberrypi.org/en/projects/python-install-options/2) or a [full Python installation](https://projects.raspberrypi.org/en/projects/python-install-options/3) and the ability to [install Python packages](https://projects.raspberrypi.org/en/projects/install-python-packages).
]

### Python packages

[if a package isnt required until later in the course, introduce it "just in time" as its own step]

You will need to install the following packages to complete the practical activities in this course:

+ [pillow](https://pypi.org/project/Pillow/)
+ [requests](https://pypi.org/project/requests/)
+ [pokebase](https://pypi.org/project/pokebase/)
+ [guizero](https://lawsie.github.io/guizero/)

How you install a package will depend on:

+ The set up of your computer
+ How you are using Python
+ Your access rights

The [Installing Python packages](https://projects.raspberrypi.org/en/projects/install-python-packages) guide provides advice on how to install Python packages for the most typical scenarios.

[Further installation instruction can be found in the [package documentation](https://link_to_package_documentation).]

You can test whether the packages have installed by creating a small Python program to import their modules.

~~~python
import requests
import pokebase
import PIL
import guizero

print("all modules imported")
~~~

When you run the program, you should see the message `all modules imported`. If you see an error, such as `ModuleNotFoundError: No module named` followed by the name of a module, that module hasn't been installed correctly. Make sure that all of these packages are correctly installed before you move on to the next step.

### Scratch

To create Scratch programs you will need access to [Scratch 3](https://scratch.mit.edu/) either [online](https://scratch.mit.edu/projects/editor) or [installed on your computer](https://scratch.mit.edu/download).

### [Other software]

[Any other software required to complete the course. If it is only required for certain steps or weeks, state which these are. ]

### [hardware]

[Any specific hardware or peripherals required]
