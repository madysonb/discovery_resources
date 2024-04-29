# Supplemental resources for the discovery of IRAS 04125+2902 b

This repository contains the code and observational data used in the discovery and characterization of IRAS 04125+2902 b. Github links to package owners are provided where appropriate. The code has been tested on macOS Monterey 12.2.1. The code in this repository is written in python, and most additional code (linked below in Additional Packages) is in python as well.


### Python Dependencies

astropy  
numpy  
random  
scipy   
Batman: https://github.com/lkreidberg/batman

### Installation

Most code does not require special installation; clone this repo and ensure dependencies are installed. Some code expects data files with specific names and locations; be sure to update these to match your organization. Some larger files need to be unzipped. The posterior for the TESS transit fit can be found here: https://drive.google.com/file/d/1GM_xhhIyeaNbNGCwhw1jCUb6ggDRALYq/view?usp=sharing The demos expect this to be in the "LCs" folder.

For the Notch update; simply replace the existing core.py file with the one provided here. 

The download process should not take more than a few minutes. 

### Demos / Instructions

Code stored in this repository is presented as jupyter notebooks for simple use. For demo purposes, we reduce the MCMC walkers and steps so the code runs on the order of seconds to minutes. The results of this code are published in Barber et al. in prep. Due to the MCMC, results may vary within reported uncertainties. 

The notebook transit_plots.ipynb shows the user how to read in the misttborn posteriors and make a phase folded transit and a GP TESS sector.

See Notch_and_LOCoR (https://github.com/arizzuto/Notch_and_LOCoR) for example uses of the Notch pipeline. 

### Citation

If you find this repository useful in your research, please cite Barber et al. in prep

### Additional Packages

Some packages exist in their author's GitHub repositories. If you find these packages useful in your research, please cite appropriately. 

RVs: https://github.com/indiajoe/HxRGproc, https://github.com/tofflemire/saphires  
LOFTI binary orbits: https://github.com/logan-pearce/lofti_gaia  
SED Fitter: https://github.com/awmann/sed_fit  
TTV fits: https://github.com/AnaLopezMurillo/TaurusTTVs  
Astrometry: https://github.com/awmann/basic_astrometry, http://www.bo.astro.it/StarFinder/paper6.htm  
Rotation period: https://github.com/waqasbhatti/astrobase  
vsini: https://github.com/aurorayk/Vsini  
cosi: https://github.com/mjfields/cosi  
Original planet search pipeline, Notch and LOCoR: https://github.com/arizzuto/Notch_and_LOCoR  
