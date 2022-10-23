# 3D-Xray-gammapy
Testing a 3D analysis of X-ray data using gammapy.

For this you first need to create data cube (RA, DEc, Energy) from the X-ray event list.
So far the best way I found is using gammapy (a gamma-ray Python package).
You will need to install gammapy first :  
https://docs.gammapy.org/0.20/getting-started/index.html#quickstart-setup

Installing in a separate environment is recommended.

To create an X-ray cube for Chandra, XMM-Newton or eROSITA data follow the notebook : 
Create-cube-gammapy.ipynb
