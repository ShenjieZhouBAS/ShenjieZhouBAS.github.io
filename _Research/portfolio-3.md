---
title: "Stochastic parametersation of mesoscale wind kinetic energy"
excerpt: "A coherent reanalysis (ERA5) wind kinetic energy deficiency over mesoscale range in both wavenumber and frequency domain <br/><img src='/images/WIND_KE.png'>"
collection: Research
---

This is part of my PhD chapter where we investigated on a generalized approach to parameterise the commonly under-represented mesoscale wind variability in the re-analysis atmosphere field (e.g. ERA5). The atmosphere reanalysis data are commonly used to force a ocean simulations with realistic configuration. The wind forcing is the primary momentum input into the ocean that drives the large-scale general ocean circulation in the model. It is previsouly recognised that the presence of polar lows, tip jets associated with the orograhpic feature at the atmosphere-ocean boundry layer can change the modelled behavior of meridional overturning circulation ([Condron and Renfrew, 2013)](https://doi.org/10.1038/ngeo1661), [Pickart et al., 2003](https://doi.org/10.1038/nature01729)). These specific atmosphere phenomena were poorly resolved in reanalysis products due to the lack of resolution, but largely well-resolved now. In the meantime, the wind kinetic energy is still generally under-represented on a broad wavelength scales in the most recent ERA5 reanalysis wind field (Figure 1) even though the mesoscale wind systems (e.g., polar lows) are properly resolved.

We developed a generalized approach to parameterise 'broadband' wind energy deficiency over the mesoscale range on spatial and temporal domain (Figure 1), and we managed to rectify the wind kinentic energy spectra on the wavenumber and frequency domain at the same time (Figure 1). The parameterisation possesses folllowing advantages:

1. A direct control on the energetic characteristics of the parameterised wind field on wavenumber and frequency domain.
2. Easy to implement for attribution study in atmosphere-ocean coupling scheme.
3. Overall 'correction' or offset brought by the parameterisation on the mean state is small enough to be assessed and compared with the original ERA5 data.

![Figure 1](/images/Research_2_fig1.png)
Figure 1. (left) The ellipses used in our climatology aligning with SSH contour (red) from SOSE. (right) The majoraxis length (km) of each ellipse varying with local bathymetry.

We then construct 2D maps for metrics that are of our interests such as the temperature of Circumpolar Deep Water (CDW) which is the primary source of heat that leads to Antarctic ice shelves melting. The comparison between our climatology and the SOSE results shows high consistency (Figure 2), suggesting that the climatology is capturing the broad the picture of the thermohaline characteristics of the Southern Ocean water masses. Version 1 of the profile compilation is now published at [SEANOE data repository](https://www.seanoe.org/data/00886/99787/) and freely downloadable. Please get in touch if you are interested in using the climatology product.

![Figure 2](/images/Research_1_fig2.png)
Figure 2. (left column) The conservative temperature map of CDW (upper panel, defined as the temperature maximum below 200 m down along the water column) and winter water (lower panel,defined as temperature minimum between 50 to 400 m down along the water column) from our climatology. (right column) Same field derived from SOSE output.
