# Charts

--

## Line chart from JSON string

<div style="height:480px">
<canvas data-chart="line" >
<!--
{
 "data": {
  "labels": ["January"," February"," March"," April"," May"," June"," July"],
  "datasets":[
   {
    "data":[65,59,80,81,56,55,40],
    "label":"My first dataset","backgroundColor":"rgba(20,220,220,.8)",
    "borderColor": "rgba(20,220,220,.8)"
   },
   {
    "data":[28,48,40,19,86,27,90],
    "label":"My second dataset","backgroundColor":"rgba(220,120,120,.8)",
    "borderColor": "rgba(220,120,120,.8)"
   }
  ]
 }
}
-->
</canvas>
</div>

--

## Bar chart with CSV data

<div style="height:480px">
<canvas data-chart="bar" >
,January, February, March, April, May, June, July
My first dataset, 65, 59, 80, 81, 56, 55, 40
My second dataset, 28, 48, 40, 19, 86, 27, 90
</canvas>
</div>

--

## Stacked bar chart from CSV file with JSON configuration

<div style="height:480px">
<canvas data-chart="bar" data-chart-src="data/chart-data.csv">
<!-- 
{
"data" : {
"datasets" : [{ "backgroundColor": "#0f0" }, { "backgroundColor": "#0ff" } ]
},
"options": { "scales": { "x": { "stacked": true }, "y": { "stacked": true } } }
}
-->
</canvas>
</div>

--

## Pie chart

<div style="height:480px">
<canvas data-chart="pie">
,Black, Red, Green, Yellow
My first dataset, 40, 40, 20, 6
</canvas>
</div> 
