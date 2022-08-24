---
title: Gallery
permalink: /gallery/
---

## Image Gallery

This gallery displays all the images used in the Hexagons dataset and is organized  by categories. 
Once you select an image, insert its associated drawing procedures in the [Visualization](/Hexagons/visual). 
As a rule, each image is associated with three <i> different </i> drawing procedures. 

<button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen()">Go Full-Screen</button>

<iframe id="image_gallery" src="https://nlp.biu.ac.il/~royi/hexagon-paper-visualization-res/#/task-gallery" title="Image Gallery" style="width:100%; height:720px; border:none;"></iframe>

<script>
    function fullScreen() {
        var url = document.getElementById('image_gallery').src;
        window.open(url, '_blank');
        
        }        
    
</script>
