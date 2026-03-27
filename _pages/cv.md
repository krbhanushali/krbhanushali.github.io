---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/example_pdf.pdf # you can also use external links here
cv_format: rendercv # options: rendercv, jsonresume
description: 
toc:
  sidebar: 
---

<iframe src="{{ page.cv_pdf | relative_url }}" width="100%" height="900px" style="border: none;">
  <p>Your browser does not support iframes.
  <a href="{{ page.cv_pdf | relative_url }}">Download the PDF</a> instead.</p>
</iframe>

<div style="text-align: center; margin-top: 12px;">
  <a href="{{ page.cv_pdf | relative_url }}" target="_blank">Open in new tab</a>
  &nbsp;·&nbsp;
  <a href="{{ page.cv_pdf | relative_url }}" download>Download</a>
</div>