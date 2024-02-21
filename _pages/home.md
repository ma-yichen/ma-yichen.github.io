---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<style>
code {padding: 6px 8px; font-size: 90%;}
</style>

# Welcome!

I lead a team at <a href="https://www.bayer.com/en/agriculture" target="_blank">Bayer Crop Science</a> researching and implementing methods for using Artificial Intelligence (AI) to inform genetic design of climate resilient crops. If you are interested in our vision/research or are curious about joining the team, please do not hesistate to reach out to me at ethan.pickering@bayer.com.  

I also lecture and collaborate frequently at MIT. Previous to my new roles, I was a postdoctoral associate in Mechanical Engineering working with <a href="http://sandlab.mit.edu/" target="_blank">Professor Themis Sapsis</a> on prediction of extreme events in chaotic systems at the <a href="http://meche.mit.edu/" target="_blank">Massachusetts Institute of Technology</a>. Specifically, we combine deep neural networks with optimal sampling techniques to efficiently perform experimental design. Check out newest publication in Nature Computational Science on Discovering Extremes with AI, as well as our related 2022 preprints on the publications page.

I completed my Ph.D. in Mechanical Engineering working with <a href="https://www.colonius.caltech.edu/" target="_blank">Professor Tim Colonius</a> on reduced-order turbulence models at the <a href="https://www.caltech.edu/" target="_blank">California Institute of Technology</a>. I began my studies (B.S.) at Case Western Reserve University in Mechanical and Aerospace Engineering (Summa Cum Laude) and continued with a Masters (M.S.) in Mechanical Engineering studying building energy efficiency data analytics.  I have work experience with Philips Healthcare, NASA, and the Great Lakes Energy Institute.  In these roles I spent time working as a prototype engineer, a thermodynamic system modeler, and a building energy data analyst. Currently,  I am pursuing research at the intersection of computational fluid dynamics and data science.

### Active Learning for Discovering Extremes

My recent research activity at MIT centers around discovery and prediction of extreme
events by leveraging recent advancements in deep neural networks and Bayesian
statistics. Check out this quick 3 minute <a href="https://www.youtube.com/watch?v=ZYbB9TayxmQ" target="_blank">video</a> for a snapshot into my current work. Please check out our publication page form my information on this work.

<br/>

<div class="row" style="text-align:center">
<video controls autoplay muted loop width="90%" style="display:inline-block; border-radius: 25px; border:0px solid #FFF;">
  <source src="{{ site.url }}{{ site.baseurl }}/images/videos/jet_spod_resolvent.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
  Spectral Proper Orthogonal Decomposition and Resolvent Analysis of a Mach 1.5 jet. 
<br/>
Pickering et al., *Journal of Fluid Mechanics* (2020)
</div>
<br/>

### Data-Driven Turbulence Modeling

My research investigates the fundamental mechanisms that exist in complex and chaotic fluid flows by leveraging large, high-fidelity datasets to inform and validate reduced-order modeling strategies. These mechanisms are of importance as they govern engineering quantities such as noise, drag, and efficiency. Unfortunately, both high-fidelity datasets and reduced order models, alone, can only provide limited insight into these mechanisms. In much of my research, I look to pose optimization problems where our models assimilate/learn various properties of turbulence from the data to yield reduced-order models that are both predictive and general (i.e. applicable to other flows geometries and conditions). In short, this research takes a constrained-''machine learning'' approach, where the Navier-Stokes equations remain a central component of the model.


To learn from the data, turbulent flows are decomposed into their most energetic components (using Spectral Proper Orthogonal Decomposition) and then modeled via linear amplification theory of the equations of motion (Resolvent Analysis). Check out the video above on how we decompose massive datasets (numerous TB) into SPOD modes and then seek to model their theoretical equivalent with resolvent analysis.


<br/>
<div class="well-md">
<h3>Sponsors</h3>
<div style='display:block; text-align:center; margin-left:auto; margin-right:auto;'>
 {% for funder in site.data.funders %}{% if funder.url %}<a href="{{funder.url}}" target="_blank"><img src='/images/logopic/{{ funder.image }}' style='max-height: 70px; max-width: 170px;'/></a>{% else %}<img src='/images/logopic/{{ funder.image }}' class='mycenter' style='max-height: 70px; max-width: 170px;'/>{% endif %}   {% endfor %}
</div>

</div>


