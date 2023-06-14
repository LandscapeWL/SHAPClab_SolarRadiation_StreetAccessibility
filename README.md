# SHAPClab_UrbanPerception_SpatiotemporalChanges
# Urban Heat Comfort Evaluation Based on Accessibility and Solar Radiation Analysis

This project presents a comprehensive approach for evaluating urban heat comfort based on a detailed analysis of accessibility and solar radiation data for urban streets. The system developed here uses cutting-edge geospatial analysis techniques and high-resolution solar radiation simulations to provide insightful, actionable information to urban planners and other interested parties.

## Overview

The system has been designed to give a better understanding of urban heat comfort by combining two primary factors - accessibility and solar radiation. In this context, accessibility is a measure of how easily a location can be reached from other locations in a city. Solar radiation is a key contributor to thermal comfort. The results of this analysis can be used by city planners to design more thermally comfortable cities.

The top 20% most accessible streets are classified as highly accessible, while streets with the highest 20% solar radiation are considered high radiation streets. Conversely, streets with the lowest 20% solar radiation are classified as low radiation streets. A combination of these geospatial positions is used to identify areas with high accessibility but different levels of solar radiation.

In areas with high accessibility, high solar radiation indicates that people may feel hotter due to direct sun exposure and experience poor thermal comfort. On the other hand, low solar radiation indicates that people may feel less direct sun exposure, thus experiencing better thermal comfort and urban shading effects.

## Key Features

1. **Highly Accurate Solar Radiation Simulation**: This project uses high-resolution data and advanced algorithms to simulate the amount of solar radiation received on different streets in the city.

2. **Accessibility Analysis**: The project also includes a detailed accessibility analysis of city streets, which provides valuable information about how easy it is for people to reach different parts of the city.

3. **Combined Analysis of Solar Radiation and Accessibility**: By combining solar radiation data with accessibility information, this project offers a more comprehensive understanding of urban heat comfort. This combined analysis can highlight areas of the city that are both highly accessible and have either high or low solar radiation.

4. **Visualisation**: The project also provides clear visual representations of the data, making it easier for city planners and other stakeholders to understand and act on the information provided.

This project provides a powerful tool for understanding and improving urban heat comfort, and we hope it will be useful to urban planners and researchers around the world.

![UrbanPerceptionchange](http://m.qpic.cn/psc?/V51wK6B50SnpHF0Ql90V120XkX2YMvAu/bqQfVz5yrrGYSXMvKr.cqefeDUb0jFbQhmCaFt.3Dg.nKcdg41gydpM9DDsYZ5VmyOEcXxIKeDIW8swEvDZ3FEmU6gBksVj4vuHMleLwRGY!/b&bo=IQdABiEHQAYBByA!&rf=viewer_4 "UrbanPerceptionchange")
# Information
The research is carried out under the SHAPC-lab and the lab director & the corresponding author:Jie He academic social networks page:<br>
http://faculty.hitsz.edu.cn/hejie

For more information related to the research, please follow the laboratory's WeChat Official Account:<br>
![空间人文与场所计算](http://m.qpic.cn/psc?/V51wK6B50SnpHF0Ql90V120XkX2YMvAu/bqQfVz5yrrGYSXMvKr.cqaGvn*U8.XtKGUKoCXp2T7*rr64Fh949noTXvtqynumAfdG91L2EpB0ozp5TDQDefp4ivWRqPAlBcUTccYj7QHE!/b&bo=lgGcAZYBnAEBByA!&rf=viewer_4 "空间人文与场所计算")
# Requirements
- Jupyter notebook
- ArcGIS software
# Python Requirements
- Pillow
- GeoPandas
- Numpy
- Matplotlib
- sklearn
# Usage
- Processing solar radiation source code<br>
`processing_code`<br>
- Street View mete information<br>
`streetview_data`<br>
- Solar radiation result and street view collection point data<br>
`gis_data`<br>
