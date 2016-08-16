Kismet-Heatmap
==============

This repository contains a python program that interpolates heatmaps from Kismet gpsxml output. The current directory will be filled with PNG files at a size of 1000x1000 containing the heatmap named by its BSSID. These files are accompanied by PNGW files, a World File which describes how the image should be presented in a geospatial tool as Qgis.

This code was created because I have been disappointed with the performance and innerworkings of kis-heat and the poor results of the interpolation and heatmap functions in Qgis.


Usage
=====

gpsxml2png.py /path/to/Kismet.gpsxml
