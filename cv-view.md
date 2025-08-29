---
title: View CV
permalink: /cv/view/
layout: default
---

<div class="cv-viewport" role="region" aria-label="PDF viewer — Mofart Ayiega CV">
  <object
    data="{{ '/assets/cv.pdf?v=20250829#view=FitH' | relative_url }}"
    type="application/pdf"
    class="cv-object"
  >
    <iframe
      src="{{ '/assets/cv.pdf?v=20250829#view=FitH' | relative_url }}"
      class="cv-iframe"
      title="Mofart Ayiega — CV"
    ></iframe>
    <p>
      Your browser can’t display PDFs inline.
      <a href="{{ '/assets/cv.pdf' | relative_url }}" target="_blank" rel="noopener">Open the CV file</a>.
    </p>
  </object>
</div>

<style>
.cv-viewport { height: 100vh; margin: 0; }
.cv-object, .cv-iframe { width: 100%; height: 100%; border: 0; display: block; }
</style>
