[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/pymol-binder/master?filepath=index.ipynb)


# pymol-binder
PyMol able to be run via MyBinder.org.

Click a 'launch binder' badge on this page to begin an active session where PyMol and the necessary dependencies are set to run.

This repo is meant to allow running PyMol without the typical graphical user interface (GUI), instead running headless using the command line/scripting, in order to extract details from molecular structure files or to render single static images or frames to compose into a movie or animation.

The notebooks available in the launched session demonstrate how to do things.  
You can use those examples as a guide to then analyze and make images or movies/animations of molecules of interest to you.

Resources
---------

- [PyMOL Wiki](https://pymolwiki.org/index.php/Main_Page)

- [List of the PyMol API commands](https://pymol.org/dokuwiki/doku.php?id=api:cmd:alpha) (Note that this doesn't seem to include the the utilities library's commands, such as [Util.cbc()](https://pymolwiki.org/index.php/CBC), and in fact I could only find [these related mentions](https://pymol.org/dokuwiki/doku.php?do=search&id=util) among the PyMol documentation.)

- [Online Supplemental content "An Introduction to Biomolecular Graphics" published in PLoS Comput Biol (2010)](https://pymolwiki.org/index.php/PLoS) that includes code for generating several images.

- [PyMol tutorial from Nicholas Fitzkee's Structual Biology Bootcamp 2019](http://folding.chemistry.msstate.edu/files/bootcamp/2019/session-08_pymol-tutorial.pdf), plus see the entire set of materials for session 8 [http://fitzkee.chemistry.msstate.edu/node/250]

- [A tutorial for PyMol](http://www.pitt.edu/~epolinko/IntroPyMOL.pdf) - uses the standard graphical user interface. And so you might use that to see how some things are done and try performing the steps via scripts here.

- [My structurework repo](https://github.com/fomightez/structurework) - includes PyMol-related utilities by myself and others.

Alternatives
------------

**Looking for something easier than even typical PyMol? Don't want to use code to generate fancy structure images and animations/movies?**  
Then check out [POLYVIEW-3D server](http://polyview.cchmc.org/polyview3d.html). Using that webtool you an fill out forms and check toggle boxes to choose options and settings and then have the server render your image or animation using PyMol behind-the-scenes.

Technical note
--------------

The necessary packages to make PyMol useable via the MyBinder.org system was worked out by [Dominique Sydow](https://github.com/dominiquesydow), see the repo [here](https://github.com/dominiquesydow/pymolmeetsbinder).


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/pymol-binder/master?filepath=index.ipynb)
