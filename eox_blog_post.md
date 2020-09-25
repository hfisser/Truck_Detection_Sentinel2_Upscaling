## Sentinel-2 truck detection - upscaling

Can we detect moving trucks using Sentinel-2 data? Normally, targeting objects of this size at 10 m resolution does not seem promising. Still, Henrik Fisser, Master's student at the University of Würzburg, presented a method that enables to detect moving trucks with Sentinel-2 data and won the first prize of the [Euro Data Cube COVID-19 Custom Script Contest](https://www.sentinel-hub.com/contest-covid/) with this contribution. The method exploits an effect of the Sentinel-2 Multispectral Instrument (MSI) that sees moving objects not once per spectral band at slightly different times. Due to this effect objects of sufficient size appear spectrally disassembled in the data, which makes them detectable based on the unusual spectral signature.
<p align="center">
<img src="https://github.com/hfisser/Truck_Detection_Sentinel2_Upscaling/blob/master/2018-04-19_france.jpeg"width=400/>
</p>

*Fig. 1: Truck detection example in southern France*

Having proven the concept, Henrik Fisser scaled up the truck detection to the area of the whole EU for integration into the [Rapid Action on Coronavirus and EO (RACE)](https://race.esa.int/) dashboard. The derived truck information may indicate how truck traffic has developed during the COVID-19 pandemic compared to normal years.
All data processing was implemented on [Euro Data Cube](https://eurodatacube.com/) resources. In the Euro Data Cube session at [ESA EO Phi-Week](https://phiweek.esa.int/programme) Henrik is going to present his work on Sentinel-2 truck detection and the upscaling to the whole EU.

Join the ESA EO Phi-Week side event 'Euro Data Cube - Furnishing the “EO Workplace” with Data and Tools for Effectiveness and Production' on Thursday, 1st of October, from 11.30 AM. 
