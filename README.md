# lidar-fog-atto

This repository is about a scientific inicitiation that I've developded during my graduation in Physics at University of São Paulo (USP) at the LAF (Laboratory of Atmospheric Physics). The project title is: Lidar measurements of fog occurrence at the ATTO tower.

The main objective of this project is to study the correlation between fog occurrence during the dawn and the shallow cloud cover in the morning at the ATTO (Amazon Tall Tower Observatory), located in the Amazon forest. To do so, I've analyzed daily data recorded by a ceilometer - an instrument that works like a LiDAR (Light Detection and Range), emitting light to the atmospheric and recording the amount of light (photons) that is backscattered, being able to detect clouds and inform their heights -  in the period from sep/21 to aug/22. All the files can be founded at [LFA website](https://lfa.if.usp.br/)

To perform the analysis I've used Python, more specifically Pandas, Matplotlib, Numpy, Datetime and netCDF4 - a library that helped me to decode the files that were delivered by the equipment. NetCDF is a common file extension for scientific data, because it allows you to include metadata about de file itself. In the ceilometer case, the metadata contained information about the variables - what they meant, their unities, etc. This was essential to know which variables to use during the analyzes.

You can find a lot more information about netCDF4 library in this link [Documentation_netCDF4](https://unidata.github.io/netcdf4-python/)

The main deliverable of this project was a 2D histogram showing the vertical distribution of clouds during the day (consolidated) during two typical periods at the amazon forest - dry and rainy. I've also analysed the quality of the data, discarding those who didn't attend some criterias - like presenting a positive signal during all measures - and produced a graph showing the variation in cloud cover during the day in cases where there was (or not) fog. You can find the resume of my project in this repository.
