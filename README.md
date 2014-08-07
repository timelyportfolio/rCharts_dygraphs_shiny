rCharts + shiny + dygraphs -> maybe a good combination
======================

In the rChartsDygraph project, one of the [first issues](https://github.com/danielkrizian/rCharts_dygraphs/issues/2) was how do I integrate my fancy new rCharts-generated dygraphs in [shiny](http://shiny.rstudio.com/).  While I first thought that this would require changes to rChartsDygraph, I actually discovered that changes to rCharts would probably best solve the problem and add flexibility for future rCharts extra libraries.

To run this, install the newest version of shiny, and then use `runGitHub`.  Altogether, the code will look something like this:

```
#install.packages("shiny")
#require(devtools)


require(shiny)
runGitHub("rCharts_dygraphs_shiny","timelyportfolio")
```
