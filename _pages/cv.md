---
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
description: "Education, research experience, teaching, practice, and academic service of Jeffrey Wong."
---

Jeffrey Wong · Faculty of Health Sciences, Simon Fraser University · [jow3@sfu.ca](mailto:jow3@sfu.ca)

## Education

**MSc, Health Sciences** — Simon Fraser University, 2026–present<br>
Supervisor: Dr. Kiffer Card

**BA, Sociology** — Trinity Western University, 2022–2026

## Research experience

**Graduate Research Assistant**<br>
[Healthy Ecologies and Lifestyles (HEAL) Lab](https://heal-lab.ca)<br>
Faculty of Health Sciences, Simon Fraser University<br>
September 2026–present · Supervisor: Dr. Kiffer Card

Provincial scale-up and evaluation of social prescribing for older adults in British Columbia.

**Research Assistant and Knowledge Translation Lead**<br>
[Innovation in Dementia and Aging (IDEA) Lab](https://idea.nursing.ubc.ca)<br>
MacIsaac School of Nursing, The University of British Columbia<br>
January 2025–September 2026 · Supervisor: Dr. Lillian Hung

Led a scoping review of community-based social supports for 2S/LGBTQ+ older adults, collaborated with community partners throughout the review, and managed lab social media.

**Research Assistant**<br>
Department of Psychology, Trinity Western University<br>
November 2025–June 2026 · Supervisor: Dr. Yeeun Archer Lee

Contributed to a brief report and infographic on loneliness and social isolation among sexual and gender minority older adults, including secondary analysis of the Canadian Social Connection Survey.

**Research Assistant**<br>
Vancouver Coastal Health<br>
September 2023–December 2024 · Supervisor: Ms. Margurite Wong

Supported implementation and evaluation of a virtual seated dance program for older adults in long-term care, with dissemination at research and gerontology conferences.

## Teaching

**Graduate Teaching Assistant**<br>
Faculty of Health Sciences, Simon Fraser University<br>
September 2026–present · HSCI 341: Fundamental Epidemiological Concepts and Approaches

**Teaching Assistant**<br>
Department of Sociology and Anthropology, Trinity Western University<br>
January–May 2026 · SOCI 101: Introduction to Sociology

See the [teaching page]({{ '/teaching/' | relative_url }}) for details.

## Community practice

**Seniors Community Connector**<br>
Langley Senior Resources Society, 2025–2026

Co-developed wellness plans with older adults aged 65 and over, connected people with community resources, and supported home visits and meal deliveries.

**Human Services Practicum Student**<br>
Langley Senior Resources Society, 2025

Developed a program evaluation framework and follow-up survey for social prescribing referrals from health services to the community, and conducted three-month follow-up calls.

## Awards and fellowships

- **EPIC-AT Fellowship**, AGE-WELL, 2026–2027 — CAD $8,000
- **Student Travel Grant**, Canadian Association on Gerontology, 2026 — CAD $330

## Publications

{% for category in site.publication_category %}
{% assign category_posts = site.publications | where: 'category', category[0] | sort: 'date' | reverse %}
{% if category_posts.size > 0 %}
<h3>{{ category[1].title }}</h3>
{% for post in category_posts %}
{% include publication-entry.html %}
{% endfor %}
{% endif %}
{% endfor %}

Conference contributions are listed on the [presentations page]({{ '/talks/' | relative_url }}).

## Academic and community service

- **Education Committee member**, Network of Networks (N2), 2024–present
- **Co-Lead**, Canadian Social Prescribing Student Collective, 2024–present
- **Conference co-host**, N2 Annual Conference, 2025
- **Volunteer**, Canadian Red Cross Health Equipment Loan Program, 2022–2025

## Peer review

- *Perspectives*, Canadian Gerontological Nursing Association, 2026
- *Journal of Medical Internet Research* and *JMIR Research Protocols*, 2025
- *Journal of the American Medical Directors Association*, 2025

## Professional memberships

- AGE-WELL HQP Affiliate, 2025–present
- Canadian Public Health Association, 2025–present
- Canadian Association for Health Services and Policy Research, 2025–present
- Canadian Association on Gerontology, 2023–present
- Canadian Social Prescribing Student Collective, 2023–present

## Training

- San'yas Indigenous Cultural Safety Training
- TCPS 2: CORE 2022
