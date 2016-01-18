# CartoDB-2016

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <title>Carte Mapbox</title>
      <link href="cover.css" rel="stylesheet">
	  

<script src="http://libs.cartocdn.com/cartodb.js/v3/3.15/cartodb.js"></script> 	  
<link rel="stylesheet" href="http://libs.cartocdn.com/cartodb.js/v3/3.15/themes/css/cartodb.css" /> 

<style>
  body { margin:0; padding:0; }
  #map { width: 1200px; height:600px; margin:100px; padding:10px; background: black;}
  </style>	  
	  
  </head>

  
  
  <body>
      <div class="site-wrapper-inner">
      <div class="inner">
      <h3 class="masthead-brand">Carte intercative du métro rennais</h3>
  
  <div id='map'></div>

<script>

window.onload = function() { cartodb.createVis('map', 'https://mastersigat.cartodb.com/api/v2/viz/979c7816-0556-11e5-bf47-0e4fddd5de28/viz.json'); } 

</script>
    
  </body>
</html>
