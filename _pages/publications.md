---
title: "Ribo centre - Publications"
layout: gridlay
excerpt: "Ribo centre -- Publications."
sitemap: false
permalink: /publications/
---

# Publications

> <font size=4>List of all the articles of Ribozyme.<font><br>


<!--{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p>{{ publi.authors }}</p>
  <p><em><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></em></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


## Full List of publications

{% for publi in site.data.publist %}

  <b>{{ publi.title }}</b> <br />
  {{ publi.authors }} <br /><em><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></em>

{% endfor %}-->


<!--rank the table-->

<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Sort table example</title>
    <style>
	    body {
			font-size: 14px;
			margin: 50px 30px;
      }
		  table {
        border: 2px solid #f8f8ff;
        border: 2px solid #767676;
		    border: 2px solid #767676;
		    border-radius: 5px;
		    background-color: #fff;
        }
		  th {
        background-color: #0874c4;
        background-color: #0874c4;
        background-color: #0874c4;
        color: rgba(255,255,255,0.9);
		    cursor: pointer;
        }
		  td {
		    background-color: #ffffff;
		    background-color: #f9f9f9;
		    background-color: #f9f9f9;
		    }		
		  th, td {
		  min-width: 90px;
		  padding: 10px 10px;
		}		
		  .arrow {
		  display: inline-block;
		  vertical-align: middle;
		  width: 0;
		  height: 0;
		  margin-left: 5px;
		  opacity: 0.66;
		}		
		  .arrow.asc {
		  border-left: 4px solid transparent;
		  border-right: 4px solid transparent;
		  border-bottom: 4px solid #fff;
		} 
		  .arrow.dsc {
		  border-left: 4px solid transparent;
		  border-right: 4px solid transparent;
		  border-top: 4px solid #fff;
		}
	  </style>
  </head>
    <body>
        <table id="table_id" class="table table-striped table-bordered" cellspacing="0" width="100%">
            <tr>
                <th id="th0" onclick="SortTable(this)" class="as">Year<span class="arrow asc"></span></th>
                <th id="th1" onclick="SortTable(this)" class="as">Author<span class="arrow asc"></span></th>
                <th id="th2" onclick="SortTable(this)" class="as">Title<span class="arrow asc"></span></th>
                <th id="th3" onclick="SortTable(this)" class="as">journal<span class="arrow asc"></span></th>
                <th id="th4" onclick="SortTable(this)" class="as">PDB ID<span class="arrow asc"></span></th>
                <th id="th5" onclick="SortTable(this)" class="as">ribozyme name<span class="arrow asc"></span></th>
       	        <th id="th6" onclick="SortTable(this)" class="as">description<span class="arrow asc"></span></th>
            </tr>
            <tr>
                <td name="td0">1990</td>
                <td name="td1">Saville, B. J. and R. A.Collins </td>
                <td name="td2">A site-specific self-cleavage reaction performed by a novel RNA in neurospora mitochondria.</td>
                <td name="td3">Cell 61(4): 685-696.<a href="https://www.ncbi.nlm.nih.gov/pubmed/14690435">(14690435)</a></td>
                <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14690435">14690435</a></td>
                <td name="td5">VS ribozyme</td>
                <td name="td6">Discovery</td> 
           </tr>
           <tr>
                <td name="td0">1995</td>
                <td name="td1">Beattie, T. L., J. E. Olive and R. A. Collins</td>
                <td name="td2">A secondary-structure model for the self-cleaving region of Neurospora VS RNA.</td>
                <td name="td3">Proc Natl Acad Sci U S A 92(10): 4686-4690.</td>
                <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14690435">14690435</a></td>
                <td name="td5">VS ribozyme</td>
                <td name="td6">Secondary structure</td>
           </tr>
           <tr>
                 <td name="td0">2001</td>
                 <td name="td1">Lafontaine, D. A., T. J. Wilson, D. G. Norman and D. M. Lilley</td>
                 <td name="td2">The A730 loop is an important component of the active site of the VS ribozyme.</td>
                 <td name="td3">J Mol Biol 312(4): 663-674.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/18808125">18808125</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">A730 loop is important<br></td>
           </tr>
           <tr>
                 <td name="td0">2001</td>
                 <td name="td1">Flinders, J. and T. Dieckmann </td>
                 <td name="td2">A pH controlled conformational switch in the cleavage site of the VS ribozyme substrate RNA.</td>
                 <td name="td3"> J Mol Biol 308(4): 665-679.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">NMR structure of the isolated substrate helix<br></td>
           </tr>
           <tr>
                 <td name="td0">2002</td>
                 <td name="td1">Lafontaine, D. A., T. J. Wilson, Z.-Y. Zhao and D. M. J. Lilley</td>
                 <td name="td2">Functional Group Requirements in the Probable Active Site of the VS Ribozyme.</td>
                 <td name="td3"> Journal of Molecular Biology 323(1): 23-34.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">A756 is critical for catalysis<br></td>
           </tr>
           <tr>
                 <td name="td0">2005</td>
                 <td name="td1">Campbell, D. O. and P. Legault</td>
                 <td name="td2">Nuclear magnetic resonance structure of the Varkud satellite ribozyme stem-loop V RNA and magnesium-ion binding from chemical-shift mapping.</td>
                 <td name="td3">Biochemistry 44(11): 4157-4170.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">NMR structure of SL5<br></td>
           </tr>
           <tr>
                 <td name="td0">2007</td>
                 <td name="td1">Wilson, T. J., A. C. McLeod and D. M. Lilley</td>
                 <td name="td2">A guanine nucleobase important for catalysis by the VS ribozyme.</td>
                 <td name="td3">EMBO J 26(10): 2489-2500.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">G638 is critical for catalysis<br></td>
           </tr>
           <tr>
                 <td name="td0">2008</td>
                 <td name="td1">Lipfert, J., J. Ouellet, D. G. Norman, S. Doniach and D. M. Lilley</td>
                 <td name="td2">The complete VS ribozyme in solution studied by small-angle X-ray scattering.</td>
                 <td name="td3"> Structure 16(9): 1357-1367.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">SAXS-deriverd structure<br></td>
           </tr>
           <tr>
                 <td name="td0">2010</td>
                 <td name="td1">Wilson, T. J., N. S. Li, J. Lu, J. K. Frederiksen, J. A. Piccirilli and D. M. Lilley</td>
                 <td name="td2">Nucleobase-mediated general acid-base catalysis in the Varkud satellite ribozyme.</td>
                 <td name="td3">Proc Natl Acad Sci U S A 107(26): 11751-11756.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">A756 stabilizes leaving group<br></td>
           </tr>
           <tr>
                 <td name="td0">2011</td>
                 <td name="td1">Desjardins, G., E. Bonneau, N. Girard, J. Boisbouvier and P. Legault</td>
                 <td name="td2">NMR structure of the A730 loop of the Neurospora VS ribozyme: insights into the formation of the active site.</td>
                 <td name="td3">Nucleic Acids Res 39(10): 4427-4437.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">NMR structure of A730 loop<br></td>
           </tr>
           <tr>
                 <td name="td0">2014</td>
                 <td name="td1">Bonneau, E. and P. Legault</td>
                 <td name="td2">Nuclear magnetic resonance structure of the III-IV-V three-way junction from the Varkud satellite ribozyme and identification of magnesium-binding sites using paramagnetic relaxation enhancement.</td>
                 <td name="td3"> Biochemistry 53(39): 6264-6275.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">NMR structure of the III-IV-V three-way junction<br></td>
           </tr>
           <tr>
                 <td name="td0">2014</td>
                 <td name="td1">Bonneau, E., N. Girard, S. Lemieux and P. Legault</td>
                 <td name="td2">The NMR structure of the II-III-VI three-way junction from the Neurospora VS ribozyme reveals a critical tertiary interaction and provides new insights into the global ribozyme structure.</td>
                 <td name="td3">RNA 21(9): 1621-1632.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">NMR structure of the II-III-VI three-way junction<br></td>
           </tr>
           <tr>
                 <td name="td0">2015</td>
                 <td name="td1">Suslov, N. B., S. DasGupta, H. Huang, J. R. Fuller, D. M. Lilley, P. A. Rice and J. A. Piccirilli</td>
                 <td name="td2">Crystal structure of the Varkud satellite ribozyme.</td>
                 <td name="td3">Nat Chem Biol 11(11): 840-846.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">Crystal structure<br></td>
           </tr>
           <tr>
                 <td name="td0">2017</td>
                 <td name="td1">DasGupta, S., N. B. Suslov and J. A. Piccirilli</td>
                 <td name="td2">Structural Basis for Substrate Helix Remodeling and Cleavage Loop Activation in the Varkud Satellite Ribozyme.</td>
                 <td name="td3"> J Am Chem Soc 139(28): 9591-9597.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">Crystal structure<br></td>
           </tr>
           <tr>
                 <td name="td0">2020</td>
                 <td name="td1">Ganguly, A., B. P. Weissman, T. J. Giese, N. S. Li, S. Hoshika, S. Rao, S. A. Benner, J. A. Piccirilli and D. M. York</td>
                 <td name="td2">Confluence of theory and experiment reveals the catalytic mechanism of the Varkud satellite ribozyme.</td>
                 <td name="td3">Nat Chem 12(2): 193-201.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5">VS ribozyme</td>
                 <td name="td6">Catalytic mechanism<br></td>
           </tr>
        </table>
    </body>
</html>
<script type="text/javascript"> 
    var tag=1;
    function SortTable(obj){
        var td0s=document.getElementsByName("td0");//得到id为td0的一串列表，下相同
        var td1s=document.getElementsByName("td1");
        var td2s=document.getElementsByName("td2");
        var td3s=document.getElementsByName("td3");
        var td4s=document.getElementsByName("td4");
        var td5s=document.getElementsByName("td5");
        var td6s=document.getElementsByName("td6");
        var tdArray0=[];
        var tdArray1=[];
        var tdArray2=[];
        var tdArray3=[];
        var tdArray4=[];
        var tdArray5=[];
        var tdArray6=[];
        for(var i=0;i<td0s.length;i++){
            tdArray0.push(td0s[i].innerHTML);
        }//每串都写到数组中
        for(var i=0;i<td1s.length;i++){
            tdArray1.push(td1s[i].innerHTML);
        }
        for(var i=0;i<td2s.length;i++){
            tdArray2.push(td2s[i].innerHTML);
        }
        for(var i=0;i<td3s.length;i++){
            tdArray3.push(td3s[i].innerHTML);
        }
        for(var i=0;i<td4s.length;i++){
            tdArray4.push(td4s[i].innerHTML);
        }
        for(var i=0;i<td5s.length;i++){
            tdArray5.push(td5s[i].innerHTML);
        }
        for(var i=0;i<td6s.length;i++){
            tdArray6.push(td6s[i].innerHTML);
        }
        var tds = document.getElementsByName("td" + obj.id.substr(2, 1));
        //得到当前传入对象的那一列
        var columnArray=[];
        for(var i=0;i<tds.length;i++){
            columnArray.push(tds[i].innerHTML);
        }//当前那一列都写入column这个栈，是逆序的
        var orginArray=[];
        for(var i=0;i<columnArray.length;i++){
            orginArray.push(columnArray[i]);
        }//将这一列的内容再存储一遍，一会原来列表修改以后，
        //通过比对值的方式对应到当前行的内容，实现同行内容一起修改
        columnArray.sort();   //排序后的新值，只排序了当前列
        for(var i=0;i<columnArray.length;i++){
            for(var j=0;j<orginArray.length;j++){
                if(orginArray[j]==columnArray[i]){
                    document.getElementsByName("td0")[i].innerHTML=tdArray0[j];
                    document.getElementsByName("td1")[i].innerHTML=tdArray1[j];
                    document.getElementsByName("td2")[i].innerHTML=tdArray2[j];
                    document.getElementsByName("td3")[i].innerHTML=tdArray3[j];
                    document.getElementsByName("td4")[i].innerHTML=tdArray4[j];
                    document.getElementsByName("td5")[i].innerHTML=tdArray5[j];
                    document.getElementsByName("td6")[i].innerHTML=tdArray6[j];
                    orginArray[j]=null;
                    break;
                }
            }
        }
    }
</script>
