---
title: "Speaking SQL"
date: 2025-06-12
comments: true
layout: splash
read_time: true
author_profile: false
categories:
  - blog
tags:
  - career-pivot
  - data-science
  - women-in-tech
  - health-tech
excerpt: "How I learned to talk to databases without losing my mind"
header:
  teaser: /assets/images/sql_speaking.png
---

![Speaking structured query language](/assets/images/sql_speaking.png){: .align-center}
*Conversation with a database*

When I first heard of SQL, I thought it was just another tech skill to tick off. You know, one of those things recruiters look for. So I opened YouTube, typed in “SQL tutorial,” and expected to figure it out in an hour. Big mistake.

SQL was nothing like what I had imagined. It looked simple, but it had its own rules, its own rhythm. It reminded me of learning to ride a bicycle. It looked easy until I fell a few times and realized I had no clue what I was doing. I could copy and paste queries that worked, but I did not understand why they worked or what I was actually asking the database to do.

But everything changed during a project I did a few years back, I was building a medication tracking system. It had to pull real-time data from multiple tables: patients, prescriptions, pharmacy inventory, and administration records. I could not rely on guesswork anymore because this system would impact how care was delivered. It had to be right.

That was the moment SQL stopped being “just syntax” and started feeling like a language. Not the spoken kind, but one you use to think and structure your thoughts in order to ask the right questions. It became my way of communicating with data.

---

## SQL Is Not Just Code. It Is Language

When I finally slowed down to learn SQL properly, I realized it is not about writing fancy code. It is about learning how data speaks and how to listen. Every clause has a role. Every JOIN is a connection in the story. A misplaced WHERE clause can tell a completely different version of events.

I once wrote a query that was supposed to show the number of patients with post-op complications. Everything looked good, until someone asked why our numbers were higher than expected. I had filtered the data after a JOIN instead of before. That single mistake included records that should not have been there. That is when it hit me - logic matters more than length.

SQL made me slow down and think. It made me structure my questions better. It made me curious about *why* things were showing up the way they were.

---

## Why SQL Feels Like a Secret Superpower

You do not realize how powerful SQL is until you start using it on real problems. Whether I was working on hospital dashboards, nonprofit impact evaluations, or marketing reports for a fintech client, SQL was always in the background helping me extract clarity from chaos.

It is quiet. It is direct. It does not need loops or complex logic. It just needs you to be clear about what you want. When you finally write a clean, efficient query and the results come back exactly as expected, it feels like solving a puzzle without forcing the pieces.

Over time, SQL became more than a tool. It became a thinking framework. It made me ask better questions before even touching the keyboard.

Just recently, I encountered a rather interesting SQL test during an interview. The interviewer stated a preferred SQL syntax but allowed the use of any syntax I preferred, but I knew he really wanted his preferred syntax, Oracle. So I used Oracle.

This made me smirk to myself, as it highlighted the very point I've been making: SQL is a language with many dialects, and understanding the underlying logic is far more important than adhering to a single rigid syntax.

It reinforced my belief that once you grasp the core concepts of how to communicate with data, the specific syntax becomes a mere detail, easily adaptable to different environments and preferences. It is like knowing how to express an idea in English, and then being able to translate it into French or Spanish—the idea remains the same, only the words change.

---

## How I Actually Learned SQL

I did not learn SQL by watching one big tutorial or reading one perfect book. I learned it in fragments, through real deadlines and messy spreadsheets and a lot of trial and error. But a few resources stood out and made the process less painful.

Here are some that really helped me, and I still return to them from time to time:

### 📚 Books

- [SQL for Data Scientists by Renee M. P. Teate](https://www.amazon.com/SQL-Data-Scientists-Beginners-Building/dp/1119669367)
- [SQL Queries for Mere Mortals by John L. Viescas and Michael J. Hernandez](https://www.amazon.ca/s?k=sql+queries+for+mere+mortals&gad_source=1&hvadid=587950863789&hvdev=c&hvexpln=0&hvlocint=1002478&hvlocphy=9076649&hvnetw=g&hvocijid=8316349698237162224--&hvqmt=e&hvrand=8316349698237162224&hvtargid=kwd-301036621111&hydadcr=22463_13336656&mcid=95eca8901e113e6f96b7c4096ebc6de8&tag=googcana-20&ref=pd_sl_8ly9zziriy_e)
- [Learning SQL by Alan Beaulieu (O'Reilly)](https://www.amazon.ca/Learning-SQL-Alan-Beaulieu/dp/0596007272/ref=sr_1_4?dib=eyJ2IjoiMSJ9.I6KfAXJX85-XUSIt_83hk_bWwVAvX2lqfcVRSGNIgRf0Ca4hUNt7MQMbRGSR7WQN3KB686mnWQEZCjYUFPcbeN5bdEb24GOKB6dTGTH91A0.35syG0ZQqqrEHmZiRLed9jLQHqSzPt0eXkxtG9Ot_do&dib_tag=se&gad_source=1&hvadid=324956203162&hvdev=c&hvexpln=0&hvlocint=1002478&hvlocphy=9076649&hvnetw=g&hvocijid=774513953490095109--&hvqmt=e&hvrand=774513953490095109&hvtargid=kwd-312865785332&hydadcr=16084_9598702&keywords=learning+sql+by+alan+beaulieu&mcid=233d7f47c667364ebede48730efb593b&qid=1749771997&sr=8-4)

### 🎓 Courses and Practice Platforms

- [Mode SQL Tutorial](https://mode.com/sql-tutorial/)
- [Khan Academy – Intro to SQL](https://www.khanacademy.org/computing/computer-programming/sql)
- [StrataScratch](https://www.stratascratch.com/)
- [LeetCode SQL Practice](https://leetcode.com/problemset/database/)
- [SQLBolt](https://sqlbolt.com/)

### 🛠️ Tools That Helped

- [DB Fiddle](https://www.db-fiddle.com/)
- [SQL Fiddle](http://sqlfiddle.com/)
- [DataCamp SQL Fundamentals Track](https://www.datacamp.com/tracks/sql-fundamentals)

---

## What I Know Now That I Wish I Knew Then

If I could go back and tell myself one thing about learning SQL, it would be this—take your time. It is not just about learning to code. It is about learning to *think like data*. You are training your brain to ask sharper questions, think in relationships, and draw meaning from structure.

SQL helped me slow down and ask, “What exactly am I trying to say?” And often, that question alone helped me solve problems even before writing the query.

So if you are just starting out and feeling confused or overwhelmed, that is perfectly normal. You are not doing it wrong. You are just learning a new language. One that does not shout or sparkle, but one that quietly powers decisions behind hospitals, nonprofits, banks, and apps.

And once you start speaking it fluently, even just a little, the world of data starts making more sense.

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
