![](https://github.com/vtmvanzelst/BwNCodebook/blob/main/imgs/saltmarsh.PNG)

# BwN Notebook
 Supporting software for Delft University of Technology Building with Nature course 2024-2025.


## Usage

For the design assignment we are making use of the hydrodynamic numerical model XBeach in combination with JupyterLite notebooks. 
These scripts provide some basic functionality. Feel challenged to adapt/develop these scripts to retrieve better system understanding. 
Below we provide instructions on:
1. [Download and use of XBeach](https://github.com/vtmvanzelst/BwNLite#xbeach)
2. [JupyterLite Environment](https://github.com/vtmvanzelst/BwNLite#jupyterlite-environment)


## XBeach
XBeach is a two-dimensional model for wave propagation, long waves and mean flow, sediment transport and morphological change on the coastal nearshore area (Roelvink et al., 2009). 
It includes a vegetation module that solves short-wave and long-wave -vegetation interaction (Van Rooijen et al., 2015; Van Rooijen et al., 2016). 

* XBeach software can be downloaded at: 	(https://download.deltares.nl/xbeach)

* XBeach manual:				(https://xbeach.readthedocs.io/en/latest/xbeach_manual.html)


**We did not test XBeach on Mac. You can pre-process and post-process data in Python on your Mac, but we do not provide instructions on how to run XBeach on Mac.**

If multiple XBeach versions are downloaded. This assignment is tested for **XBeach_1.24.6057_Halloween_win64_netcdf**.

Extract the files into `..\YOUR_FOLDER\00_XB_software\` on your device.


## JupyterLite Environment
For this assignment a JupyterLite Environment is created. This environment runs in the browser, thus does not require any local Python installation.
[Link to JupyterLite Environment](https://vtmvanzelst.github.io/BwNLite/)
The environment consists of:
1. `00_XB_software` 	[empty folder - to show the required folder structure on your local device]
2. `01_transects`   	[folder       - includes transect data (bottom profile, vegetation presence)] 	
3. `02_XB_sims`         [folder       - includes some dummy XBeach input files (do not make changes to those files) and will be used to store new input files based on user input] 
4. `support_funcs`      [folder       - that holds a Python file that contains functions that are used in the notebook]

5. `XB_notebook.ipynb`  [Notebook     - JupyterLite notebook that contains instructions and functions to set-up, run and post-process XBeach simulations.

6. `imgs`               [folder       - some images to support the environment]





## References
1. Roelvink, D. et al. Modelling storm impacts on beaches, dunes and barrier islands. Coast. Eng. 56, 1133–1152 (2009).
2. van Rooijen, A. A. et al. Modeling of wave attenuation by vegetation with XBeach. E-proceedings 36th IAHR World Congr. 7 (2015).
3. Van Rooijen, A. A. et al. Modeling the effect of wave-vegetation interaction on wave setup. J. Geophys. Res. Ocean. 121, 4341–4359 (2016).
