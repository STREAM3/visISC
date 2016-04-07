# visisc
A visualisation library for event data anaylised using the pyISC anomaly detection framework.

##Prerequisite

Install pyisc (including all prerequisites) : https://github.com/STREAM3/pyisc/

Notice, pyisc must be placed in the same folder as visisc so that visisc can find the source code.

Install Mayavi and wxPython (version 2.8.1 is preferred, otherwise if it does not exists as for Mac OS X choose 3.0)

Windows:
`>> conda install --channel https://conda.anaconda.org/krisvanneste wxpython==2.8.12`

Other:
`>> conda install wxpython`

All:

`>> conda install mayavi`

To undo the downgrading of the numpy libraries in previous step:

`>> conda install numpy`


##Installation
`>> git clone https://github.com/STREAM3/visisc`

`>> cd visisc`

`>> python setup.py install`

##Run tutorial

`>> cd docs`

`>> jupyter notebook visISC_tutorial.ipynb`

If not opened automatically, click  on `visISC_tutorial.ipynb` in the web page that was opened in a web browser.
