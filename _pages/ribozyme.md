---
title: "Ribo centre - Ribozyme"
layout: ribozyme
excerpt: "Ribo centre - Ribozyme"
sitemap: false
permalink: /ribozyme/
---

# Ribozyme

**Known ribozymes**

[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/ribozyme/2022/04/19/VS-ribozyme.html)
[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/_site/ribozyme/2022/04/19/)
<!--Read more [here]({{ site.url }}{{ site.baseurl }}/ribozyme/2022/04/19/VS-ribozyme.html)-->
<!--[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/structure/index.html?id=VS_ribozyme)-->
[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/_site/ribozyme/2022/04/19/VS-ribozyme.html)
[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/ribozyme/index.html?id=VS_ribozyme)
[VS_ribozyme]({{ site.url }}{{ site.baseurl }}/ribozyme/2022/04/19/index.html?id=VS_ribozyme)
# Ribozyme

**Known ribozymes**

<!--<html lang="en">
  <head>
    <meta charset="utf-8">
  </head>
    <tbody>
        <table id="table_id" class="table table-striped table-bordered" cellspacing="0" width="100%">
        <tr>
        <th>ribozymes</th>   
        </tr>
        <tr>
        <td><a href="https://www.ncbi.nlm.nih.gov/pubmed/16086354/">16086354</a></td>
        </tr>
        <tr>
        <td><a href="https://www.ncbi.nlm.nih.gov/pubmed/16086354/">16086354</a></td>
        </tr>
        <tr>
        <td><a href="https://www.ncbi.nlm.nih.gov/pubmed/16086354/">16086354</a></td>
        </tr>
        <tr>
        <td><a href="https://www.ncbi.nlm.nih.gov/pubmed/16086354/">16086354</a></td>
        </tr>
        <tr>
        <td><a href="https://www.ncbi.nlm.nih.gov/pubmed/16086354/">16086354</a></td>
        </tr>
        </table>
    </tbody>
</html>-->

 <div  style="padding-top: 0px; padding-bottom: 50px; padding-left: 30px; padding-right: 30px;">



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
</table>

<script>
$('#dnazymes_table').DataTable( {
    deferRender: true,
    ajax: {
      type: "GET",
      dataType: 'json',
      data:{
          "sf_reaction":"all",
          "sf_metal_ion":"all",
          "sf_reportedin":"m",
          "sf_kinetics":"all"
          },
      url: '/DNAmoreDB/dnazymes/apidnazymes',
    },
    columns: [
      { data: 'name' },
      {  data: 'length' },
      {  data: 'e' },
      {  data: 'reaction' },
      {  data: 'metal_ions' }
    ],
    "order": [], // this is needed to preserve the order of the table outputted by view.py
    "processing": true,
    "scrollX": true,
    "scrollY": "550px",
    "scrollCollapse": true,
    "paging": false,

    "dom": 'Bfrtip',
    "buttons": [
      {
        extend: 'pdfHtml5',
        orientation: 'landscape',
        pageSize: 'LEGAL'
      },
    'csv', 'print',
    ],
} );
</script>
If the sequence is longer than 50 nucleotides it is trimmed to render the page correctly and three dots are added at the end of it.
To explore the full sequence please open the corresponding DNAzyme entry. Entries for which kinetics parameters and yield data are reported are denoted in <b>bold characters</b>





