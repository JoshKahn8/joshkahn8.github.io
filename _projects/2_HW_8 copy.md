---
name: Homework Number Eight 
tools: [Python, HTML, vega-lite]
image: assets/pngs/Bigfoot_Viz1.png
description: Bigfoot sightings dataset visualizations of total sightings per state and wind speed vs. wind bearing.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Total Bigfoot Sightings by State

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart1.json" style="width: 50%"></vegachart>

# Wind Speed vs. Wind Bearing (Interactive)

<vegachart schema-url="{{ site.baseurl }}/assets/json/jsonchart2.json" style="width: 50%"></vegachart>


<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/JoshKahn8/joshkahn8.github.io/blob/main/python_notebooks/IS445%20Homework_8.ipynb" text="The Analysis" %}
</div>

