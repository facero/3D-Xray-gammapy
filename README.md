# 3D-Xray-gammapy
Showing the several steps of a 3D analysis of X-ray data using GMCA and gammapy:
- Creating data cubes from X-ray event lists
- Applying a blind source separation technique to disentangle physical components and retrieving their spatial and spectral signatures
- Showcasing a 3D X-ray analysis following the 3D forward folding technique as in Fermi-LAT & Cherenkov telescopes


For this you first need to create data cube (RA, Dec, Energy) from the X-ray event list.
So far the best way I found is using gammapy (a gamma-ray Python package).
You will need to install gammapy first :  
https://docs.gammapy.org/0.20/getting-started/index.html#quickstart-setup

Installing in a separate environment is recommended.



To create an X-ray cube for Chandra, XMM-Newton or eROSITA data follow the notebook : 
`Create-cube-gammapy.ipynb` 

For the blind source separation application on real X-ray data cubes (no semi-blind mode) :
`sGMCA_source_separation_example.ipynb`  
 
 For the 3D X-ray analysis check out:
 `Cube_Xrayfitting_gammapy020.ipynb`  
 
