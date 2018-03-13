postpic-examples
================

This repository contains examples demonstrating the functionality of [postpic (the open-source particle in cell post processor)](https://github.com/skuschel/postpic). Postpic is used to postprocess the particle and field data written by PIC simulations. Postpic is data format agnostic, so it can be easily extended to read a specific data format.

View the contents of this repository at:  
http://nbviewer.jupyter.org/github/skuschel/postpic-examples/tree/master/

Alternatively [download it](https://github.com/skuschel/postpic-examples/archive/master.zip) to run in on your local machine.
Please note, that some of the examples here depend on specialized readers for the data format and may not run unless their individual dependencies are satisfied, such as the SDF file format reader.


Table of Contents
========

* postpic can be install without leaving the jupyter enviroment. This is particularly useful when working on a front-end node of a cluster, such as JURECA. The neccessary steps are explained in "[00 installation and version check.ipynb](http://nbviewer.jupyter.org/github/skuschel/postpic-examples/blob/master/00%20installation%20and%20version%20check.ipynb)".
* There are two basic examples, which are essentially identical, but work with different file formats, which is set in the first few notebook cells.
  * First, the [epochSDF.ipynb](http://nbviewer.jupyter.org/github/skuschel/postpic-examples/blob/master/epochSDF.ipynb), demonstrating basic usage when working with data from the [EPOCH PIC code](https://cfsa-pmw.warwick.ac.uk/EPOCH/epoch). Note, that the [SDF](https://github.com/keithbennett/SDF) reader (shipped with EPOCH) is neccessary to run it.
  * Secondly, an almost identical example using the [openPMD format](https://github.com/openPMD) can be found here: [openPMD.ipynb](http://nbviewer.jupyter.org/github/skuschel/postpic-examples/blob/master/openPMD.ipynb). This only requires an hdf5 reader.



Contributing
============

**Contributions of any kind are very welcome!** Ideally there are jupyter notebooks containing working examples/use cases/demonstrations of functionality/minimal examples. However anything that is useful will be accepted. So when in doubt, use the issues page to start a discussion.

Use cases demonstrated in this repository can also be a good hint to develop a new feature. If the code proofs general enough, it may finally find its way into the postpic code base to simplify the use of postpic or add new functionality.
