---
title: "Ribo centre - Helps"
layout: piclay
excerpt: "Ribo centre -- Helps"
permalink: /Helps/
---

# Helps

<br><br>
**Ribocentre is designed to contain comprehensive information of all natural ribozymes. In addition to a brief introduction to ribozymes，on each ribozyme page，you'll see a timeline of vital breakthroughs in ribozyme research，representative structures and the chemical mechanism of this ribozyme. Besides，we provide multiple indexing and searching methods，you can index/search about the publications, structure，catalytic and application of ribozymes that interest you. Users are more than welcome to submit new ribozyme cases or related comments through the submission portal to help us improve our database.**

<br>
**You can find:**
<br><br>

<blockquote>
  <p>Pages</p>
</blockquote>

In <code class="language-plaintext highlighter-rouge"><font color=Gray>Home</font></code> page, we use the text introduction message from wiki. We hope you could get some basic concepts of ribozymes and know what is ribozyme.

You can clink the Ribozyme name in <code class="language-plaintext highlighter-rouge"><font color=Gray>Ribozyme</font></code> page, and then it would turn into a single page which shows the timeline, structure, cytalytic information and so on about the ribozyme you choosed. We hope you could get the message you want!

And in <code class="language-plaintext highlighter-rouge"><font color=Gray>Application</font></code> page, you can find two example of how a ribozyme be used by research teams to do something about application creatively. We would keep focus on this section and update our website page in time.

We also sum up some catalytic centres information which be proved in publication to directly show a classification of the ribozymes in <code class="language-plaintext highlighter-rouge"><font color=Gray>Calalysis</font></code>page.

In some pages, we use a table-format to show the information of different ribozymes.You can click the <code class="language-plaintext highlighter-rouge"><font color=Gray>header</font></code> to rank the column information. You could use the <code class="language-plaintext highlighter-rouge"><font color=Gray>Search</font></code>to find the ribozymes/years/and so on information you want. Under the table, you could find how many items we provided in the left. We also provide the function of  <code class="language-plaintext highlighter-rouge"><font color=Gray>Print</font></code> and download function when you click <code class="language-plaintext highlighter-rouge"><font color=Gray>Csv</font></code> <code class="language-plaintext highlighter-rouge"><font color=Gray>PDF</font></code> and so on to get the file format you want to save.

The <code class="language-plaintext highlighter-rouge"><font color=Gray>Structure</font></code> and <code class="language-plaintext highlighter-rouge"><font color=Gray>Publication</font></code> page provide more details of ribozymes in different aspects and the link of single ribozyme page/structure details/publications.<br><br>

<blockquote>
  <p>Summit</p>
</blockquote>

The more updated information and more functions are trying to be used in our database. We also need the voice from different people at the same time. It is our pleasure if we could get some feedback to make the database more integral, easier to be used. Such as:


<img src="https://www.ribocentre.org/images/help.png" alt="drawing" style="weight:450px;height:200px;display:block;margin:0 auto;"><br>


**You can add some information of your found about new Ribozyme ! We are pleasure if you could contact us with different opinion !**
**Please feel free to contact us with some mistake you find! We need more feedback to complete our work to improve the convenience and applicability. You also could commit our work by the <code class="language-plaintext highlighter-rouge"><font color=Gray>Submit</font></code> button.**

You could easily find the team group information under the <code class="language-plaintext highlighter-rouge"><font color=Gray>Submit</font></code> section. We also provide the way that you could leave your message online.<br><br>


 If you want to submit your work or give us some feedback, We add some examples you can follow to more accurately let us know what you want to tell us! Such as:<br><br>
 
 This is a table of Ribozyme database .You could find the Ribozyme which you interested in and give the relative question or your own opinion!
 
 <img src="https://www.ribocentre.org/images/HelpsPic/summit1.png" alt="drawing" style="weight:450px;height:200px;display:block;margin:0 auto;"><br><br>
 This is a example if you want to summit a/some new ribozyme/ribozymes or the latest publication. Please as complete as possible give us the information of the new one. 
 
 <img src="https://www.ribocentre.org/images/HelpsPic/summit2.png" alt="drawing" style="weight:450px;height:200px;display:block;margin:0 auto;"><br><br>
 This is a example if you find some mistake in our database, we need some details to help us found the faults. Please tell us where you find the mistake. It is great if you could give us some advice at the same time!(No advice given is OK, please feel free. )
 
 <img src="https://www.ribocentre.org/images/HelpsPic/summit3.png" alt="drawing" style="weight:450px;height:200px;display:block;margin:0 auto;"><br><br>
 

><a href="https://docs.google.com/spreadsheets/d/1dWzCMqP9_fmOxxBxpx6Rc0Ro2Her0YIn-07Rpx7fzEs/edit?usp=sharing"  target="_blank"><button>Summit</button></a><br><br>
> If we could get your feedback, we would try to update the database  as soon as possible!
> For large datasets please contact the database team group directly by using the submission form.

<br><br>

>## Contact us:


### Group Members


***

{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


<!--## Graduate Students-->
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}<br><br>






#### Relative websites:


[RCSB PDB](https://www.rcsb.org/) :As a member of the wwPDB, the RCSB PDB curates and annotates PDB data according to agreed upon standards. <br>
[ Forna ](http://rna.tbi.univie.ac.at/forna/) :RNA Secondary Structure Visualization Using a Force Directed Graph Layout. <br>
[ Rfam](https://rfam.xfam.org/) : The RNA families database <br>
[Wiki](https://www.wikipedia.org/) : A typical wiki contains multiple pages for the subjects or scope of the project and could be either open to the public or limited to use within an organization for maintaining its internal knowledge base. <br> <br>







