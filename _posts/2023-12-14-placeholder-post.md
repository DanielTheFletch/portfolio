---
title: Introducing Daniel's Online Portfolio Website
slug: introducing-daniels-online-portfolio-website
---

Hello, World! And welcome to my online portfolio website!

After attaining my computer science degree last December,
I started working on all sorts of projects in the pursuit of learning new skills. That said,
I did not take the time to find some way to organize all of these disparate works in an
easily-accessible, centralized location. Fast forward to December 2023, and voila! We're
finally here.

This truly has been a monumental undertaking for me&mdash;easily the largest solo development
project I have worked on to date. Following much trial and error with various technologies and
frameworks, I ultimately decided on Jekyll to be the core of my portfolio's functionality.
Jekyll's native framework offers exactly what I needed, particularly the ability to create
templated content and pages (like this one) while still maintaining the static nature of the site.

Then came... *the development cycle*. I tried to treat the development of my portfolio like a
professional development project, doing my best to use tools like Git to keep organized and
stay on track. The biggest hurdle I faced in development was easily my own underestimation of
how much time implementing some of my ideas would take (individual pages for each and every
project was a major offender on that front). Now that I'm here, though, I am very happy with
how everything turned out.

With all of that said, please take a look around the site and let me know what you think!
And, if you're interested, below are the myriad features coming with v1.0.0 of Daniel
Fletcher's Portfolio site.

---

##### **Core site pages**
{% assign page_link = site.data.navigation[0].link %}
- <a class="external-link fw-bold" href="{{ page_link | relative_url }}">Home</a> &ndash; Learn about
me, both personally and professionally. You can also find my primary contact information
here, as well as a brief walkthrough of the site's main pages&mdash;that's what you're
reading right now!
{% assign page_link = site.data.navigation[1].link %}
- <a class="external-link fw-bold" href="{{ page_link | relative_url }}">Activity</a> &ndash; A blog of
sorts that also serves as a changelog for my portfolio. I aim to create new posts whenever
I update the site, whether that be adding new projects, implementing new features, or
working in key bug fixes.
{% assign page_link = site.data.navigation[2].link %}
- <a class="external-link fw-bold" href="{{ page_link | relative_url }}">Projects</a> &ndash; Take a look
at the multitude of projects I have worked on, ranging from Harvard University academic
submissions to personal passion projects. This page contains a rotating selection of three
featured projects and a comprehensive index of all my past project work.
{% assign page_link = site.data.navigation[3].link %}
- <a class="external-link fw-bold" href="{{ page_link | relative_url }}">Certifications</a> &ndash; Check
out all the certifications I have earned so far in my computer science journey, complete
with links to the corresponding certification credentials.
{% assign page_link = site.data.navigation[4].link %}
- <a class="external-link fw-bold" href="{{ page_link | relative_url }}">Links</a> &ndash; All of my
relevant online profiles are listed here, including those found on learning sites,
networking platforms, and the like.
{% assign page_link = site.data.navigation[5].link %}
- <a class="external-link fw-bold" href="{{ page_link | relative_url }}">Resources</a> &ndash; Look into
some of the *incredible* resources that have helped me get to where I am now. Seriously, I
would not be where I am today without these resources and the amazing people behind them.
All relevant links included.

---

##### **Starter pack of published projects**
{% assign proj = site.projects | find: "name", "proj-survey-form.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-tribute-page.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-technical-documentation-page.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-product-landing-page.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-rgb-defender.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-personal-portfolio.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-palindrome-checker.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-roman-numeral-converter.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-caesars-cipher.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-telephone-number-validator.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-cash-register.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-recipes-from-hyrule.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}
{% assign proj = site.projects | find: "name", "proj-random-quote-machine.html" %}
- <a class="external-link fw-bold" href="{{ proj.url | relative_url }}">{{ proj.title }}</a>
  &ndash; {{ proj.desc }}

---

##### **Odds and ends**
- Featured Projects v1.0.0:
    - RGB Defender
    - Recipes from Hyrule
    - Random Quote Machine
- Core technologies behind site functionality linked in footer
- Links opening a new tab denoted by&nbsp;&nbsp;**<span class="fa-solid fa-up-right-from-square"></span>**
- Reddish-blue color scheme
- Spinning-gear CSS animation on Home page

---

Thanks so much for taking the time to read this post. I already have some exciting ideas cooking for future projects, and I'm looking
forward to sharing them here. Stay tuned!

&mdash; Daniel