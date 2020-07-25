# Interactive directions map with OSM and networkx
<center>
<img src="https://media.giphy.com/media/fUqYN5JP8wcne0yaOd/giphy.gif" width="500" height="auto" />
</center>

<center>
<img alt="License" src="https://img.shields.io/badge/made%20by-tallesfelix-brightgreen">
<img alt="License" src="https://img.shields.io/github/license/tallesfelix/directions-with-osm-networkx">
</center>

This is a simple example that deals with interactive map **directions between two geolocated points**, using data retrieved from Open Street Map and Networkx graphs! 

<p align='center'>
	<a href="https://medium.com/@tallesfelixg95/interative-map-with-osm-directions-and-networkx-582c4f3435bc">MEDIUM POST</a>
</p>

# Getting started
You must first download and install  [Miniconda](https://docs.conda.io/en/latest/miniconda.html).

Then execute these commands to create and configure your environment:
```
conda create -n directions-example
conda activate directions-example 
conda config --env --add channels conda-forge  
conda config --env --set channel_priority strict  
conda install python=3.7 osmnx ipyleaflet networkx jupyter  
jupyter notebook
```
## Built With

* [OSMNX](https://github.com/gboeing/osmnx)- Used to get Open Street Map data
* [Networkx](https://networkx.github.io/)- Used to handle the graph 
* [Ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/)- Used to plot the map
