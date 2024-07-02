# Detecting & Mapping Ocean Platics with ML and Sentinel2

<div style="display: flex; flex-direction: row;">
    <img src="https://github.com/NSF-ALL-SPICE-Alliance/marine-debris-ML/assets/76076246/1521c60c-e40c-4b39-84ae-8feab2e8c91b" alt="SpiceLogo1" width="200"/>
    <img src="https://github.com/NSF-ALL-SPICE-Alliance/marine-debris-ML/assets/76076246/6b7b2573-7fb7-4d1e-bd82-6ee3bc99c6c1" alt="p3i-logo" width="200"/>
</div>

Student stipends for this work were funded by the Pacific Intelligence Innovation Initiative ([P3I](https://hawaiip3i.org/))



## Overview 

This work took place during June 2024 during the SPICE Summer Data Science Institute. With inspiration from [NASA-IMPACT](https://github.com/NASA-IMPACT/marine_debris_ML) we became very interested in mapping plastic debris in the ocean of the **Windward side of Oahu, Hawaii.** This interest lead us to the paper *Automatic Detection and Identification of Floating Marine Debris Using Multispectral Satellite Imagery* and it's [github repo](https://github.com/miguelmendesduarte/Floating-Marine-Debris-Data). This amazing work contains data to train a model to detect plastic using Sentinel2. We trained a decision tree model (opposed to xgboost utilized in the paper) and achieved a similiar accuracy score of __%. 

From there, we downloaded Sentinel 2 data for a bounding box off the Windward Coast of Oahu from the [Copernicus Open Access Hub](https://dataspace.copernicus.eu/). We downloaded data for Bands 1-8, 11 & 12. This data was processed utilizing the Texas Advanced Computing Center ([TACC](https://tacc.utexas.edu/)); the workflow can be found in Sentinel-Query1.ipynb. 

Lastly we utilized our trained model to make predictions on the processed data. The predictions were mapped utilizing the [geemap](https://geemap.org/) Python package


## Student Videos



https://github.com/NSF-ALL-SPICE-Alliance/marine-debris-ML/assets/76076246/55151e77-0dcb-48a4-88af-797564712fcd




https://github.com/NSF-ALL-SPICE-Alliance/marine-debris-ML/assets/76076246/482a7d8f-a038-4b2b-9361-fcfd8f30adf8




#### Students 

[Wilneris Colon ](https://github.com/wcarri)

[Johnny Bae](https://github.com/9un-Bae)

#### Mentor 

[Connor Flynn](https://github.com/ConnorFlynn)




