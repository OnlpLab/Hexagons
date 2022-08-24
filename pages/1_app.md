---
title: App
permalink: /app/
---

## APP
The Hexagons board is a two-dimensional board paved with hexagonal tiles. 
This board is arranged in 18 columns and 10 rows. <br/>
The Hexagons App provides a drawing interface in which a user may paint tiles using a palette of eight colors  - white (default), black, yellow, green, red, blue, purple and orange. 

<button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen()">Go Full-Screen</button>

<iframe id="hexagon_app" src="https://nlp.biu.ac.il/~royi/hexagon-paper-demo-collection/#/sandbox" title="Hexagon App" style="width:100%; height:720px; border:none;"></iframe>

<script>
    function fullScreen() {
        var url = document.getElementById('hexagon_app').src;
        window.open(url, '_blank');
        
        }   
</script>

