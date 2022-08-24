---
title: Gallery
permalink: /gallery/
---

## Image Gallery

<button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen()">Go Full-Screen</button>

This gallery displays all the images used in the Hexagons dataset and is organized  by categories. 
Once you select an image, insert its associated drawing procedures in the [Visualization](/Hexagons/visual). 
As a rule, each image is associated with three <i> different </i> drawing procedures. 

<iframe id="data_visualization" src="https://nlp.biu.ac.il/~royi/hexagon-paper-visualization-res/#/task-gallery" title="Dataset Visualization" style="width:100%; height:720px; border:none;"></iframe>

<script>
    function fullScreen() {
        var url = document.getElementById('data_visualization').src;
        window.open(url, '_blank');
        
        }        
    
</script>
