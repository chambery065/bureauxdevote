<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Carte</title>
	<script  src="https://d3js.org/d3.v4.min.js" type="text/javascript"></script>
	
	
	<style>
	body {
	  background: #fcfcfa;
	}
	


	.bureaux {
	  fill: #58c5ea;
	  stroke: #fff;
	  stroke-width: .5px;
	}
	
	div.tooltip {
    position: absolute;
    text-align: center;
    color: black;
    width: 275px;
    height: 37px;
    padding: 2px;
    font: 15px sans-serif;
    background: grey;
    border: 0px;
    border-radius: 8px;
    pointer-events: none;
}
		
	

</style>
	
	
</head>


<body>


<h1>Chambéry</h1>
<p>Carte des bureaux de vote au 1er janvier 2019.</p>

<div id="map"></div>


	<script type="text/javascript">
	//dimanche 27 janvier
	
	//Largeur et hauteur du graphe
	var larg = 1500;
	var haut = 900;
	
	var projection = d3.geoConicConformal()
		    .scale(400000) //Échelle à revoir ?
		    .translate([larg / 2, haut / 2]) //Dimensions à revoir ?
			.center([5.9577, 45.5674]); //Chambéry au centre

	
	var path = d3.geoPath()
				.projection(projection);

								
	//Création de l'élément SVG
	var svg = d3.select('#map')
			.append("svg")
			.attr("width", larg)
			.attr("height", haut);
	
	var div = d3.select("body").append("div")   
    .attr("class", "tooltip")               
    .style("opacity", 0);
	

	d3.json("data/bureaux_chy_36_geoj.geojson", function(json) {
	
	svg.selectAll("path")
		.data(json.features)
		.enter()
		.append("path")
		.attr("d", path)
		.attr("class", "bureaux")
		.on("mouseover", function(d) {
            div.transition()        
                .duration(200)
                .style("opacity", .9);      
            div.html("Bureau " + d.properties.CODE  + " : " + d.properties.BUREAU)  
                .style("left", (d3.event.pageX + 30) + "px")     
                .style("top", (d3.event.pageY - 30) + "px")
        })
        .on("mouseout", function(d) {
            div.transition()
                .duration(500)
                .style("opacity", 0);
            div.html("")
                .style("left", (d3.event.pageX + 30) + "px")     
                .style("top", (d3.event.pageY - 30) + "px");
        });
   
	});
	




	
	</script>
	
	
</body>
</html>
