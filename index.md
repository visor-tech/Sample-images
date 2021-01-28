## SMART Image Browser

[SMART](https://www.biorxiv.org/content/10.1101/2020.09.25.313395v1) stands for “**S**erial sectioning and clearing, 3-dimensional **M**icroscopy, with semi-**A**utomated **R**econstruction and **T**racing”. It is an integrative technology for high-throughput imaging and analysis that combines primate-optimized tissue sectioning and clearing with ultrahigh-speed, large-scale, volumetric fluorescence microscopy, capable of completing whole-brain imaging of a rhesus monkey at 1 µm × 1 µm × 2.5 µm voxel resolution within 100 hours.

The full dataset of a macaque brain is ~250 TB 16-bit TIFF images. Below are sample images of several slices.

## Sample 2D projections
### Imageset 1: superior collicuclus
This rhesus monkey was injected with AAV-Cre plus AAV-DIO-eGFP, and AAV-Cre plus AAV-DIO-mCherry into bilateral superior collicuclus (SC). The brain was sectioned into 300-µm slices, which were also stained with DAPI.

Example 3-channel maximum intensity projection (MIP) images resliced (50-µm each) from a sections could be viewed in the SMART Image Browser:

[http://smart.siat.ac.cn/slides.html?data=200309-006-156&slide=784&site=l](http://smart.siat.ac.cn/slides.html?data=200309-006-156&slide=784&site=l)



## Sample 3D image blocks
### Imageset 2: axonal morphology
[Lychnis tracer](https://github.com/SMART-pipeline/Lychnis-tracing) is for 3D fiber tracing in raw image spaces.

A series of image blocks that are surrounding a thalamocortical axon is accessible from the zenodo link provided in the manuscript. Due to the limit of file size in zenodo and figshare, the current version in zenodo is of lower resolution. Upon publication, datasets with larger size could be accessed via the following link:

_**To be updated**_

It can be loaded and viewed in _Lychnis tracer_. [Lychnis version 1.2.5](https://github.com/SMART-pipeline/Lychnis-tracing/releases/download/1.2.5/Lychnis-1.2.5.zip) has been tested for this dataset on a desktop computer running Windows 10.

Step-by-step tutorial for playing with the demo data:
1. Unzip the package and run lychnis-1.2.5.exe directly.
2. Choose File -> Open Project
3. Select the project file (F5.json) and open it.

Detailed manual of Lychnis could be found in the [project page](https://github.com/SMART-pipeline/Lychnis-tracing).


For more details see [the bioRxiv preprint](https://www.biorxiv.org/content/10.1101/2020.09.25.313395v1).

## Support or Contact

Having any questions? Contact us and we’ll help you sort it out.
