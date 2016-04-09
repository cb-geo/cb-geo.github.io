---
layout: page
title: Cambridge-Berkeley Geomechanics
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
   <div id="team">
    {% for member in site.data.team %}
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

### Cambridge 

* Krishna Kumar, Research Associate

* Yi Rui, Research Associate

* John Wong, PhD Researcher

* Shyamini Kularathna, PhD Researcher

* Hansini Malikachari, PhD Researcher

### Berkeley

* John Bray, Professor

* Nicholas Sitar, Professor

* Mike Gardner, PhD Researcher

## Resources

* [![appear.in](images/cb-geo/appear.in.png) appear.in](https://appear.in/cb-geo): Video conferencing

* [![asana](images/cb-geo/asana.png) Asana](https://asana.com/):  Project management

* [![github](images/cb-geo/github.png) GitHub](https://github.com/cb-geo): Git code hosting (mirror of GitLab)

* [![gitlab](images/cb-geo/gitlab.png) GitLab](https://git.cb-geo.com): Git code hosting and Continous Integration system

* [![slack](images/cb-geo/slack.png) Slack](https://cb-geo.slack.com/): Team communication

* [![vagrant](images/cb-geo/vagrant.png) Vagrant](https://www.vagrantup.com/): Virtual development environment deployment

