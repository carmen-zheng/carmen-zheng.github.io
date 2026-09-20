---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

Download the CV as a [PDF file]({{ base_path }}/files/carmen_zheng_cv.pdf).

**👩‍🎓 Career and Education**

- Clinical Neuropsychologist, **The Neuro Group**, [2026]–Present
- Clinical Neuropsychology Registrar, **Royal Melbourne Hospital; Austin Health; Alfred Health**, 2023-2025
- MPsych in Clinical Neuropsychology, **University of Melbourne**
- B.A (Honours) in Psychology, **University of Melbourne**
- B.A in Psychology & Sociology, **University of Melbourne**

---

**🏛️ Leadership and Service**

- [2025-Present]: [ECR Representative], [OHBM-Aus Committee]

---

**🌟 Grants and Awards**

- [Year]: [Award name]

---

**🗞️ Publications**

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

---

**💬 Talks & Conferences**

{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
