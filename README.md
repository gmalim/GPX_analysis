# GPX data analysis

This repository contains some Python test code to analyze and visualize GPX data. GPX (GPS Exchange Format) is an XML based file format for GPS tracks, and is widely used by dozens of software programs and web services for GPS data analysis and visualization. 

## Prerequisites:

Data manipulation is done using [gpxpy](https://github.com/tkrajina/gpxpy), a GPX parser for Python, and the [NumPy](http://www.numpy.org/) and [Pandas](https://pandas.pydata.org/) data analysis packages for Python. Visualization is done using [matplotlib](https://matplotlib.org/), [folium](https://github.com/python-visualization/folium), [mplleaflet](https://github.com/jwass/mplleaflet) and [gmplot](https://github.com/vgm64/gmplot).

## Analysis:

This repository contains two analyses of some example GPX running data (see [data](data) directory) in the form of Python Jupyter Notebooks that are best viewed online using [Jupyter nbviewer](https://nbviewer.jupyter.org/), which has improved display rendering capabilities compared to Github:

1. [*GPX_analysis_singlefile.ipynb*](https://nbviewer.jupyter.org/github/gmalim/GPX_analysis/blob/master/GPX_analysis_singlefile.ipynb) (one run)
2. [*GPX_analysis_multiplefiles.ipynb*](https://nbviewer.jupyter.org/github/gmalim/GPX_analysis/blob/master/GPX_analysis_multiplefiles.ipynb) (multiple runs)

## Results:

The analyses produce the following HTML maps:

- [*folium_map.html*](https://gmalim.github.io/GPX_analysis/folium_map.html) (leaflet map)
- [*mplleaflet_map.html*](https://gmalim.github.io/GPX_analysis/mplleaflet_map.html) (leaflet map)
- [*gmplot_heatmap.html*](https://gmalim.github.io/GPX_analysis/gmplot_heatmap.html) (heatmap)


