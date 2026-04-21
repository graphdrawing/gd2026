---
# permalink: /about/
layout: single
title: "Committee"
header:
    image: /assets/images/teaser/gd2026/homepage-teaser.png
    caption: "Image credit: [**Organizer**](https://brocku.ca/)"
# last_modified_at: 2025-01-17
toc: true
---

{% assign data = site.data.publicity %}

## Organizing Committee

- Therese Biedl, University of Waterloo, Canada
- Naser Ezzati-Jivan,  Brock University, Canada
- Sheridan Houghten,  Brock University, Canada
- [Debajyoti Mondal](https://www.cs.usask.ca/faculty/dmondal/), University of Saskatchewan, Canada *(general co-chair)*
- [Rahnuma Islam Nishat](https://brocku.ca/mathematics-science/computer-science/faculty-staff/rahnuma-nishat/),  Brock University, Canada   *(general co-chair)* 
- Ke Qiu,  Brock University, Canada

## Program Committee


-   Marco Angelini, Sapienza University of Rome 
-   Jürgen Bernard,	University of Zurich 
-   Therese Biedl,	University of Waterloo 
-   Prosenjit Bose,	Carleton University	 
-   Nadia Boukhelifa, INRAE			 
-   Paolo Buono, University of Bari Aldo Moro		 
-   Timothy Chan, University of Illinois at Urbana-Champaign	 
-   Steven Chaplick,		Maastricht University 
-   Sabine Cornelsen,		University of Konstanz 
-   Sara Di Bartolomeo,	TU Wien 
-   Stephane Durocher,	University of Manitoba 
-   Henry Ehlers,			yWorks 
-   Velitchko Filipov,		TU Wien 
-   Fabrizio Frati,			Roma Tre University 
-   Mohammad Ghoniem,	Luxembourg Institute of Science and Technology 
-   Michael Goodrich,		University of California, Irvine	 
-   Jan Kratochvil,		Charles University			 
-   Michael Krone,		Stuttgart University of Applied Sciences	 
-   Kostiantyn Kucher,		Linköping University				 
-   [Maarten Löffler](https://www.uu.nl/staff/MLoffler),		Utrecht University				*(program co-chair)*
-   [Silvia Miksch](https://informatics.tuwien.ac.at/people/silvia-miksch),			Vienna University of Technology		*(program co-chair)* 
-   Kazuo Misue,			University of Tsukuba			 
-   Yoshio Okamoto,		University of Electro-Communications	 
-   Daniel Pahr,			Universität Wien						 
-   Irene Parada,			Universitat Politècnica de Catalunya		 
-   Daniel Perz,			University of Perugia				 
-   Ignaz Rutter,			Universität Passau				 
-   Gerik Scheuermann,	University of Leipzig				 
-   Tobias Schreck,		Graz University of Technology		 
-   Darren Strash,		Hamilton College	 
-   Alessandra Tappini, 	University of Perugia			 
-   Soeren Terziadis, 		TU München, Heilbrunn				 
-   Alexandra Weinberger, 	FernUniversität in Hagen			 
-   Alexander Wolff,		Universität Würzburg				 
-   Jules Wulms,			TU Eindhoven				 
-   Michael Wybrow,		Monash University				 
-   Stef van den Elzen,		TU Eindhoven 
-   Tatiana von Landesberger, Universität zu Köln	 

 
## Contest Committee

-   [Sara Di Bartolomeo](https://picorana.github.io/), TU Wien, Austria *(co-chair)*
-   Henry Förster, John Cabot University, Italy
-   Fabian Klute, UPC Barcelona, Spain  
-   Soeren Terziadis, TU München, Germany
-   [Jules Wulms](https://www.ac.tuwien.ac.at/people/jwulms/), TU Eindhoven, Netherlands *(co-chair)*

<!--
{% assign role = "" %}
{% for member in data.OC-Members %}
  {% if role != member.Role %}
    {% assign role = member.Role %}
<h3 class="oc-role"><strong>{{ member.Role }}</strong></h3>
  {% endif %}
<div style="display: inline-block; width: 45%; text-align: left;">
  {% if member.Photo == "yes" %}
<img style="border-radius: 50%" src="../../assets/images/oc/{{ member.First }}_{{ member.Given }}.jpg"
     class="circle" width="150" height="150" /><br />
  {% else %}
<img style="border-radius: 50%" src="../../assets/images/oc/nobody.jpg" width="150" height="150" /><br />
  {% endif %}
<strong>{{ member.First }} {{ member.Given }}</strong><br />
{{ member.Affiliation }}<br /><br />
</div>
{% endfor %}
-->

## Steering Committee

Please refer to [graphdrawing.org](http://graphdrawing.org/sc.html)