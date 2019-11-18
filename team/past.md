---
layout: page
title: Past team members
excerpt: "CB-Geo Computational Geomechanics Research"
#image:
#  feature: cb-geo/banner.png
---

# Team

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
