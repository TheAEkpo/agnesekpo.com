---
title: "Data Governance: More Than a Compliance Checkbox"
date: 2025-04-19
comments: true
layout: splash
read_time: true
author_profile: false
categories:
  - blog
tags:
  - Data Governance
  - Data Ethics
  - PIPEDA
  - data science
  - GDPR
excerpt: "*What I have learned about truth, trust, and responsibility in a world run on data.*"
header:
  teaser: /assets/images/data_governance.png
---

![Data Governance meme generated with Sora](/assets/images/data_governance.png){: .align-center}

It started with a missing column in a spreadsheet.

During my internship on a maternal health project, I was building out the monitoring and evaluation framework. The data was pouring in from multiple communities, and at first glance, everything looked fine, but a critical field was always blank. That field was supposed to track whether a mother had received her follow-up care, but no one had filled it out, and no one knew who was responsible for it. Yet this field shaped our understanding of impact and informed decisions about funding, program design, and future interventions.

At the time, I chalked it up to poor data entry. Now, years into a career that has taken me through hospitals, fintech firms, nonprofits, and analytics consultancies, I understand what it was: a data governance failure, a gap in responsibility.

This pattern is all too familiar. Regardless of the sector, I’ve encountered the same foundational issue: no shared definitions, no clear ownership, and no system for ensuring data is meaningful, accurate, or trustworthy. Everyone wants dashboards, but few stop to ask if the data feeding them can be trusted.

That is what data governance is about, not just processes or policies, but culture and accountability. It is how we safeguard truth because when we do not, the stories we tell with data begin to fall apart.

### What a Strong Governance Framework Looks Like.

The most effective data governance frameworks I have seen are not just about structure; they are about clarity. They define who owns each dataset, what terms mean, how quality is maintained, and who is accountable for decisions based on that data. These frameworks prevent ambiguity from quietly eroding the reliability of our insights.

One of the most practical governance models I have worked with borrowed from <a href="https://datagovernance.com/the-dgi-data-governance-framework/"> the Data Governance Institute’s ten-component framework</a>. It went beyond identifying data stewards, it laid out who governed the people who governed the data, strategic leads, escalation channels, and even metrics for success. Most importantly, it reminded me that good governance improves both data quality and the quality of decisions built on that data.

In contrast, I’ve seen firsthand how fragile things become in its absence. On one project, the term “default” was interpreted differently across compliance, analytics, and marketing teams. Every model and report that depended on that term became unreliable. It was not until we established a shared glossary and a control process that we regained our footing.

Data governance is not just about avoiding disaster. It is about enabling collaboration and decision-making that is consistent, scalable, and defensible.

### Beyond the Law: Ethics and Legislation in a Shifting World.

Even with the most robust frameworks, data governance is not complete without the guiding hand of ethics and the structure of legislation.

In Canada, where I currently live and work, data privacy is governed by the Personal Information Protection and Electronic Documents Act (PIPEDA), which emphasizes informed consent and transparency. The proposed Consumer Privacy Protection Act (CPPA) is set to take this further, giving individuals greater control and introducing stronger enforcement mechanisms.

In the UK, where I completed my master’s in data science, the General Data Protection Regulation (GDPR) remains a global benchmark. It outlines lawful processing, purpose limitation, and meaningful user rights like the ability to access or erase one’s data.

In the US, the legal landscape is more fragmented. HIPAA governs health data, while states like California have enacted laws such as the CCPA and the more recent (California Privacy Rights Act) CPRA, each offering varying degrees of consumer protection. Financial data falls under yet another set of rules.

But here’s what I’ve come to understand: compliance is only the floor. It cannot stop biased models from being deployed, it will not fix flawed assumptions or tell you when your insights are missing key populations, and it certainly cannot guarantee that people will not be harmed by the conclusions your data systems produce.

I recall a project where we built a predictive tool for pediatric hospital readmissions. It passed all compliance checks, yet something felt off. A closer look revealed that children with rare diseases were severely underrepresented in the training data, and the model deprioritized them. Legally, we were in the clear. Ethically, it was a failure that could have cost lives.

This is where data ethics becomes non-negotiable. It forces us to ask: *Should we build this? Are we reinforcing systemic inequality? Is institutional convenience coming at the expense of fairness for the individual?*

These are not easy questions, but they are essential because data is no longer just a technical asset; it is a social force. It informs medical care, insurance pricing, housing access, job opportunities, and public policy. The consequences of neglecting ethics are far too serious to ignore.

Across my career, I’ve learned that data governance, legislation, and ethics are not optional side quests. They are the foundation. And they demand more than technical competence. They demand intellectual humility, the ability to think beyond the dataset, and the courage to challenge systems that prioritize speed over stewardship.

Whether you are writing a SQL query, designing a dashboard, launching a machine learning model, or cleaning survey data, you are shaping the way people are seen, understood, and served. So, define the field, document the source, ask who benefits and who is left out, challenge the assumptions, and above all, remember that data does not govern itself; people do.

We are all data stewards now, and that responsibility is both a burden and a privilege. Because in this data-driven world, how we choose to govern, protect, and interpret our data will define the kind of society we create.

And that is the kind of work worth doing.

{% if site.comments.provider == "giscus" %}
  <script src="https://giscus.app/client.js"
          data-repo="{{ site.comments.giscus.repo }}"
          data-repo-id="{{ site.comments.giscus.repo_id }}"
          data-category="{{ site.comments.giscus.category }}"
          data-category-id="{{ site.comments.giscus.category_id }}"
          data-mapping="{{ site.comments.giscus.mapping }}"
          data-reactions-enabled="{{ site.comments.giscus.reactions_enabled }}"
          data-emit-metadata="{{ site.comments.giscus.emit_metadata }}"
          data-input-position="{{ site.comments.giscus.input_position }}"
          data-theme="{{ site.comments.giscus.theme }}"
          data-lang="{{ site.comments.giscus.lang }}"
          data-loading="{{ site.comments.giscus.loading }}"
          crossorigin="{{ site.comments.giscus.crossorigin }}"
          async>
  </script>
{% endif %}
