# Measured Justice

This repo is dedicated to the analysis of publicly available court data. All of the work here has been done with freely available software. Mostly, it's a collection of [notebooks](http://www.nature.com/news/interactive-notebooks-sharing-the-code-1.16261). For people interested in replicating or expanding on this work I've put together this quick start guide for setting up [Project Jupyter](http://jupyter.org/) notebooks.
 
## Download, Install, and Run Notebooks

 Download and install Anaconda (a free distro which includes everything you need to use Jupyter). See https://www.continuum.io/downloads
+ Open up a terminal/command prompt and navigate to the directory where you want to be working (e.g., /users/yourname/documents/)
+ At the prompt enter:
  + ``jupyter notebook``
+ That should open up a new tab in your web browser.
+ You should see a dropdown menu in the upper right labeled “New.” Click on that, and choose “Python 3” under “Notebooks.”
+ That should open a new notebook. Basically, you put your code in cells and run them as needed. As the [Nature article](http://www.nature.com/news/interactive-notebooks-sharing-the-code-1.16261) linked above makes clear, this is a great way to collaborate and to keep all your work in one place. 
+ Here’s are some [example notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#introductory-tutorials) to get you started. Just cut-and-paste from these examples and start playing.  

## Common Speed Bumps

If you start to play around and get an error like:
 
``NameError: name 'pd' is not defined`` 
 
That means that your notebook hasn’t loaded a module with the name ‘pd’. So either, you’re missing something like this:
 
``import numpy as np``
 
or the module isn’t installed on your system. If it’s the latter, you’ll get an error like:
 
``ImportError: No module named 'numpy'``
 
when you try to import the module. To install a module, all you have to do is go to the terminal/command prompt and type:
 
``conda install [module name]`` For example: ``conda install numpy``
 
Have fun. 
