---
layout: page
title: Team
excerpt: "CB-Geo Computational Geomechanics Research"
#image:
#  feature: cb-geo/banner.png
---

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
