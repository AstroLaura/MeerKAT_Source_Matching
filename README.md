# MeerKAT_Source_Matching
This repository has the code I'm using for MeerKAT absolute astrometry and source matching to catalogues from other instruments at different wavelengths.


* [ATPMN_astrometry.ipynb](ATPMN_astrometry.ipynb) is the code for calculating and correcting for the absolute astrometry in the MeerKAT GX339-4 observations. It specifically includes solving for the affine transformation matrix, using a Monte Carlo method to determine the dominant uncertainty on the positions, and applying the transformation matrix to the source positions.
* [LTV_VizierMatches.ipynb](LTV_VizierMatches.ipynb) is the code used for determining whether the sources in the GX339-4 field are spatially coincident with sources in Vizier catalogues.


The DOI for this GitHub repo is:

[![DOI](https://zenodo.org/badge/332645734.svg)](https://zenodo.org/badge/latestdoi/332645734)

<b>If you use the data or code in this repo, please make sure you cite it correctly!</b>

I am part of the <a href="http://www.meertrap.org">MeerTRAP</a> team, based at the University of Manchester and funded by the European Research Council (ERC) under the European Union's Horizon 2020 research and innovation programme (grant agreement No 694745).
