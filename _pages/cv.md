---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

Download the CV as a [PDF file]({{ base_path }}/files/carmen_zheng_cv.pdf).

**👩‍🎓 Career and Education**

- 2026-Present: Clinical Neuropsychologist, **The Neuro Group**
- 2023-2025: Clinical Neuropsychology Registrar, **Royal Melbourne Hospital; Austin Health; Alfred Health**
- MPsych in Clinical Neuropsychology, **University of Melbourne**
- B.A (Honours) in Psychology, **University of Melbourne**
- B.A in Psychology & Sociology, **University of Melbourne**

---

**🏛️ Leadership and Service**

- 2025-Present: ECR Representative, [OHBM-Aus Committee](https://ohbm-aus.github.io)
- 2024-2026: Graduate Student Representative, [Florey Equity in Science](https://florey.edu.au/careers-and-study/florey-associations-and-committees/equity-in-science-committee/), **Florey Institute**
- 2024-2025: Austin Students Representative, [Students of Florey](https://florey.edu.au/careers-and-study/students-of-the-florey-institute/), **Florey Institute**
- 2021-2022: Co-President, [Neuropsychology Students' Society](https://psychologicalsciences.unimelb.edu.au/study/current-students/school-societies/nss#about), **University of Melbourne**

---

**🌟 Grants and Awards**

- 2026: Epilepsy Society of Australia Travel Scholarship
- 2026: Philanthropic Postgraduate Travel Award
- 2023: Research Training Program

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
