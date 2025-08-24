---
title: CV
permalink: /cv/
---

## Curriculum Vitae

<!-- Primary: object/embed (best cross-browser support for inline PDFs) -->
<div class="cv-viewport">
  <object
    data="{{ '/assets/cv.pdf#toolbar=0&navpanes=0&view=FitH' | relative_url }}"
    type="application/pdf"
    width="100%"
    height="100%"
  >
    <embed
      src="{{ '/assets/cv.pdf#toolbar=0&navpanes=0&view=FitH' | relative_url }}"
      type="application/pdf"
      width="100%"
      height="100%"
    />
    <!-- Fallback shown only if the browser blocks inline PDFs -->
    <p>
      This browser can’t display PDFs inline. Please
      <a href="{{ '/assets/cv.pdf' | relative_url }}" target="_blank" rel="noopener">open the CV in a new tab</a>.
    </p>
  </object>
</div>

<style>
/* Make the viewer fill the window height so users can scroll the CV */
.cv-viewport {
  height: calc(100vh - 160px); /* adjust if your header/footer is taller/shorter */
  max-width: 100%;
  overflow: hidden; /* the PDF handles its own internal scroll */
}
@media (max-width: 768px) {
  .cv-viewport { height: 85vh; }
}
</style>





