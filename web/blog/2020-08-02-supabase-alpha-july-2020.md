---
title: Supabase Alpha July 2020
description: Five months of building
author: Paul Copplestone
author_title: Supabase
author_url: https://github.com/kiwicopple
author_image_url: https://avatars2.githubusercontent.com/u/10214025?s=400&u=c6775be2ae667e2acae3ccd347fed62bb3f5b3e7&v=4
authorURL: https://github.com/kiwicopple
tags: 
    - supabase
---

After 5 months of building, we're releasing one of our most anticipated features: Supabase Auth. 

<!--truncate-->

### Quick Demo

Watch a full demo:

<iframe width="640" height="385" src="https://www.loom.com/embed/17fbbc3bc9b2459eb0efbbb174b2ce7b" frameborder="0" allowFullScreen></iframe>

### Auth

This month, we're ecstatic to announce a feature we think you'll love: Supabase Auth. It's too big to fit into a monthly update so look out for a full update in the next few days.

We want to make it easy to get started adding Auth to your app, so we've released a [simple example and a video tutorial](https://dev.to/supabase/create-a-slack-clone-with-next-js-and-supabase-3lhd) which shows you how to implement a basic auth system using PostgreSQL's Row Level Security.

### Table Editor

We've made some massive improvements to our Table Editor that we're excited to share.

#### Relationship drill down

Last month we made it easy to drill into your table relationships. This month, we make it possible to drill multiple levels deep. 

<video width="99%" autoplay="" loop="" muted="" playsinline="" controls="true">
<source src="/videos/relational-drilldown-zoom.mp4" type="video/mp4" />
</video>


#### Add, delete, and download rows

We're making it easier to manipulate your data. Next month, you'll be able to add and remove columns directly from the Table view.

<video width="99%" autoplay="" loop="" muted="" playsinline="" controls="true">
<source src="/videos/csv-download-zoom.mp4" type="video/mp4" />
</video>

### New Postgres Extensions

If you launch a new Supabase project, you'll have access to several new Postgres extensions:

- [pgsql-http](https://github.com/pramsey/pgsql-http): HTTP client for PostgreSQL, retrieve a web page from inside the database.
- [pgjwt](https://github.com/michelp/pgjwt): PostgreSQL implementation of JSON Web Tokens
- [plpgsql_check](https://github.com/okbob/plpgsql_check): a linter tool for language PL/pgSQL
- [pljava](https://github.com/tada/pljava): write Java in your stored procedures, triggers, and functions

### Kaizen

We have a number of small improvements:

- Added Auth documentation to the auto-generated docs in each project
- Added a new `or` filter [to the client library](https://supabase.io/docs/library/get#or)
- Table View now remembers which tabs you had open.
- We have [released](https://github.com/supabase/pg-api/releases) a lot of new functionality to [pg-api](https://github.com/supabase/pg-api), a server for for managing Postgres internals via a REST interface.
- Performance: the "flash of black" which was appearing on page transition is now gone

### Get started

- Start using Supabase today: [app.supabase.io](https://app.supabase.io)
- Make sure to [star us on GitHub](https://github.com/supabase/supabase)
- Follow us [on Twitter](https://twitter.com/supabase_io)
- Become a [sponsor](https://github.com/sponsors/supabase)