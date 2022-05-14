---
title: "Ribo centre - Ribozyme"
layout: ribozyme
excerpt: "Ribo centre - Ribozyme"
sitemap: false
permalink: /ribozyme/
---

[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/structure/index.html?id=VS_ribozyme)


# Ribozyme

<link rel="stylesheet" type="text/css" href="{{ site.url }}{{ site.baseurl }}/css/fornac.css" media="screen" />
<script type='text/javascript' src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script type='text/javascript' src='https://d3js.org/d3.v7.min.js'></script>
<script type='text/javascript' src='{{ site.url }}{{ site.baseurl }}/js/forna/fornac.js'></script>

<iframe src="http://nibiru.tbi.univie.ac.at/forna/forna.html?id=fasta&file=%3Ecircular_rna\nCUGCUCCACGCAAGGAGGUGGACUUAAGCGGCUCAUCCGGGUCUGCGAUAUCCACUGCGCGGUAUGCGCUCGCGAGUUCGAAUCUCGUCGCCAGUACACUGACUUCACUGGCGUGUCCGAGUGGUUAGGCAA\n..(((((((....(((((((((.....(((((((....))).))))....))))))((((.....))))..(((((.......)))))(((((((...........)))))))..)))..))))...)))..*" align="center" height="450px" width="450px"
                seamless='seamless' frameBorder="0" AllowFullScreen></iframe>


<object data="http://nibiru.tbi.univie.ac.at/forna/forna.html?id=fasta&file=%3Ecircular_rna\nCUGCUCCACGCAAGGAGGUGGACUUAAGCGGCUCAUCCGGGUCUGCGAUAUCCACUGCGCGGUAUGCGCUCGCGAGUUCGAAUCUCGUCGCCAGUACACUGACUUCACUGGCGUGUCCGAGUGGUUAGGCAA\n..(((((((....(((((((((.....(((((((....))).))))....))))))((((.....))))..(((((.......)))))(((((((...........)))))))..)))..))))...)))..*" width="600" height="400">
<embed src="http://nibiru.tbi.univie.ac.at/forna/forna.html?id=fasta&file=%3Ecircular_rna\nCUGCUCCACGCAAGGAGGUGGACUUAAGCGGCUCAUCCGGGUCUGCGAUAUCCACUGCGCGGUAUGCGCUCGCGAGUUCGAAUCUCGUCGCCAGUACACUGACUUCACUGGCGUGUCCGAGUGGUUAGGCAA\n..(((((((....(((((((((.....(((((((....))).))))....))))))((((.....))))..(((((.......)))))(((((((...........)))))))..)))..))))...)))..*" width="600" height="400"> </embed>
</object>


# Structure

  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
    <title>PDBe Molstar</title>

    <!-- Molstar CSS & JS -->
    <link rel="stylesheet" type="text/css" href="https://www.ebi.ac.uk/pdbe/pdb-component-library/css/pdbe-molstar-1.2.1.css">
	<script src="https://www.ebi.ac.uk/pdbe/pdb-component-library/js/pdbe-molstar-plugin-1.2.1.js"></script>
    <style>
      * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
      }
      .msp-plugin ::-webkit-scrollbar-thumb {
          background-color: #111111 !important;
      }
      .viewerSection {
        padding-top: 40px;
      }
      .controlsSection {
        width: 300px;
        float: left;
        padding: 40px 0 0 40px;
        margin-right: 30px;
      }
      .controlBox {
        border: 1px solid lightgray;
        padding: 10px;
        margin-bottom: 20px;
      }
      #myViewer{
        float:left;
        width:450px;
        height: 450px;
        position:relative;
      }
    </style>
  </head>

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
