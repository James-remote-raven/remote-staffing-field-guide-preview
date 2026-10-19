# Remote Staffing Field Guide

Live site: https://james-remote-raven.github.io/remote-staffing-field-guide-preview/

A static, public information site about remote staffing. The editorial brand leads the experience; every page links to a clear publisher disclosure on the About page, where Remote Raven is named. The current GitHub Pages URL retains “preview” until a permanent domain is chosen.

## Pages

- index.html — home and guide library
- guide.html — defining a remote role
- interviews.html — structured, job-related interviews
- onboarding.html — planning the first month
- about.html — purpose, editorial approach, and publisher disclosure

The guides use practical examples and link to the primary sources behind factual claims: the International Labour Organization's telework guidance, the U.S. Office of Personnel Management's structured interview guidance, and NIST's enterprise telework security guidance. The ILO article was published in 2020 and the NIST publication in 2016; their publication dates and scope are stated on the relevant guide pages.

The site has no forms, accounts, payments, analytics scripts, third-party JavaScript, backend, or connection to the private content engine or Remote Raven internal systems. The content engine and knowledgebase are not part of this repository. GitHub Pages serves only these static files.

## Local preview

Run Python's static server from this folder:

    python -m http.server 8765

Then open http://127.0.0.1:8765/ .
