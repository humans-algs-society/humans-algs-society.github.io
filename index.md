---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: 
layout: home
---

<!--- ### <center> <b>Humans, Algorithmic Decision-Making and Society</b>: <br/> Modeling Interactions and Impact </center>
<br/>
#####  <center> Workshop at <a href="https://icml.cc/Conferences/2024">International Conference on Machine Learning (ICML)</a> <br/> Date: 27 July 2024 <br/> Venue: Hall A2, Messe Wien Exhibition Congress Center, Vienna, Austria </center> --->


<br/>

With the widespread adoption of machine learning in social technologies, there are increasingly complex interactions between humans, algorithmic decision-makers, and society at large. For instance, algorithmic decisions influence the information and opportunities that are available to individuals, the news they read, the job listings they are matched to, the credit lines they receive, and the social circle they form. Such decisions can therefore affect societal outcomes such as social mobility, mental health, polarization etc. At the same time, humans also influence algorithmic decision-makers, for instance, by expressing their preferences through observed behaviors which might be inconsistent or strategic. To understand long-term individual and societal outcomes resulting from these interactions, and to develop algorithms that mitigate undesired outcomes, it has therefore become increasingly important to model these complex interactions as a whole. 

The purpose of this workshop is to bring together researchers from both academia and industry working on the full spectrum of modeling interactions between AI systems, humans, and society, from theory to practice. We will invite speakers and solicit contributed papers and posters covering the various facets of these interactions. We are targeting different communities/fields such as machine learning, network science, social systems, algorithmic game theory, economics. We expect that the presence of these different communities will result in a fruitful exchange of ideas and stimulate an open discussion about the current challenges and possible solutions. 

<br/>

### Invited Speakers 

<div class="member-profiles-grid">
{% for mem in site.speakers%}
<a href="{{mem.webpage}}">
<div class="member-profile">
<div class="member-photo-container">
<img class="member-photo" src="{{site.baseurl}}/assets/img/speakers/{{mem.img}}" target="_blank"> 
</div>
<div class="member-name"><b>{{ mem.name }}</b> <br/> {{ mem.affil}} </div>
</div>
</a>
{% endfor %}
</div>



### Organizers 

<div class="member-profiles-grid">
{% for mem in site.organizers%}
<a href="{{mem.webpage}}">
<div class="member-profile">
<div class="member-photo-container">
<img class="member-photo" src="{{site.baseurl}}/assets/img/organizers/{{mem.img}}" target="_blank"> 
</div>
<div class="member-name"><b>{{ mem.name }}</b> <br/> {{ mem.affil}} </div>
</div>
</a>
{% endfor %}
</div>



### News
* The paper submission deadline has been extended to **June 3, 2024 AOE**.
* Call for papers is out! Last date to submit is **May 31, 2024**. Please check [instructions](callforpapers) on how to submit.


<!--
* [Schedule](schedule) updated. 
* Accepted papers and reviews [available](papers)
* Thank you [reviewers](people/#reviewers)! 
-->


### Contact us

The organizers may be reached at `has.icml24 <AT> gmail <DOT> com`

<!--[Follow us on Twitter](https://twitter.com/has_icml24)!-->


