---
layout: page
title: Research
sidebar_link: true
sidebar_sort_order: 2
---

<h1>Global studies</h1>

<p><a href="https://www.frontiersin.org/articles/10.3389/frsen.2022.894571/full">GLanCE project</a><br>
<p> To address the need for high-quality land cover information we are using the global record of Landsat observations to compile annual maps of global land cover from 2001 to 2020 at 30 m spatial resolution. To create these maps we use features derived from time series of Landsat imagery in combination with ancillary geospatial data and a large database of training sites to classify land cover at annual time step.<br>

<p><img style="float: center;" src="../images/frsen-03-894571-g004.jpg" width="800" height="600"><br>

<b>Figure:</b> Version 1.0 global land cover map for 2010 based on the GLanCE Level 1 classification system.

<p><a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2019EF001316">Sensitivity of global pasturelands to climate variation</a><br>
<p> To characterize the effect of climate on pastureland productivity at global scale, we analyze the relationship between satellite‐derived enhanced vegetation index data from MODIS and gridded precipitation data from CHIRPS at 3‐ and 6‐month time lags. To account for the effects of different production systems, we stratify our analysis by agroecological zones and by rangeland versus mixed crop‐livestock systems. Results show that 14.5% of global pasturelands experienced statistically significant greening or browning trends over the 15‐year study period, with the majority of these locations showing greening.<br>

<p><img style="float: center;" src="../images/Figure5_new_full.png" width="800" height="600"><br>

<b>Figure:</b> Global mean seasonal sensitivity of pasturelands: (a) resistance to drought and (b) resilience. This figure shows the model coefficients for precipitation (a) and lagged vegetation anomalies (b) for the 20 different study units. Areas in purple and blue are most sensitive to change in precipitation regimes. Note that the two scales have different ranges.

<h1>Southern Cone of South America</h1>
	
<p><a href="https://www.mdpi.com/2072-4292/14/16/4005">Temporally-Consistent Annual Land Cover from Landsat Time Series in the Southern Cone of South America</a><br>

<p>To produce temporally-dependent land cover estimates—meaning land cover is predicted over time in connected sequences as opposed to predictions made for a given time period without consideration of past land cover—we use structured learning with conditional random fields (CRFs), coupled with a land cover augmentation method to produce time series training data and bi-weekly Landsat imagery over 20 years (1999–2018) across the Southern Cone region of South America.<br>

<p><img style="float: center;" src="../images/sch1_overview_v2_ink.png" width="800" height="600"><br>

<b>Figure:</b> Overview of classification results for the beginning (left panel) and end (right panel) of the study period at 30 m spatial resolution.
	
<p><a href="https://www.mdpi.com/2072-4292/14/16/4005"></a>Widespread Changes in 21<sup>st</sup> Century Vegetation Cover in Argentina, Paraguay, and Uruguay<br>

<p>We used Landsat to map changes in the fractional cover of bare ground, woody cover, and herbaceous vegetation at annual time steps from 1999 to 2019 over APU. Using field observations and Landsat imagery, we created a spectral library representative of these three cover types. We trained a machine learning model to map annual fractional cover at 30-meter spatial resolution, and used a Bayesian change point algorithm to characterize spatial and temporal trajectories of LCLUC.<br>
	
<p><img style="float: center;" src="../images/Figure4.png" width="800" height="600"><br>

<b>Figure:</b> Summary of change for the Paraguayan Dry Chaco and Atlantic Forest from 1999 to 2019: net change in fractional cover of herbaceous (a) and woody (b) vegetation; annual mean fractional cover (c, d); fractional cover of barren, woody and herbaceous vegetation for pixels that experienced gain in herbaceous cover (e, f). Samples in panels (c) and (d) were taken at regular intervals (5000 m) across the ecoregions. In panels (e) and (f) each point (n=10,000) represents the vegetation composition of a pixel in 1999/2000 and the colors represent the magnitude of gain in herbaceous fraction over the 20-year study period. The ‘x’ represents the mean composition for all plotted pixels in 1999/2000 and the ‘+’ represents mean composition in 2018/2019. This figure shows results for pixels with statistically significant changes only.

<h1>Methods</h1>

<p><a href="https://ieeexplore.ieee.org/document/9701288">Reconstruction of Satellite Time Series With a Dynamic Smoother</a><br>

<p>We introduce a dynamic temporal smoothing (DTS) method that reconstructs sparse and noisy signals into dense time series at regular intervals. The DTS is a weighted smoother with parameters that adjust dynamically to variation in time series and can be applied to both dense and sparse time series measurements. Because the DTS smoother we describe is specifically designed to reconstruct high-quality time series of optical imagery, it has utility for applications focused on land cover and vegetation remote sensing over long time periods at moderate spatial resolution.<br> 
	
<p><img style="float: center;" src="../images/flowchart.png" width="800" height="600"><br>

<b>Figure:</b> Key steps in the time series smoothing process. Two steps, the input data and dynamic temporal smoothing (DTS), are required. The other steps—spatial gap-filling, outlier detection, and post-DTS filtering—are optional enhancements. The DTS is designed to use as input any time series scaled between 0 and 1. Thus, reflectance bands or normalized indices are viable options. The spatial gap-filling, which is applied as the first pre-processing step, along with the post-DTS filtering are spatial-temporal methods, whereas outlier detection and the DTS are applied on one-dimensional time series at each pixel
	
<p><a href="https://www.mdpi.com/2072-4292/11/19/2201">An Empirical Assessment of the MODIS Land Cover Dynamics and TIMESAT Land Surface Phenology Algorithms</a><br>

<p>This study provides a comprehensive comparison of start of season (SOS) and end of season (EOS) phenological transition dates estimated from 500 m MODIS data based on two widely used sources of such data: the TIMESAT program and the MODIS Global Land Cover Dynamics (MLCD) product. Specifically, we evaluate the impact of land cover class, criteria used to identify SOS and EOS, and fitting algorithm (local versus global) on the transition dates estimated from time series of MODIS enhanced vegetation index (EVI). Satellite-derived transition dates from each source are compared against each other and against SOS and EOS dates estimated from PhenoCams distributed across the Northeastern United States and Canada.<br> 
	
<p><img style="float: center;" src="../images/Figure1.pdf" width="800" height="600"><br>

<b>Figure:</b> Map of four MODIS tiles and 47 near-surface PhenoCam sites used in the analysis. The background image shows the MODIS Land Cover Type product (MCD12Q1 C6) across the study region using the International Geosphere-Biosphere Programme (IGBP) classification.


