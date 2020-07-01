# Soils

### Feng Yin
### Department of Geography, UCL
### ucfafyi@ucl.ac.uk


In this notebook, I will introduce the process of gathering soil spectra from multiple sources and interpolating them into same wavelength range (400-2500). Then the principal component analysis (PCA) is applied to derive a handful of PCs for later usage.

There is not a lot of soil spectra from a single source, and we want to have samples to cover major type of soils around the world, so we end up collecting all the available soil spectra (I can find on the internet) from different sources. Below is the list of sources:

1. [USGS spectral library](https://www.usgs.gov/energy-and-minerals/mineral-resources-program/science/usgs-high-resolution-spectral-library), V5, V6 and V7;
2. [ICRAF-ISRIC Soil VNIR Spectral Library](https://www.isric.org/explore/ISRIC-collections);
3. [Prosail soil model](https://github.com/jgomezdans/prosail/blob/master/prosail/soil_reflectance.txt);
4. [Price soil model](https://naldc.nal.usda.gov/download/37764/PDF)
5. North China plain (NCP) in-situ measurements.
