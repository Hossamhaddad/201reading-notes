# Charts.js
## Charts displaying data visually better than tables, They’re easier to look at and convey data quickly .
##  Chart.js is  a JavaScript plugin that uses HTML5’s < canvas> element to draw the graph onto the page.

### Example for drwaing a line chart : 
< canvas id="buyers" width="600" height="400">< /canvas>

< script>
    var buyers = document.getElementById('buyers').getContext('2d')
    
    new Chart(buyers).Line(buyerData);

< /script>

var buyerData = {
	labels : ["January","February",
    "March","April","May","June"],
	
    datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}
 ## We can also draw : 
 1. #### Drawing a pie chart
 2. #### Drawing a bar chart

 ### You can download the latest version of Chart.jsfrom the GitHub releases or use a Chart.js CDN. 
  ## It's easy to get started with Chart.js. All that's required is the script included in your page along with a single < canvas> node to render the chart.

 ## Examples to make the chart only respond to click events : 
 var chart = new Chart(ctx, {

    type: 'line',

    data: data,

    options: {

        // This chart will not respond to mousemove, etc
        events: ['click']
    }
});
## Some Interaction Modes:
## Point
var chart = new Chart(ctx,
 {
    
    type: 'line',
    data: data,
    options: {
        tooltips: {
            mode: 'point'
        }
    }
});
## Nearest 
var chart = new Chart(ctx, {

    type: 'line',
    data: data,
    options: {
        tooltips: {
            mode: 'nearest'
        }
    }
});
## We also can control colors and fonts.

## the < canvas> element requires the closing tag   < /canvas> .

## Example to draw a rectangles :
 function draw( ) {

  var canvas = document.getElementById('canvas');

  if (canvas.getContext) {

    var ctx = canvas.getContext('2d');


    ctx.fillRect(25, 25, 100, 100);

    ctx.clearRect(45, 45, 60, 60);
    ctx.strokeRect(50, 50, 50, 50);
  }
}
 ## A strokeText example : 
 function draw() {

  var ctx = document.getElementById('canvas').getContext('2d');

  ctx.font = '48px serif';
  ctx.strokeText('Hello world', 10, 50);

}
