# More about visualizatoins, aesthetics, and annotations

## Create data visualization in R

Way of creating visuals

* ggplot2 - grammar of graphics
  * Create different types of plots
  * Customize the look and feel of plots
  * Create high quality visuals
  * Combine data manipulation and visualization
* Plotly
* Lattice
* RGL
* Dygraphs
* Leaflet
* Highcharter
* Patchwork
* gganimate
* ggridges

Other notable notes

* Aesthetics
  * Visual property of a visual in a plot
* Geoms
  * Geometric object to represent the data
* Facets
  * Let you display smaller groups or subgroups
* Labels and annotations
  * Let you customize the plot.  Titles and such.

### Sample code dissection for ggplot

ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g))

* ggplot(data = table) - creates a coordinate system that you can add layers to
* '+' - adds a layer to the plot
* geom_point() - Uses points to create scatterplots
  * geom_bar() - bar charts and so on
* (mapping = aes(x = x-axis, y = y-axis)) - ggplots need a mapping argument as apart of the call which is paired with the aes() function.
  * aes() defines the axis

Common errors for plots can be found [here](https://d18ky98rnyall9.cloudfront.net/pALIn_4vSECCyJ_-L4hAJg_3c83255ab5004b1a99957907331217b0_Common-problems-encountered-when-visualizing-in-R.pdf?Expires=1661472000&Signature=Jpc1WieefZFE36kGoertqeJ4OhHbszCgBk7pOol4l1R8nONQV84U7kzbSGOat1R71wbxvk45APGnG6G5YIMNeuwLlCXT~rMKYWNTEP0S6anQZes-VtFjjqlSUdXlfty5YFcendobI~-viRpVhPmYHEEsy~6~W3qaNK-CjwRtuKg_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

## Explore aesthetics in analysis

End arguments in the aes() can allow for different visualizations such as color, size, and other features.

All the code inside an aes() maps things to the individual data itself instead of to the whole graph

Geom - The geometrical object used to represent your data

* points
* bars
* lines

Smoothing

* Loess - For plots with less than 1000 points
* Gam - For plots with more points

Faceting

* facet_wrap(~column)
* facet_grid()

## Annotate and save visualizations

label function labs()

* titles
* subtitles
* captions

Within labs() can specify title, caption, or annotate

ggsave() - saves the current plot to the filename provided as an argument
