---
title: "Ribo centre - Structure"
layout: structure
excerpt: "Ribo centre - Structure"
sitemap: false
permalink: /structure
---

# Structure


<!-- Molstar container -->
<div id="myViewer"></div>

<script>

var viewerInstance = new PDBeMolstarPlugin();

var options = {
moleculeId: '1ehz',
expanded: false,
hideControls: true
}
var viewerContainer = document.getElementById('myViewer');
viewerInstance.render(viewerContainer, options);
</script>
