# clas12Nim

This is a collection of clas12 detector nim papers, that collect into a nim volume

Pre-requisites:
-----------------

- scons or MacTex
- latex (for mac: http://www.tug.org/mactex/)


How to use
----------

First, clone the repository: 

```git clone https://github.com/JeffersonLab/clas12Nim.git```

Then navigate to your detector and use scons:

- to create the PDF: ```scons```
- to clean:  ```scons -c```

Alternatively (on an Apple computer with latex installed) you can use MacTex to open the main file, which has the same name as the system (for example: svt.tex for sct).

What to edit
------------

Edit these files:

* titleAndAuthors.tex: include the titles, list of authors and their addresses
- abstract.tex: 
- overview.tex
- requirements.tex
- design.tex
- hardware.tex
- electronics.tex
- readout.tex
- calibration.tex
- reconstruction.tex
- simulation.tex
- performance.tex
- conclusions.tex
- acknowledgmentAndBib.tex

