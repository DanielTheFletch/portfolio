---
title: "A Little Splash of Color: Portfolio Update v1.0.1"
slug: a-little-splash-of-color-portfolio-update-101
---

2024 is finally here! To ring in the new year, I wanted to show off a project I've been working on, and
to share a new academic achievement of mine in the form of a certificate from Harvard University.

After starting this past summer, I have now successfully finished CS50's Introduction to Programming
with Python course. CS50P was an absolute joyride of a course that I learned so much from. I'm very
much looking forward to wrapping up CS50x in the next month or so, and to (hopefully) taking more
CS50 courses throughout 2024.

With the completion of CS50P, though, I was required to submit a final project that served as a culmination
of everything taught in the class. I decided to develop a custom Python package to learn about the ins and
outs of preparing custom packages for distribution. This ultimately resulted in **color50**!

<div class="d-flex flex-column justify-content-center align-items-center my-4 py-4">
  <img alt="A colorful thumbnail featuring the text &quot;color50&quot; and the Python logo"
       class="img-fluid" src="{{ "/assets/img/proj-previews/preview-color50.png" | relative_url }}"
       style="width: 640px; height: auto;" />
</div>

**color50** is a custom Python package I developed to offer more options for printing in color at the
command line. Working on this project took me deep into all sorts of technical rabbit holes, from writing
Sphinx-style documentation to configuring packages for distribution via PyPI. I am very pleased
with how it turned out, and I hope fellow Python developers and CS50 students can find some utility in
using it!

<div class="my-4"></div>

---

<div class="my-4"></div>

#### **Portfolio Update v1.0.1**

<div class="my-4"></div>

##### **New certifications**
{% assign cert_title = "CS50's Introduction to Programming with Python" %}
{% assign cert_desc = "Awarded by CS50 at Harvard University." %}
- <a class="external-link fw-bold" href="{{ "/certifications/" | relative_url }}">{{ cert_title }}</a>
  &ndash; {{ cert_desc }}

<div class="my-4"></div>

##### **New projects**
{% assign proj = site.projects | find: "name", "proj-color50.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}

<div class="my-4"></div>

##### **Odds and ends**
- Featured Projects v1.0.1:
  - color50
  - RGB Defender
- Removed explicit mention of three featured projects to allow for more flexibility
- Changed résumé and CV to 2024 versions
- Updated site copyright to 2024

<div class="my-4"></div>

---

<div class="my-4"></div>

Thank you for reading and for taking interest in my new project. Cheers to a Happy New Year!

&mdash; Daniel