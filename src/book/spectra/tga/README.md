# Thermogravimetric analysis

This module allows visualizing and processing TGA curves. You can upload `txt` files and `jcamp` files.

![Screenshot of the TGA analysis module](images/analysis.png)

## Upload

Files can be uploaded either by drag-and-drop to the field on the left-hand-side (1 in the image) or automatically from the instrument. The files will appear in field 2. Note that you can only upload files to samples to which you have write access.

## Visualization

To add patterns to the visualizer, click on the `+` in field 1. The sample will then appear in field 3 from which you can control the visualization settings.

If you click on the color in a row, you can select any color you which for the line and you can use the control buttons in the top right corner of field 3 to control which figures you show in a spectrum.

In the chart you can draw a rectangle to zoom and double click to reset. You can move the graphs by pressing `SHIFT` while dragging them.

Currently, we can display weight vs. temperature and weight vs. time. A percentage-weight-loss view is currently being implemented.

## Processing

Field 4 gives you some basic processing tools. For example, you can get the derivatives of the patterns or normalize it. To scale the maximum intensity to one, you should use the `Rescale (x to y)` option.

## Feature requests and support

If you need additional tools and support for this module, [Open an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue) on the [tga-spectrum GitHub repository](https://github.com/cheminfo/tga-spectrum) or simply post a question on the [forum](https://groups.google.com/forum/#!forum/cheminfo).