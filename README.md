# Plotly_Deploy

## Overview:

Given the [sample data](https://github.com/SoumyaAbraham/Plotly_Deploy/blob/main/samples.json) for thr Bellybutton Biodiversity experiment, we are going to create a vizualization of bacteria for each volunteer.  
Each volunteer will be able to look up their ID and find out the top 10 species found in their bellybutton. In this way, if any of the bacteria are used in the manufacturing of Improbable beef, the volunteers can see if that species is found in their navel.

## Dashboard:  

The customized dashboard has the following features:  
  1. Dropdown Menu: This dropdown menu provides the Test Subject ID number.
  2. Demographic Info: This panel shows the demographic for each selected test Subject ID.
  3. Bar Chart: Visualizing the top 10 bacteria cultures found in the navel of the selected subject.
  4. Gauge Chart: A chart showing the weekly washing frequency, displayed as a measure from 1-10 for each selected subject.
  5. Bubble Chart: A bubble chart to show the OTU IDs on the x axis and bubble color, the sample values as the y axis and marker size and the OTU labels as the hover-text value.
  
  ## Demo:
  
  This is what the page looks like:
  
  ![full_page](https://github.com/SoumyaAbraham/Plotly_Deploy/blob/main/Screenshots/full_page.png)  
  
  Taking a closer look, we have the Dropdown Menu, Demographic Info and Bar graph:
  
  ![bar_graph](https://github.com/SoumyaAbraham/Plotly_Deploy/blob/main/Screenshots/bar_graph.png)
  
  Gauge Chart:  
  
  ![gauge_chart](https://github.com/SoumyaAbraham/Plotly_Deploy/blob/main/Screenshots/gauge_chart.png)
  
  Bubble Chart:
  
  ![bubble_graph](https://github.com/SoumyaAbraham/Plotly_Deploy/blob/main/Screenshots/bubble_chart.png)  
  --
  
  You can find the code here:  
  - [Bellybutton_Chart_Code.js](https://github.com/SoumyaAbraham/Plotly_Deploy/blob/main/static/js/BellyButton_Chart_Code.js)  
  - [index.html](https://github.com/SoumyaAbraham/Plotly_Deploy/blob/main/index.html)  
  - [sample data](https://github.com/SoumyaAbraham/Plotly_Deploy/blob/main/samples.json)  
  
