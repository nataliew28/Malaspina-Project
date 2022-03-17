# Malaspina-Project

# Motivation:
The Malaspina Glacier located in SE Alaskan coast, is currently retreating very quickly due to a number of reasons including climate-induced forcing factors. As it reatreats, the remnant debris-covered ice left-over in areas where the glacier used to be has started to melt and form lake systems that expand outward as melting increases. Due to the glacier's proximity to the coast there is a very real concern that relatively warm tidal intrusions from the ocean could connect with the expanding lakes that are forming in from of the glacier. If this were to happen, then the warm tidal intrusions form the ocean would trigger a mass melting event on scale we've never seen in our lifetime. The area of the entire glacier is roughly that of Rhode Island. If all that ice were to suddenly melt over the course of a few decades, the affects on surroudning ecosystems would undoubtedly be permanent and far-reaching to an unknown degree. In order to model and predict if, when, and where the ocean might gain access to the main glacial lobe, transient electromagnetics are used to map the presence and thickness of subsurface ice in regions surrounding the glacier.

# Program:
The purpose of this project is to model the observed transient electromegnetic (TEM) data our team collected from Malaspina Glacier, AK using the open-source Python package Simulation and Parameter Estimation in Geophysics (SimPEG). 

The execution of this program pulls in a raw .usf data file to be parsed into separate useable channels of data. The observed data is modeled by varying the resistivity and thickness parameters for the surface layer of a 3-4 layer earth model. The program creates a separate simulated data set for each thickness and resistivity value within a set range. These simulations are then plotted with the observed data, and the RMSE is calculated for each simulation to determine the best pair of parameters to model the data.

NOTE: This project is currently in progress and will be used in my thesis, as such I cannot provide the our data publicly yet. I will be working on an example "real" dataset to provide for example executions. 


  
