# Prediction of the Powder Catchment Efficiency and Melt Track Height in Laser Directed Energy Deposition

Code Title: DED-LB particle stream diameter measurement using Python OpenCV

## Overview:

This code extracts the Particle stream diameter from back-illuminated high speed video franes across different powder deposition parameters.
The code is published for research reproducibility of the high-speed image analysis in corresponding project manuscript (https://doi.org/10.1016/j.jmapro.2025.01.039). 
For evaluating the code, the raw high-speed imaging data for the 67 - 80 um powder under a carrier gas flow rate of 6 L/min is available for download from the data repository folder "HighSpeedDataForGitLabCode". An automatic data download is also available in the code.

## Installation

Clone the repository
```shell
git clone https://github.com/CMU-EMIT-Lab/DED_ParticleStreamDiameter.git
```

Install the required packages. A new python environment of version 3.9.X is recommended, shown below. Installation should take less than 10 minutes.

```shell
conda create --name DEDParticleStream python=3.9.19
conda activate DEDParticleStream
pip install -r requirements.txt
```

Note: Since this code was writted in jupyter notebook, use a code IDE that has jupyter notebook support (i.e. VCcode, but not Pycharm Community Edition).

## Reference

Please use the following reference if you utilize this code.

```
@article{ANCALMO2025207,
  title = {Prediction of the powder catchment efficiency and melt track height in laser directed energy deposition},
  author = {Colin Ancalmo and Sneha Prabha Narra},
  journal = {Journal of Manufacturing Processes},
  volume = {137},
  pages = {207-220},
  year = {2025},
  issn = {1526-6125},
  doi = {https://doi.org/10.1016/j.jmapro.2025.01.039}
}
```