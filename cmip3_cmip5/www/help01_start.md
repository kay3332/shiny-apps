### Getting Started

#### Introduction

This **R** Shiny web application compares downscaled outputs from CMIP3
and CMIP5 global climate models (GCMs) in a variety of ways. Downscaled
observation-based historical data from the Climatological Research Unit
(CRU 3.1) can be included in comparisons as well. Four general plot
types are available: time series plots (not time series analysis),
scatter plots, heat maps, and various plots designed more specifically
to highlight variability. Below you can find more information regarding
the data in this app, and how to manipulate and graph it.

### Exploratory Data Analysis

The plots available in the app allow for an in-depth graphical analysis
of the included downscaled climate model outputs and CRU data.
Nevertheless, they provide an exploratory as opposed to confirmatory
analysis of the data. This is not to take away from their value. Much
can be gleaned from the wide range of customizable plots which can be
produced. In fact, any confirmatory data analysis should be preceded by
exploratory data analysis. This is just to say that no inferences are
inherent in the graphs. There is no statistical modelling being
performed. It is strictly a descriptive analysis; a visual (and tabular)
representation of the data - ignoring for the moment that the GCMs
include projected model outputs out to year 2100 (or that the earlier
years of CRU data over Alaska also have increasing uncertainty), but
that has nothing to do with what this app does with the data provided to
it.

### App Layout

This is not your grandmama's R Shiny app. So let's start simple.

#### Navigation Bar

The navigation bar at the top has the typical `Home` tab, followed by a
tab for each type of plot available in the app, labelled `Time Series`,
`Scatter Plot`, `Heat Map`, and `Variability`, and finally an `About`
tab. The tabs which have to do with the actual graphical EDA are split
into left and right panels. Data selection and plot formatting occurs on
the left. Graphs and tables appear on the right.

#### Data Selection Panel

The data selection panel appears in the top left corner under the
navigation bar. But there is no reason for it to appear on the `Home`
tab, so make sure to navigate over to `Time Series` for example and then
it will become available. By default the panel is open on app launch
with the data selection checkbox checked. This reveals a number of
options. Until data selection is completed, there is nothing else to
display, no plot options panel, and of course, no plots or tables.

#### Plot Options Panel

The plot options panel appears directly beneath the data selection
panel. Similar to the data selection panel, it is visible only when
relevant. You must be on a plot tab in the navigation bar. It also does
not appear below the data selection panel if data selection has not been
completed. When displayed, the plot options panel offers a number of
powerful options for organizing the data in a plot various ways such as
grouping and faceting, as well as basic formatting options like color,
transparency, and font size.

#### Graphs and Tables

Graphs and tables appear on the right for any plot tab. Tables appear
first. Tables are ready for display as soon as data selection occurs,
even though plot options have not been set yet by the user. Once plot
options are set and a plot is generated, the plot will appear at the top
of the right panel, bumping any table further below.