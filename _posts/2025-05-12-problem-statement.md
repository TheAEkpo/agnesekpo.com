---
title: "Getting the Problem Statement Right"
date: 2025-05-12
comments: true
layout: splash
read_time: true
author_profile: false
categories:
  - blog
tags:
  - learning
  - data analysis
  - data science
  - web development
excerpt: "As data professionals, it's easy to rush into analysis, dashboards, or modeling without first confirming what we're truly trying to solve. "
header:
  teaser: /assets/images/problem-solver.jpeg
---
You know that moment when you're deep into a project, SQL scripts flowing, your dashboard shaping up nicely, and everything seems to be on track, until someone from leadership leans in and asks, "What exactly were we trying to fix here?" And for a second, you pause, because suddenly it hits you: you've been solving a version of the problem that no one really asked for.

Well, that moment used to terrify me and not because I didn’t do the work, but because I did too much of the wrong work. In one project for a retail client, I was asked to "help improve customer conversion rates." Naturally, I dove into web analytics, user funnel drop-offs, time-on-page metrics. I built a great set of insights, complete with heatmaps and predictive segments. Only to find out after almost two weeks in that the real concern was cart abandonment due to stock unavailability, not website behavior at all.

I had interpreted the problem as a marketing issue. They were really asking for inventory intelligence. And no amount of segmentation was going to fix that mismatch.

![Quote by V. Anton Spraul](/assets/images/problem-statement.png){: .align-center}

What I learned, slowly and through a few more of those moments, is that understanding the problem is not a step you rush through… It is the step, and when you skip it, everything else becomes a cascade of best guesses dressed as insight.

[Lenny Rachitsky’s](https://www.lennysnewsletter.com/p/a-three-step-framework-for-solving) breakdown of the problem-solving trap really hit me hard. He explains how we often go from a vague ask to designing solutions without validating whether we even understand what’s broken. We build fast, then backtrack, then patch, then burn out. It’s such a familiar rhythm. And it’s the exact opposite of what thoughtful, impactful analysis should look like.

That’s why I now force myself to slow down at the beginning. I try to write out the problem in plain English. If it sounds like it could mean two or three different things, I take that as a sign to dig deeper. I talk to the people experiencing the issue. I look at operational metrics alongside stakeholder pain points. I ask annoying questions like, “What happens if we don’t solve this?” and “Who actually feels the pain here?” These days, I don’t start building until I can say the problem out loud and have everyone in the room nod in agreement.

The irony is, when I first got into data, I thought the challenge would be in the math or the code. But the real challenge is upstream. It’s getting clarity. It’s stripping away assumptions. It’s realizing that people often ask for what they think the solution should be, when what they really need is help defining the problem more clearly.

Once you get that clarity, everything changes. Suddenly, your analysis isn’t just accurate, it’s useful. People see themselves in your findings. Your dashboard answers the question they were actually asking, not the one they typed in an email.

I still have old reports I built that are technically sound but completely useless, and now I know why. They were solutions looking for a better question.

If you're a data analyst, data scientist, or just someone solving messy, ambiguous problems, what problem-solving technique do you use? If you do not, let this be a gentle reminder. Before the code, before the dashboard, before the model, ask yourself: “Do I really understand what we’re trying to solve?” Because the most painful kind of wasted effort is the kind that looks productive on the surface, but never stood a chance of solving the real thing.

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
