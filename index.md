---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: 
layout: home
---

<h2 style="text-align: center;" class="custom-title-page"> Humans, Algorithmic Decision-Making and Society: Modeling Interactions and Impact </h2>
<h3 style="text-align: center;" class="custom-subtitle-page"> Workshop at <a href="https://icml.cc/Conferences/2024">ICML 2024 </a> </h3>
<br>

With the widespread adoption of machine learning in social technologies, there are increasingly complex interactions between humans, algorithmic decision-makers, and society at large. For instance, algorithmic decisions influence the information and opportunities that are available to individuals, the news they read, the job listings they are matched to, the credit lines they receive, and the social circle they form. On a macroscopic level, such decisions can therefore affect societal outcomes such as social mobility, mental health, polarization etc. At the same time, humans also influence algorithmic decision-makers, for instance, by expressing their preferences through observed behaviors which might be inconsistent or strategic. To understand long-term individual and societal outcomes resulting from these interactions, and to develop algorithms that mitigate undesired outcomes, it has therefore become increasingly important to model these complex interactions as a whole. 

The purpose of this workshop is to bring together researchers from both academia and industry working on the full spectrum of modeling interactions between AI systems, humans, and society, from theory to practice. We will invite speakers and solicit contributed papers and posters covering the various facets of these interactions. We are targeting different communities/fields such as machine learning, network science, social systems, algorithmic game theory, economics. We expect that the presence of these different communities will result in a fruitful exchange of ideas and stimulate an open discussion about the current challenges and possible solutions. 


### Invited Speakers 
 
<figure>
	<div class = "post-content">
	  <table style="border-collapse: collapse; border: none;">
	  	{% for speaker in site.speakers %}
		    <tr style="border: none;">
		        <td style="border: none;">
		            <div class="col-xs-6">
		                <p align="center">
		                	{% if speaker.img %}
		                    	<img class="people-pic" src="{{ speaker.img | prepend: '/assets/img/speakers/' | prepend: site.baseurl | prepend: site.url }}" target="_blank">
		                    {% else %}
		                    	<img class="people-pic" src="{{ 'avatar.jpg' | prepend: '/assets/img/speakers/' | prepend: site.baseurl | prepend: site.url }}" target="_blank">
		                    {% endif %}
		                </p>
		            </div>
		        </td>
    		    <td style="border: none;">
		            <div class="people-name text-center">
		            	<!-- Speaker name (link to webpage if provided) -->
		            	{% if speaker.webpage %}
		            		<b><a href="{{ speaker.webpage }}" target="_blank">{{ speaker.name }}</a></b>
		            	{% else %}
		            		<b>{{ speaker.name }}</b>
		            	{% endif %}
		                <br>
		                <!-- Speaker affiliation (if provided) -->
		                {% if speaker.affil_link %}
		                	<a href="{{ speaker.affil_link }}" target="_blank">{{ speaker.affil }}</a>
		                {% else %}
		                	{{ speaker.affil }}
		                {% endif %}
		                <!-- Additional speaker affiliation (if provided) -->
		                {% if speaker.affil2_link %}
		                	<br>
		                	<a href="{{ speaker.affil2_link }}" target="_blank">{{ speaker.affil2 }}</a>
		                {% elsif speaker.affil2 %}
		                	<br>
		                	{{ speaker.affil2 }}
		                {% endif %}
		            </div>
		        </td>
		        <td style="border: none;">
		        	<div class="people-name text-center">
		        		{{ speaker.content }}
		        	</div>
		        </td>
		    </tr>
	    {% endfor %}
	  </table>
  </div>
</figure>


### News

* Call for papers is out! Last date to submit is **May 24, 2024**. Please check [instructions](submit) on how to submit.


<!--
* [Schedule](schedule) updated. 
* Accepted papers and reviews [available](papers)
* Thank you [reviewers](people/#reviewers)! 
-->


### Contact us

The organizers may be reached at `has_icml24 <AT> gmail <DOT> com`

<!--[Follow us on Twitter](https://twitter.com/has_icml24)!-->


### Related past workshops


1. [Socially Responsible Machine Learning (SRML)](https://iclrsrml.github.io/) - ICLR, 2022
2. [Socially Responsible Machine Learning](https://icmlsrml2021.github.io/) - ICML, 2021
3. [Learning in Presence of Strategic Behavior](https://sites.google.com/view/strategicml/) - NeurIPS, 2021
4. [Workshop on Responsible AI ](https://sites.google.com/view/rai-workshop/home) - ICLR, 2021
5. [Workshop on Consequential Decision Making in Dynamic Environments](https://dynamicdecisions.github.io/) - NeurIPS, 2020
