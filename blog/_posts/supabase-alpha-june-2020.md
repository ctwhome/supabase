---
title: Supabase Alpha June 2020.
description: Four months of building.
excerpt: We're now 4 months into building Supabase, which means another major update. Here's a few things we think you'll love in this release.
coverImage: /assets/blog/dynamic-routing/cover.jpg
date: '2020-07-01T05:35:07.322Z'
author:
  name: Paul Copplestone
  picture: https://github.com/kiwicopple.png
ogImage:
  url: '/assets/blog/dynamic-routing/cover.jpg'
tags:
  - supabase
---

We're now 4 months into building [Supabase](https://supabase.io), which means another major update. Here's a few things we think you'll love in this release.

<!--truncate-->

### 4 minute demo

Watch a full demo:

<iframe width="640" height="385" src="https://www.loom.com/embed/b3ba79c1633d464ea758e0796bbb39da" frameborder="0" allowFullScreen></iframe>

### View relational data

We're sometimes asked how we will make Postgres as simple as Firebase, since Postgres is a relational database. This month we're making our first steps to prove that relational databases can be even easier to use than document stores. We're releasing an excel-like editing interface which can drill down into your relational data.

<iframe width="640" height="385" src="https://www.loom.com/embed/c6d504bb0a1c43e9bf65cb2aef2949d5" frameBorder="0" allowFullScreen></iframe>

### Manage JSON data

Postgres is an amazing database, giving the flexibility of a document store with the power of a RDBMS. If you use `JSON` data in Postgres, then we want to make that easy too. Supabase detects when your column is `JSON` or `JSONB`, and provides an easy way to edit and view your data. More improvements coming soon for this feature!

<iframe width="640" height="385" src="https://www.loom.com/embed/0b03ac2858324cfabdc6a202c93673f3" frameBorder="0" allowFullScreen></iframe>

### Choose your region

If you noticed a bit of latency on Supabase, it's because your projects were previously set up in Singapore. It was always our intention that you'd be able to choose your database region, and this month we've delivered it. In the next releases we'll even allow you to go multi-region, instantly replicating your database close to your customers.

<iframe width="640" height="385" src="https://www.loom.com/embed/1dcc1bca2ebc45e296e732a66a462c61" frameBorder="0" allowFullScreen></iframe>

### Backups

A guiding principle at Supabase is zero lock-in. So this month we are exposing your daily database backups on the dashboard, giving you a simple way to migrate off Supabase. We have a lot more to build in this space (`WAL-G!`), so watch this space.

<iframe width="640" height="385" src="https://www.loom.com/embed/fc1cb9b395eb4c408c7137bf8e6e1963" frameBorder="0" allowFullScreen></iframe>

### Kaizen

We have a number of small improvements:

- Improved SQL editor - with better syntax highlighting
- Improved API docs - with more code snippets
- UX improvements - with a simplified and consistent UX

### Hiring

- This month we [welcome Steve Chavez to the team](/blog/2020/06/15/supabase-steve-chavez). Steve is a maintainer of PostgREST, one of the core tools which makes Supabase possible. 
- We're hiring a part-time designer or UX expert. See more [here](https://news.ycombinator.com/item?id=23708351).

### Get started

- Start using Supabase today: [app.supabase.io](https://app.supabase.io)
- Make sure to [star us on GitHub](https://github.com/supabase/supabase)
- Follow us [on Twitter](https://twitter.com/supabase_io)
- Become a [sponsor](https://github.com/sponsors/supabase)



 