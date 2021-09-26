# charts

![img](https://canvasjs.com/wp-content/uploads/images/gallery/javascript-charts/overview/javascript-charts-graphs-index-data-label.png)

## Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create

- Drawing a line chart

`<canvas id="buyers" width="600" height="400"></canvas>`

- Drawing a pie chart

`<canvas id="countries" width="600" height="400"></canvas>`

`var countries= document.getElementById("countries").getContext("2d"); new Chart(countries).Pie(pieData, pieOptions);`

- Drawing a bar chart

`<canvas id="income" width="600" height="400"></canvas>`

` var income = document.getElementById("income").getContext("2d"); `

` new Chart(income).Bar(barData); `
