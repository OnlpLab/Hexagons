---
title: Visualization
permalink: /visual/
---

## Visualization
You may insert an index of a drawing procedure or first select an image in the [Gallery](/Hexagons/gallery) and then insert the indices of its associated drawing procedures. 

<button id="full_screen" type="button" class="btn btn-primary btn-sm" onclick="fullScreen()">Go Full-Screen</button>

<iframe id="data_visualization" src="https://nlp.biu.ac.il/~royi/hexagon-paper-visualization/#/main" title="Dataset Visualization" style="width:100%; height:720px; border:none;"></iframe>

<script>
    function fullScreen() {
        var url = document.getElementById('data_visualization').src;
        window.open(url, '_blank');
        
        }       
    
</script>
