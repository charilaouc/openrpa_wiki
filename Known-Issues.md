SAP recording is in beta, and only tested on latest version of the sap client with the default theme.
SAP get datatable() is in ALPHA

IFrames are not supported in Internet explorer

Framesets and Iframe is not supported in xpath mode in IE

Virtual clicking and setting values are not working in 32bit version of java, and in some version of oracle JVM

Robot cannot be run from an UNC share or special One/dropbox/G-drive, all files **must** be located on the local pc.

If recording on a computer with multiple screens, try and only use the primary monitor

Recording with windows display settings where Scale and layout is not set to 100% will not work.
( you can change this back to a non 100% value after recording, if all clicks are virtual )
![right click desktop and select display settings](https://github.com/open-rpa/openrpa/raw/master/docs/img/dpi1.png)
![Set scale to 100%](https://github.com/open-rpa/openrpa/raw/master/docs/img/dpi2.png)

Disabling the embedded python and using the locally installed version will not work with anaconda python. 
A normal python install should work with version 3.5 and up to 3.7 ( needed if you want to use tkinter )