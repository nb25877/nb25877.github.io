---
title: Contact
tags: [contact]
---

# Contact

- **LinkedIn:** [nbhal](https://www.linkedin.com/in/nbhal/){ target=_blank }
- **Email:** <span class="obf" data-user="hello" data-domain="nikunjb.com"></span>

<script>
  // simple email obfuscation
  const s = document.currentScript.previousElementSibling;
  if (s && s.classList.contains('obf')) {
    const u = s.dataset.user, d = s.dataset.domain;
    s.innerHTML = `<a href="mailto:${u}@${d}">${u}@${d}</a>`;
  }
</script>

_Last updated: {{ git_revision_date_localized }}_