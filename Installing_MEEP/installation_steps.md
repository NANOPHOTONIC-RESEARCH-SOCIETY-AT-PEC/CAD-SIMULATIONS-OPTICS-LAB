## Installation steps for MEEP Software by MIT
This doc will guide you to get your MEEP simulation environment readu on your linux distributions (PClinuxOS)

### What is MEEP ?
Meep implements the finite-difference time-domain (FDTD) method for computational electromagnetics. This is a widely used technique in which space is divided into a discrete grid and the fields are evolved in time using discrete time steps — as the grid and the time steps are made finer and finer, this becomes a closer and closer approximation for the true continuous equations, and one can simulate many practical problems essentially exactly.

You can know more about it at its official documentation : https://meep.readthedocs.io/

## What is PClinuxOS ?
PCLinuxOS is a user-friendly Linux distribution with out-of-the-box support for many popular graphics and sound cards, as well as other peripheral devices. The bootable live DVD provides an easy-to-use graphical installer and the distribution sports a wide range of popular applications for the typical desktop user, including browser plugins and full multimedia playback. The intuitive system configuration tools include Synaptic for package management, Addlocale to add support to many languages and Mylivecd to create a customised live CD.

## So let us begin once your linux OS is ready and updated
--> Open the terminal window
--> type command : 

**[desugnerguy13@localhost ~]$ su**     
// here designerguy13 is my user name and su is linux commands which means enter into superuser

**(base) [root@localhost desugnerguy13]#**

//welcme now you are in super user called root login

--> The easiest way to get started as suggested by MEEP community is to install Miniconda, which comes with everything necessary to create Python environments with Conda. For example, to install Miniconda with Python 3 on Linux:
--> Run the command :

**(base) [root@localhost desugnerguy13]# wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh -O miniconda.sh**

// press Y when asked for permission untill the packages are downloaded 
// Make sure you are on internet

-->  Now it is time to create Conda environment for PyMeep to isolate it from other Python libraries that may be installed.

**(base) [root@localhost desugnerguy13]# conda create -n mp -c conda-forge pymeep**

--> This creates an environment called "mp" (you can name this anything you like) with PyMeep and all its dependencies. 
Now everytime yougot to use meep, come to this terminal and then type 

**(base) [root@localhost desugnerguy13]# conda activate mp**  

///////////Remeber if you donot mention it to be mp then bydefault it will consider your 
root conda environment if there s any, ignore this if you are following this for the first time

## congratulations you installed meep
Now to use it, you can use jupyter notebook 

for that follow steps,

**(base) [root@localhost desugnerguy13]# jupyter-notebook --allow-root

and then you will be directed to jupyter notebook

## Test whether meep package has been installed or not !
In juoyter , create a python file and type the command

**import meep as mp 

then press Shoft + Enter

and see if it executes without any traceback error

# Acknowledgements
- [Nanostructures and Computation Group
](https://github.com/NanoComp), http://math.mit.edu/~stevenj/group (MIT, Cambridge, MA, USA
)
