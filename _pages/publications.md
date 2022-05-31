---
title: "Ribo centre - Publications"
layout: gridlay
excerpt: "Ribo centre -- Publications."
sitemap: false
permalink: /publications/
---

# Publications
**List of all the articles of Ribozyme.**

<html>
	<head>
		<meta charset="utf-8">
		<title></title>
		<style type="text/css">
			
			form .text {
				display: inline-block;
				border: 0;
				width: 260px;
				height: 35px;
				font-size: 14px;
				outline: none;
				
				border: 2px solid #01af63;
			}
			
			form .search {
				
				width: 90px;
				height: 38px;
				border: 0;
				outline: none;
				cursor: pointer;
				/*   cursor: pointer;   鼠标悬停或点击时button时鼠标变成其他图标  */
				text-align: center;
				line-height: 40px;
				background-color: #01af63;
				color: #FFFFFF;
			}
		</style>
	</head>
	<body>
		
		<form target="_blank" method="get" action="https://www.baidu.com/s">
			<input type="text" placeholder="Key words" name="word" class="text" />
			<input type="submit" value="search" class="search">
		</form>
	</body>
</html><br>

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
		  border: 2px solid #42b983;
		  border-radius: 5px;
		  background-color: #fff;
		}
		  th {
		  background-color: #42b983;
      color: rgba(255,255,255,0.66);
		  cursor: pointer;
		}
		  td {
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
                <th id="th0" onclick="SortTable(this)" class="as">Year of pub.<span class="arrow asc"></span></th>
                <th id="th1" onclick="SortTable(this)" class="as">First Author<span class="arrow asc"></span></th>
                <th id="th2" onclick="SortTable(this)" class="as">Laboratory<span class="arrow asc"></span></th>
                <th id="th3" onclick="SortTable(this)" class="as">Title<span class="arrow asc"></span></th>
                <th id="th4" onclick="SortTable(this)" class="as">PubMed ID<span class="arrow asc"></span></th>
                <th id="th5" onclick="SortTable(this)" class="as">DOI<span class="arrow asc"></span></th>
       	        <th id="th6" onclick="SortTable(this)" class="as">Reaction<span class="arrow asc"></span></th>
            </tr>
            <tr>
                <td name="td0">2005</td>
                <td name="td1">Y Wang</td>
                <td name="td2">S K Silverman</td>
                <td name="td3">Efficient one-step synthesis of biologically related lariat RNAs by a deoxyribozyme.</td>
                <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/16086354">16086354</a></td>
                <td name="td5"><a href="https://www.doi.org/10.1002/anie.200501643">10.1002/anie.200501643</a></td>
                <td name="td6">Thymine dimer repair</td> 
           </tr>
           <tr>
                <td name="td0">2003</td>
                <td name="td1">Y Wang</td>
                <td name="td2">S K Silverman</td>
                <td name="td3">Characterization of deoxyribozymes that synthesize branched RNA.</td>
                <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14690435">14690435</a></td>
                <td name="td5"><a href="https://www.doi.org/10.1021/bi0355847">10.1021/bi0355847</a></td>
                <td name="td6">RNA ligation</td>
           </tr>
           <tr>
                 <td name="td0">2008</td>
                 <td name="td1">T P Mui</td>
                 <td name="td2">S K Silverman</td>
                 <td name="td3">Convergent and general one-step DNA-catalyzed synthesis of multiply branched DNA.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/18808125">18808125</a></td>
                 <td name="td5"><a href="https://www.doi.org/10.1021/ol801568q">10.1021/ol801568q</a></td>
                 <td name="td6">DNA ligation<br></td>
           </tr>
           <tr>
                 <td name="td0">2004</td>
                 <td name="td1">D J-F Chinnapen</td>
                 <td name="td2">D Sen</td>
                 <td name="td3">A deoxyribozyme that harnesses light to repair thymine dimers in DNA.</td>
                 <td name="td4"><a href="https://www.ncbi.nlm.nih.gov/pubmed/14691255">14691255</a></td>
                 <td name="td5"><a href="https://www.doi.org/10.1073/pnas.0305943101">10.1073/pnas.0305943101</a></td>
                 <td name="td6">Thymine dimer repair<br></td>
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



