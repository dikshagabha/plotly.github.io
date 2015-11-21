---
layout: excel-tutorial-single_layout
title: Create a Pareto Chart with Plotly and Excel
subtitle: A Step-by-Step Guide to Create a Pareto Chart
permalink: /excel/pareto-chart
imageurl: 
state: inactive
tags: excel
meta_description: Create a Pareto chart. Easily make interactive graphs online and for free with Plotly.
popularity: featured
section: BasicCharts
actioncall: Created a Pareto Chart with Plotly
actioncall-url: https://plot.ly/7162/~Dreamshot/?plot_type=Line%20plot
download-url: https://raw.githubusercontent.com/plotly/datasets/master/pareto-chart.csv

similar:
 - title: Make a Graph with Three Y Axes
   url: /excel/3-y-axes
   imgurl: http://images.plot.ly/excel/3-y-axes-excel/three-axes-thumb.png
 - title: Make a Graph with Mulitple Y Axes
   url: /excel/multiple-axes/
   imgurl: http://images.plot.ly/excel/multiple-axes-excel/double-axes-chart-thumb.png
 - title: Add Maps to a Dashboard
   url: /excel/dashboard/
   imgurl: http://images.plot.ly/excel/dashboards/dashboards-thumbnail.png

otherlang: Know how to program? See how to create this in [Python](https://plot.ly/python/shapes/) or [R](https://plot.ly/r/shapes/).

live-graph: <iframe width="100%" height="800" frameborder="0" scrolling="no" src="https://plot.ly/~Dreamshot/7164.embed"></iframe>

steps:
 - title: About a Pareto Chart
   sub-steps:
    - copy: "A Pareto chart combines a bar and line chart. The Pareto principle states that, 'for many events, roughly 80% of the effects come from 20% of the causes.' In this example, we will see that 80% of complaints come from 20% of the complaint types."
       img: "![Pareto principle](http://images.plot.ly/excel/pareto-chart-excel/pareto-principal-pareto-chart.jpg)"
 - title: Upload your Excel data to Plotly's grid
   sub-steps:
    - copy: "Open the data file for this tutorial in Excel. You can download the file here in [CSV format](https://raw.githubusercontent.com/plotly/datasets/master/pareto-chart.csv)"
      img: "![Excel view](http://images.plot.ly/excel/shaded-region-excel/excel-view-shaded-region.png)"
 - title: Head to Plotly
   sub-steps:
    - copy: "Head to [Plotly's Workspace](https://plot.ly/plot) and sign into your free Plotly account. Go to 'Import,' click 'Upload a file,' then choose your Excel file to upload. Your Excel file will now open in Plotly's grid. For more about Plotly's grid, see [this tutorial](help.plot.ly/add-data-to-the-plotly-grid/)"
      img: "![Import data](http://images.plot.ly/excel/pareto-chart-excel/import-pareto-chart.png)"
 - title: Creating Your Chart
   sub-steps:
    - copy: "Once you've loaded the data in Plotly, label your columns like we did below. You'll have complaint type on the x axis data and percentage on the y axis data. Then, select 'Line plots' from the CHOOSE PLOT TYPE menu. When you're finished, click on the blue 'LINE PLOT' button in the sidebar."
      img: "![Grid](http://images.plot.ly/excel/pareto-chart-excel/grid-pareto-chart.png)"
    - copy: "Your plot would initially look something like this."
      img: "![Original](http://images.plot.ly/excel/pareto-chart-excel/original-pareto-chart.png)"
    - copy: "In order recreate a typical Standard Normal Probability Density Function graph, we'll smooth out the traces. Head to the 'Traces' menu and select 'All traces' within the drop down menu. Click the 'Style' menu and select the smooth 'Shape' as we highlight in the image below."
      img: "![Smooth](http://images.plot.ly/excel/shaded-region-excel/smooth-shaded-region.png)"
    - copy: "Take a moment to resize your plot to something less wide. A width of 800 and a height of 600 seems reasonable. Head to the layout menu to do this."
      img: "![Resize](http://images.plot.ly/excel/shaded-region-excel/resize-shaded-region.png)"
    - copy: "With our particular data, a normal score range is -1 to 1, so we'll shade that region. Head to the 'Traces' menu and select 'Col4' from the drop down menu. Then, within the 'Fill To' area, select 'Y=0.' Your plot should then look similar to the one below."
      img: "![Shade](http://images.plot.ly/excel/shaded-region-excel/shade-shaded-region.png)"
    - copy: "For clarification, we'll revist our grid. Since we wanted the region between -1.0 and 1.0 shaded, our second x-y combination contained values up to -1 and 1. If we wanted the region between -1.5 and 1.5 shaded, for instances, we would have included those values in our second x-y combination. We've highlighted the extra steps to illustrate this difference; it all depends on your indivdual shading needs!"
      img: "![Grid2](http://images.plot.ly/excel/shaded-region-excel/grid2-shaded-region.png)"
 - title: Finalizing Your Graph
   sub-steps:
    - copy: "Your graph should now look something like this."
      img: "![Final](http://images.plot.ly/excel/shaded-region-excel/final-shaded-region.png)"
    - copy: "Head to the 'Traces' menu and then the 'Style' tab to set the trace color to your liking. You can title your graph and axes like we did. You can also blank out the legend, as it is not particularly necessary for this graph. Hide the legend within the 'Legend' menu."
      img: "![Styling](http://images.plot.ly/excel/shaded-region-excel/styling-shaded-region.png)"
    - copy: "Here's our finished graph."
      img: "![Finished](http://images.plot.ly/excel/shaded-region-excel/finished-shaded-region.png)"
    - copy: "You can download your finished Plotly graph to embed in your Excel workbook. We also recommend including the Plotly link to the graph inside your Excel workbook for easy access to the interactive Plotly version. Get the link to your graph by clicking the 'Share' button. Download an image of your Plotly graph by clicking EXPORT on the toolbar."
      img: "![Export](http://images.plot.ly/excel/shaded-region-excel/export-shaded-region.png)"
    - copy: "To add the Excel file to your workbook, click where you want to insert the picture inside Excel. On the INSERT tab inside Excel, in the ILLUSTRATIONS group, click PICTURE. Locate the Plotly graph image that you downloaded and then double-click it. Notice that we also copy-pasted the Plotly graph link in a cell for easy access to the interactive Plotly version."
      img: "![Excel workbook](http://images.plot.ly/excel/shaded-region-excel/excel-workbook-shaded-region.png)"
---