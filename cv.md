---
title: CV
permalink: /cv/
---

## Curriculum Vitae

<div class="cv-actions">
  <a class="btn" href="{{ '/assets/cv.pdf' | relative_url }}" target="_blank" rel="noopener">Open in new tab</a>
  <a class="btn" href="{{ '/assets/cv.pdf' | relative_url }}" download>Download PDF</a>
</div>

<div class="cv-embed" role="region" aria-label="Embedded PDF viewer: Mofart Ayiega — CV">
  <!-- Primary: inline PDF via <object> for better fallback behavior -->
  <object
    data="{{ '/assets/cv.pdf#view=FitH' | relative_url }}"
    type="application/pdf"
    class="cv-object"
  >
    <!-- Secondary: iframe attempt if <object> is blocked -->
    <iframe
      src="{{ '/assets/cv.pdf#view=FitH' | relative_url }}"
      title="Mofart Ayiega — CV"
      class="cv-iframe"
      loading="lazy"
      allowfullscreen
      referrerpolicy="no-referrer"
    ></iframe>

    <!-- Fallback content for browsers with no PDF support -->
    <div class="cv-fallback">
      <p>Your browser can’t display PDFs inline.</p>
      <p>
        <a href="{{ '/assets/cv.pdf' | relative_url }}" target="_blank" rel="noopener">Open the CV in a new tab</a>
        or
        <a href="{{ '/assets/cv.pdf' | relative_url }}" download>download the PDF</a>.
      </p>
    </div>
  </object>
</div>

<noscript>
  <p>
    JavaScript is disabled. Please
    <a href="{{ '/assets/cv.pdf' | relative_url }}" target="_blank" rel="noopener">open the CV in a new tab</a>.
  </p>
</noscript>

<style>
/* Layout controls */
.cv-embed {
  height: calc(100vh - 160px); /* leave room for header/footer */
  max-width: 100%;
  display: block;
  background: var(--cv-bg, #f6f7f8);
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 2px 12px rgba(0,0,0,.06);
}

/* Prefer <object>, but keep iframe styled as a backup */
.cv-object,
.cv-iframe {
  width: 100%;
  height: 100%;
  border: none;
  display: block;
}

/* Action buttons */
.cv-actions {
  display: flex;
  gap: .75rem;
  margin: 0 0 0.75rem 0;
  flex-wrap: wrap;
}
.cv-actions .btn {
  display: inline-block;
  padding: .5rem .9rem;
  border-radius: 999px;
  text-decoration: none;
  border: 1px solid rgba(0,0,0,.12);
  background: #fff;
  font-size: .95rem;
}
@media (prefers-color-scheme: dark) {
  :root { --cv-bg: #111315; }
  .cv-actions .btn {
    background: #1a1c1f;
    color: #eaecef;
    border-color: #2a2d31;
  }
}

/* Fallback message */
.cv-fallback {
  padding: 1rem;
  font-size: .95rem;
  line-height: 1.4;
}

/* Mobile: slightly shorter viewport to avoid footer overlaps */
@media (max-width: 768px) {
  .cv-embed { height: 85vh; }
}
</style>









