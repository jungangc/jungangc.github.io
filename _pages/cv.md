---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[⬇️ Download CV (PDF)]({{ '/files/Gordon-Chen-CV.pdf' | relative_url }}){: .btn .btn--primary target="_blank" }

<!-- Optional: embed a preview -->
<object data="{{ '/files/resume.pdf' | relative_url }}" type="application/pdf" width="100%" height="900px">
  <p>Your browser can’t display PDFs. 
  <a href="{{ '/files/resume.pdf' | relative_url }}">Download the CV</a>.</p>
</object>

{% include base_path %}

Education
======
* Ph.D in Petroleum Engineering, Texas A&M University, 2024
* M.S. in Petroleum Engineering, University of Southern California, 2019
* B.S. in Engineering, China University of Petroleum, Beijing, 2017

Work experience
======
* Feb 2025--Current: Postdoctoral Fellow
  * Bureau of Economic Geology, UT Austin 
  * Duties includes: 1. develop and advance newest version of EASiTool. 2. lead researches on machine learning applications for CCS. 

* June 2024 - Aug 2024: Machine Learning Intern
  * CNPC USA, Houston, Texas
  * Duties included: Collaborated with a cross-functional team to establish strategic roadmap for machine learning applications in drilling
operations. Utilized industry-standard metrics and physics-based methodologies to identify and label drilling dysfunctions

* May 2022 - Aug 2022: Machine Learning Intern (Contract)
  * ConocoPhillips Company, Remote
  * Duties included: Developed GeoGPT which generate geomodels according to user-defined properties, offering up to a 95% reduction in
geomodel generation time. Developed and applied the PixelSNAIL auto-regressive deep learning model for the rapid generation of new geomodels,
significantly outpacing conventional techniques, published an impactful paper as the first author.


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Member, Society of Petroleum Engineers;
* Reviewer, Geoenergy Science and Engineerin;
* Reviewer, Neural Computing and Applications;
* Reviewer, Computer Methods in Applied Mechanics and Engineering;
* Reviewer, Mathematical Geosciences;
* Reviewer, Advances in Water Resources; 
