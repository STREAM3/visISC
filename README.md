# visisc
A visualisation library for event data analysed using the pyISC anomaly detection framework.


##Prerequisite

Notice, pyISC/visISC is only been tested on 64 bits machines.

Install pyisc (including all prerequisites) : https://github.com/STREAM3/pyisc/

Notice, pyisc must be placed in the same folder as visisc so that visisc can find the source code. The pyisc folder must be named "pyisc".

Install Mayavi and wxPython (version 2.8.1 is preferred, otherwise if it does not exists as for Mac OS X choose 3.0)

<<<<<<< HEAD
=======
(If you want to disable ssl verification when installing, you will find the instructions <a href="https://docs.continuum.io/anaconda-repository/faq#how-do-i-disable-ssl-checking-on-package-installation">here</a>.)

Windows:
`>> conda install --channel https://conda.anaconda.org/krisvanneste wxpython==2.8.12`
>>>>>>> origin/master

`>> conda install mayavi wxpython ipython=4.2 numpy=1.9.3 pandas matplotlib`


*Notice*: The latest version (4.0.5) of Anaconda is more restrictive to conflicting library versions. Thus, when installing Mayavi (version 4.4), numpy is most likly downgraded to 1.9.3 and cannot be upgraded again. If you have not already downgraded numpy before installing pyISC, you have to reinstall pyISC after installing Mayavi. 

>>>>>>> Stashed changes

##Installation
`>> git clone https://github.com/STREAM3/visisc`

`>> cd visisc`

`>> python setup.py install`

##Run tutorial

`>> cd docs`

`>> jupyter notebook visISC_tutorial.ipynb`

If not opened automatically, click  on `visISC_tutorial.ipynb` in the web page that was opened in the web browser.
