---
layout: page
#title: Cambridge-Berkeley Geomechanics
excerpt: "Cambridge-Berkeley Computational Geomechanics Research"
image:
  feature: cb-geo/banner.png
---
* Table of Contents
{:toc}


## Welcome

Welcome to the Cambridge - Berkeley Computational Geomechanics (CB-Geo) group. We encourage you to make use of our infrastructure and tools, and also contribute towards the development of geomechanics.

## Team



<!-- Team filled from _data/team.yaml-->
   <div class="team">
    {% for member in site.data.core-team %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
    {% endfor %}
   </div>
<!-- End team -->

### Academics

<!-- Team filled from _data/team.yaml-->
   <div class="team">
    {% for member in site.data.academics %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
    {% endfor %}
   </div>
<!-- End team -->

### Post docs

<!-- Team filled from _data/team.yaml-->
   <div class="team">
    {% for member in site.data.postdocs %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
    {% endfor %}
   </div>
<!-- End team -->

### Students

<!-- Team filled from _data/team.yaml-->
   <div class="team">
    {% for member in site.data.students %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
    {% endfor %}
   </div>
<!-- End team -->

### Visitors

<!-- Team filled from _data/team.yaml-->
   <div class="team">
    {% for member in site.data.visitors %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
    {% endfor %}
   </div>
<!-- End team -->


### Past team members
<!-- Team filled from _data/team.yaml-->
   <div class="team">
    {% for member in site.data.teampast %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
    {% endfor %}
   </div>
<!-- End team -->
