# GPX data analysis

This repository contains some Python code to analyze and visualize GPX data. GPX (GPS Exchange Format) is an XML based file format for GPS tracks, and is widely used by dozens of software programs and web services for GPS data analysis and visualization. 

## Prerequisites:

Data manipulation is done using [gpxpy](https://github.com/tkrajina/gpxpy), a GPX parser for Python, and the [NumPy](http://www.numpy.org/) and [Pandas](https://pandas.pydata.org/) data analysis packages for Python. Visualization is done using:

1. [matplotlib](https://matplotlib.org/)
2. [folium](https://github.com/python-visualization/folium)
3. [mplleaflet](https://github.com/jwass/mplleaflet)
4. [gmplot](https://github.com/vgm64/gmplot)

## Analysis:

This repository contains two analyses in the form of Python Jupyter Notebooks that can be viewed online using [Jupyter nbviewer](https://nbviewer.jupyter.org/), which has improved display rendering capabilities compared to Github:

1. [Single file analysis](https://nbviewer.jupyter.org/github/gmalim/GPX_analysis/blob/master/GPX_analysis_singlefile.ipynb)
	- [Resulting folium map](https://gmalim.github.io/GPX_analysis/folium_test.html)
	- [Resulting mplleaflet map](https://gmalim.github.io/GPX_analysis/mplleaflet_test.html)

2. [Multiple file analysis](https://nbviewer.jupyter.org/github/gmalim/GPX_analysis/blob/master/GPX_analysis_multiplefiles.ipynb)
	- [Resulting heatmap](https://gmalim.github.io/GPX_analysis/index.html)
