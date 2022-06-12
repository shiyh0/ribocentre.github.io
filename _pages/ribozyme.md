---
title: "Ribo centre - Ribozyme"
layout: ribozyme
excerpt: "Ribo centre - Ribozyme"
sitemap: false
permalink: /ribozyme/
---

# Ribozyme

**Known ribozymes**

[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/docs/2022-04-19-VS-ribozyme.md)
<!--Read more [here]({{ site.url }}{{ site.baseurl }}/ribozyme/2022/04/19/VS-ribozyme)-->
[Twister]({{ site.url }}{{ site.baseurl }}/ribozyme/2022/04/19/twister/)
[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/ribozyme/2022/04/19/VS-ribozyme.html)
[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/ribozyme/VS-ribozyme.html)
[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/_site/ribozyme/2022/04/19/)
<!--Read more [here]({{ site.url }}{{ site.baseurl }}/ribozyme/2022/04/19/VS-ribozyme.html)-->
<!--[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/structure/index.html?id=VS_ribozyme)-->
[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/_site/ribozyme/2022/04/19/VS-ribozyme.html)


<!--<div  style="padding-top: 0px; padding-bottom: 50px; padding-left: 30px; padding-right: 30px;">

<table id="dnazymes_table" class="table table-striped table-bordered" cellspacing="0" width="100%">
  <thead>
    <tr>
      <th><a href="/DNAmoreDB/help#help5"><i class="fas fa-question-circle"></i></a>&nbsp;Name</th>
      <th>Length</th>
      <th><a href="/DNAmoreDB/help#help12"><i class="fas fa-question-circle"></i></a>&nbsp;Catalytic region of the Ribozyme</th>
      <th><a href="/DNAmoreDB/help#help4"><i class="fas fa-question-circle"></i></a>&nbsp;Reaction</th>
      <th><a href="/DNAmoreDB/help#help6"><i class="fas fa-question-circle"></i></a>&nbsp;Metal ions/cofactors</th>
    </tr>
    <tr>
      <td name="td0"><a href="https://www.ncbi.nlm.nih.gov/pubmed/16086354">8XL1</a></td>
      <td name="td1">50</td>
      <td name="td2">CCCCGAGGTGTGGACATAGCGGGCTGGTGTGGCGCGCAGT...</td>
      <td name="td3">RNA ligation</td>
      <td name="td4">Mn2+</td>
    </tr>
  </thead>
</table>-->


If the sequence is longer than 50 nucleotides it is trimmed to render the page correctly and three dots are added at the end of it.
To explore the full sequence please open the corresponding DNAzyme entry. Entries for which kinetics parameters and yield data are reported are denoted in <b>bold characters</b>


> 2D representation

<table><tr>
<td><embed src="http://localhost:4000/images/VSD1.svg" style="display:block;width:500px;height:400px" border=0 /></td>
<!--<td><img src="http://localhost:4000/images/VS_ribozymePic/VS2D.svg" alt="drawing" style="height:400px" border=0></td>-->
<td>
<html>
<meta charset="utf-8">
This is an RNA container.
<div id='rna_ss'> </div>
This is after the RNA container.
<script>
    <link rel="stylesheet" type="text/css" href="{{ site.url }}{{ site.baseurl }}/css/fornac.css" />
    <script type='text/javascript' src='{{ site.url }}{{ site.baseurl }}/js/forna/jquery.js'></script>
    <script type='text/javascript' src='{{ site.url }}{{ site.baseurl }}/js/forna/d3.js'></script>
    <script type='text/javascript' src='{{ site.url }}{{ site.baseurl }}/js/forna/fornac.js'></script>
    <script type='text/javascript'>
        var container = new FornaContainer("#rna_ss", {'animation': false});

        var options = {'structure': '((..((....)).(((....))).))',
                       'sequence':             'CGCUUCAUAUAAUCCUAAUGACCUAU'};

        container.addRNA(options.structure, options);
</script>
</td>
</tr></table><br>







