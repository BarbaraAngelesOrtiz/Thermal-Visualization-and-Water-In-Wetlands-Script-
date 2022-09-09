# Thermal Visualization and Water In Wetlands Script 

[Show](README.md) script or [download](script.js)

 ## Evaluate and visualize
 
[EO Browser](https://sentinelshare.page.link/bjQi) {:target="_blank"}

 ## General description of the script
 
In the midst of an unprecedented heat wave and ongoing drought, northeastern Argentina suffered a series of forest fires in nature reserves and fields. In mid-January 2022, sweltering heat gripped central South America and temperatures soared to more than 40°C (104°F). At the time, Argentina was the hottest place on the planet.[2] 

La Niña coupling of the atmosphere and ocean alters global atmospheric circulation and can cause shifts in the path of mid-latitude jet streams in ways that intensify rainfall in some regions and bring drought to others.[3] Corrientes, which normally averages 162 millimeters (6.5 inches) of rain during February, has received less than 20 millimeters (1 inch) so far, according to the National Meteorological Service (SMN).[1]

Since the fires began in December, more than 520,000 hectares (1.3 million acres) have burned, killing wildlife and livestock, decimating pasturelands, and destroying crops such as yerba mate and rice. [1] On February 7, 2022, Corrientes was declared a state of emergency and an agricultural disaster.

Through the Sentinel Hub EO Browser tool, these 2 custom scripts are programmed, using satellite data from Landsat 8-9 OLI-TIRS Collection 2 Level 1 Data. Where through the fusion of data it is possible to observe in a single graph the temperature of the surface and the humidity of the wetlands. The aim is to prevent and be able to carry out the necessary tasks to minimize this natural disaster, whose protagonists are drought and the protection of wetlands.

### Thermal Visualization Script: 
This heat shield is based on band 10. At the central wavelength of 10895nm, it measures in the thermal infrared or TIR. Instead of measuring the temperature of the air, as weather stations do, band 10 reports on the ground, which is usually much hotter. Thermal band 10 is useful for providing surface temperatures and is collected at 100 meter resolution.[5]

### Water In Wetlands Script:
WIW is a remote sensing tool for monitoring water in wetlands. One of the main challenges is to detect the water under the vegetation cover and wetlands are usually characterized by the presence of emergent plants of variable height and density. The reflectance values of the corresponding pixels of the optical spectral bands of the Landsat sensors were used as reference. The overall accuracy of the water maps constructed using the WIW ranged from 89% to 94% for both the training and validation samples. Landsat 8: WIW = NIR = 0.1735 and SWIR2 = 0.1035 [6]


 ## Details of the script
 
 The images acquired by the Operational Land Imager-2 (OLI-2) on Landsat 9 on February 16, 2022, show the scorched fields and heavy smoke from the multiple wildfires still burning near Iberá National Park.[1]
 
![Figura 0](https://user-images.githubusercontent.com/105976212/189240786-2bac29db-3056-4476-8ca7-b93c881e84ce.jpg)

Here you can see in detail different critical points of February 16, 2022, being 1, 2 and 3 the main sources of fire. Script A is the one that indicates temperature and humidity of the wetlands, where the darker the red color, the higher the temperature. Script C is a temperature impact analysis reference, this indicates higher temperature with white color. [4]

![aFig2_16-2-22](https://user-images.githubusercontent.com/105976212/189244008-1e9dc89c-1a8d-4bb5-a97c-894c9d0b13d2.png)

Point 4 and 5 are critical fire points. If we analyze the area marked by point 6, we can see that on February 8, 2022 the temperature on the surface was high and if we compare the humidity of the area with the previous scripts on February 16, there is a drought mark causing more outbreaks of forest fire.

![aFig1_8-2-22](https://user-images.githubusercontent.com/105976212/189244163-d3615999-89f3-470f-a5e8-af032572e1e7.png)

In addition, Timelapse of the area analyzed from November 2021 to March 2022 is observed below (week interval), where it is seen how the humidity of the wetlands and the temperature on the surface vary. 

![AWS_LOTL1-500618976762302-timelapse](https://user-images.githubusercontent.com/105976212/189212267-45dd173d-4b0d-45fd-8684-ab82434e7f10.gif)
 

 ## Author of the script
 
 Barbara de los Angeles Ortiz
 
 ## References
 
 [1] Earthobservatory Nasa, March 01 2022,  [Earthobservatory.nasa.gov/Wildfires Ravage Corrientes, Argentina](https://earthobservatory.nasa.gov/images/149478/wildfires-ravage-corrientes-argentina)
 
 [2]  Earthobservatory Nasa, January 11 2022, 2022[Earthobservatory.nasa.gov/Southern Hemisphere Scorchers](https://earthobservatory.nasa.gov/images/149331/southern-hemisphere-scorchers)
 
 [3] Earthobservatory Nasa, December 01 2021,  [Earthobservatory.nasa.gov/La Niña Returns for a Second Winter](https://earthobservatory.nasa.gov/images/149201/la-nina-returns-for-a-second-winter)
 
 [4] Mohor Gartner, 2019, [Land Surface Temperature (LST) Mapping Script]([https://earthobservatory.nasa.gov/images/149478/wildfires-ravage-corrientes-argentina](https://github.com/sentinel-hub/custom-scripts/tree/master/landsat-8/land_surface_temperature_mapping))
 
 [5] Sentinel Hub [About Landsat 8-9 OLI-TIRS Collection 2 Level 1 Data](https://docs.sentinel-hub.com/api/latest/data/landsat-8/)
 
 [6] Sentinels Copernicus, 05 September 2019, ([Track changes in seasonal water of wetlands](https://sentinels.copernicus.eu/web/success-stories/-/copernicus-sentinel-2-helps-track-changes-in-seasonal-water-of-wetlands)


