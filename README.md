[![Language](https://img.shields.io/badge/python-3.8%2B-blue?style=flat-square)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)](https://github.com/yunjunz/2025-Myanmar-EQ/blob/main/LICENSE)
[![Citation](https://img.shields.io/badge/DOI-10.1126/science.ady6100-blue?style=flat-square)](https://doi.org/10.1126/science.ady6100)


## 2025-Mandalay-EQ

This repo contains notebooks for the coseismic deformation and damage proxy maps of the 2025 Mandalay earthquake in Myanmar ([USGS](https://earthquake.usgs.gov/earthquakes/eventpage/us7000pn9s/executive)). It's used in the following manuscript:

+ Xu, L., Meng, L., Yunjun, Z., Yang, Y., Wang, Y., Hu, C., Weng, H., Xu, W., Su, E., Ji, C. Bimaterial Effect and Favorable Energy Ratio Enabled Supershear Rupture in the 2025 Mandalay Earthquake. _Science, 390_(6772), 476-481. https://doi.org/10.1126/science.ady6100

| Fig. 2. Ground deformation and slip model  | Fig. 3. Multihazard analysis           |
| ------------------------------------------ | -------------------------------------- |
| <img length="800" alt="Fig. 2" src="https://github.com/user-attachments/assets/4ece6603-b5c6-4216-b355-f770d87f988c" /> | <img length="800" alt="Fig. 3" src="https://github.com/user-attachments/assets/4dbf3941-08a9-4564-8c90-06a22144c5a5" /> |


### Data ([Zenodo](https://doi.org/10.5281/zenodo.17113310))

The Sentinel-1, LuTan-1 and ALOS-2 SAR data used in the study are provided by ESA, CRESDA and JAXA, respectively. The derived displacement products are available on Zenodo at https://doi.org/10.5281/zenodo.17113310. It includes the following products:

+ `3D_DEFO.zip`: Three dimensional deformation estimated from the combination of Sentinel-1, LuTan-1, ALOS-2 and Sentinel-2 satellite.
+ `LOS_DEFO.zip`: Deformation estimated from each of Sentinel-1, LuTan-1, ALOS-2 and Sentinel-2 satellite.
+ `DPM.zip`: Damage proxy maps (DPMs) generated from Sentinel-1.
