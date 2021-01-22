# BoWebScript/BWS(-SSB) 1WVC Example

## About BWS 1WVCs Example

BWS 1WVCs (1 Window View Controller site)
is a type of website that uses only index.bws and controller.bwsfc (BWS File Controller file) to display multiple sites sometimes even if another file

BWS mostly uses the JHTMLF (Jeff's HTML Framework) but can be changed by changing Framework in controller.webs (the framework needs to be installed before hand)

this example uses SSB-BWS Code from BWS v1.1RC(t)3

## Prerequisites

A compiler that can execute SSB and has a module or library (JypiterCompiler, BWS-CMD-CLEH, MBTM-BWSC or other 3rd party software)

A Windows 10 computer with atleast 3GB Free RAM space and atleast 3GB storage space (SSD recommended)

## installment & using

### BWS using The JupyterCompiler

**1:)** Get the JypiterCompiler from jcomp.bomeneer.net or download direct from GETSCR by using the web address "get.program.bomeneer.net/jcomp/latest/"

**2:)** When downloading JypiterCompiler select at support "BWS", "BWSH", "BWSC", "BWS-SSB" and "SSBIn" (SSBin is optional) and select at Libs "SSBS", "BWS@a" and "JCOMP.C"

**3:)** go to the folder you want to use in the JypiterCompiler (and where the files are (index.bws and controller.bwsfc)), create a bat file with inside "JCOMP -BWS --tfolder"(if SSBin is installed also include: "---Reload=10seconds")

**4:)** your done, have a nice day.

### BWS using BWS-CMD-CLEH

**1:)** get BWS-CMD-CLEH from bws.ssb.bomeneer.net/get/bwscc/latest or direct from GETSCR using "get.dd.bomeneer.net/bwscc/latest/ --DD"

**2:)** (only if you downloaded the .exe file from bws.ssb.bomeneer.net): execute the .exe and in the commandline fill in "Construct -SysW --CMDI=true"

**3:)** open cmd and navigate to the folder containing the index.bws and controller.bwsfc files

**4:)** to start the bws website use the command (instead of %port% use an open port) "bws -start --here ---%port% --index=normal --controller=true ---controller-name=$normal"

## credits

Original html files by @bkuppeveld-edu

BoWebScript and index.bws by @BoMeneerNL


## Contact

do you have any questions about this repository

you can contact me on

Discord: BoMeneer#4000

or on

Twitter DM: BoMeneer


###### Disclaimer: Every inch of this repository is for an assignment there for all data is atleast outdated if not fake at point reading