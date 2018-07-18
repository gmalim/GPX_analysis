# GPX data analysis

This repository contains some Python test code to analyze and visualize GPX data. GPX (GPS Exchange Format) is an XML based file format for GPS tracks, and is widely used by dozens of software programs and web services for GPS data analysis and visualization. 

## Prerequisites:

Data manipulation is done using [gpxpy](https://github.com/tkrajina/gpxpy), a GPX parser for Python, and the [NumPy](http://www.numpy.org/) and [Pandas](https://pandas.pydata.org/) data analysis packages for Python. Visualization is done using [matplotlib](https://matplotlib.org/), [mplleaflet](https://github.com/jwass/mplleaflet), [gmplot](https://github.com/vgm64/gmplot) and [folium](https://github.com/python-visualization/folium).

## Analysis:

This repository contains two analyses of some example GPX running data (see [data](data) directory) in the form of Python Jupyter Notebooks that are best viewed online using [Jupyter nbviewer](https://nbviewer.jupyter.org/), which has improved display rendering capabilities compared to Github:

1. Single file: [*GPX_analysis_singlefile.ipynb*](https://nbviewer.jupyter.org/github/gmalim/GPX_analysis/blob/master/GPX_analysis_singlefile.ipynb)
2. Multiple files: [*GPX_analysis_multiplefiles.ipynb*](https://nbviewer.jupyter.org/github/gmalim/GPX_analysis/blob/master/GPX_analysis_multiplefiles.ipynb)

## Results:

The analyses produce the following [leaflet](https://leafletjs.com/) maps:

1. Single file: 
	- [*mplleaflet_map.html*](https://gmalim.github.io/GPX_analysis/mplleaflet_map.html)
	- [*folium_map.html*](https://gmalim.github.io/GPX_analysis/folium_map.html)
2. Multiple files:
	- [*gmplot_heatmap.html*](https://gmalim.github.io/GPX_analysis/gmplot_heatmap.html)
	- [*folium_heatmap.html*](https://gmalim.github.io/GPX_analysis/folium_heatmap.html)


