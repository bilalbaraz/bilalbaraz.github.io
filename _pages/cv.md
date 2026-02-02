---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Engineering, Kocaeli University, 2012–2016

Work experience
======
* Mar 2025 – Jan 2026: Mobile Developer at Getmobil | Istanbul, Turkey
  * Developed the partner mobile application using React Native for iOS and Android, and optimized performance to improve user experience.
  * Built analytics infrastructure to measure user behavior; handled maintenance tasks and resolved application errors.
  * Set up CI/CD distribution with Fastlane and GitHub Actions.
  * Coordinated the planned İşCep integration between Türkiye İş Bankası and Getmobil, aligning work across teams.
  * Built backend (Golang) and frontend (React) features for the planned Apple–Getmobil device issue detection application.

* May 2020 – Mar 2025: Senior Software Engineer at Wisho | Istanbul, Turkey
  * Developed a WebRTC video calling application, resolving iOS/Android interoperability and browser compatibility issues for seamless communication.
  * Produced integration documentation and ensured the solution met customer and market requirements while continuously researching and integrating new technologies.
  * Improved code quality through automated unit tests and comprehensive code reviews; supported reliable B2B platform operations.
  * Led AWS cost optimization by serving static files from S3 via CloudFront, reducing S3 costs by 80% and lowering storage expenses.
  * Separated high-traffic endpoints into AWS Lambda with API Gateway to balance traffic, reduce EC2 load, and improve resilience under peak demand.
  * Applied OWASP guidelines and contributed to ISO 27001 compliance to strengthen security posture.
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Volunteering
======
* Chair of Management Board, Kocaeli University Computer Club, Sep 2014 – Oct 2015
* Vice-Chair of Management Board, Kocaeli University Computer Club, Nov 2013 – Sep 2014
