---
layout: page
#title: CB-Geo
excerpt: "CB-Geo Computational Geomechanics Research Group"
image:
  feature: cb-geo/banner.png
---
* Table of Contents
{:toc}


# Welcome

Welcome to the CB-Geo computational geomechanics research group. We develop open source numerical tools and methods to solve complex geomechanics problems. Please see our [research](https://www.cb-geo.com/research) section for more details. We encourage you to make use of our infrastructure and tools, and also contribute towards the development of geomechanics.

# Team

### Academics

<!-- Team filled from _data/members.yaml-->
   <div class="team">
    {% for member in site.data.members %}
      {% if member.role == "academic" %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
      {% endif %}
    {% endfor %}
   </div>
<!-- End team -->

### Post docs

<!-- Team filled from _data/members.yaml-->
   <div class="team">
    {% for member in site.data.members %}
      {% if member.role == "researcher" %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
      {% endif %}
    {% endfor %}
   </div>
<!-- End team -->

### Students

<!-- Team filled from _data/members.yaml-->
   <div class="team">
    {% for member in site.data.members %}
      {% if member.role == "student" %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
      {% endif %}
    {% endfor %}
   </div>
<!-- End team -->

### Visitors

<!-- Team filled from _data/members.yaml-->
   <div class="team">
    {% for member in site.data.members %}
      {% if member.role == "visitor" %}
       <div class="user">
         <div class="userimg" style="background-image:url('{{ site.baseurl }}/images/cb-geo/team/{{ member.image }}')">
         </div>
         <h4>{{ member.name }}</h4>	
         {{ member.position }}, {{member.uni }}<br/>
	 <a href="mailto:{{ member.email }}">{{ member.email }}</a>
       </div>
      {% endif %}
    {% endfor %}
   </div>
<!-- End team -->


### Past team members
<!-- Team filled from _data/teampast.yaml-->
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
