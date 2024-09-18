![](https://github.com/vtmvanzelst/BwNCodebook/blob/main/imgs/saltmarsh.PNG)

# BwN Notebook
 Supporting software for Delft University of Technology Building with Nature course 2024-2025.


## Usage

For the design assignment we are making use of the hydrodynamic numerical model XBeach in combination with JupyterLite notebooks. 
These scripts provide some basic functionality. Feel challenged to adapt/develop these scripts to retrieve better system understanding. 
Below we provide instructions on:
1. [JupyterLite Environment](https://github.com/vtmvanzelst/BwNLite#jupyterlite-environment)
2. [Download and use of XBeach](https://github.com/vtmvanzelst/BwNLite#xbeach)

## JupyterLite Environment
For this assignment a JupyterLite Environment is created. This environment runs in the browser, thus does not require any local Python installation.
JupyterLite Environment(https://vtmvanzelst.github.io/BwNLite/)


By these steps, the files that are hosted at GitHub are "pulled" to your machine:
* 1.1 Download GitHub Desktop via (https://desktop.github.com/) and install on your computer.
* 1.2 Browse to (https://github.com/vtmvanzelst/BwNCodebook), click on the green "Code"
   		button and select "Open with GitHub Desktop", or paste the URL into the GitHub client.

#### Windows
1. Download the [Mambaforge](https://mamba.readthedocs.io/en/latest/installation.html) executable file for Windows from [Miniforge GitHub page](https://github.com/conda-forge/miniforge#mambaforge). On that page there are also binaries for Mac and Linux; and for `conda` package managers, so make sure you download
the `mambaforge` executable file for Windows. Install the executable by clicking on it; you can stay with the default settings by just clicking next through the installation client.




## XBeach
XBeach is a two-dimensional model for wave propagation, long waves and mean flow, sediment transport and morphological change on the coastal nearshore area (Roelvink et al., 2009). 
It includes a vegetation module that solves short-wave and long-wave -vegetation interaction (Van Rooijen et al., 2015; Van Rooijen et al., 2016). 

* XBeach software can be downloaded at: 	(https://download.deltares.nl/xbeach)

* XBeach manual:				(https://xbeach.readthedocs.io/en/latest/xbeach_manual.html)


**We did not test XBeach on Mac. You can pre-process and post-process data in Python on your Mac, but we do not provide instructions on how to run XBeach on Mac.**

If multiple XBeach versions are downloaded. This assignment is tested for **XBeach_1.24.6057_Halloween_win64_netcdf**.

Extract the files into `..\YOUR_FOLDER\00_XB_software\`




## References
1. Roelvink, D. et al. Modelling storm impacts on beaches, dunes and barrier islands. Coast. Eng. 56, 1133–1152 (2009).
2. van Rooijen, A. A. et al. Modeling of wave attenuation by vegetation with XBeach. E-proceedings 36th IAHR World Congr. 7 (2015).
3. Van Rooijen, A. A. et al. Modeling the effect of wave-vegetation interaction on wave setup. J. Geophys. Res. Ocean. 121, 4341–4359 (2016).
