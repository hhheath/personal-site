---
title: The Beginning of Mindr
teaser: I need a self-hostable way to send myself reminders on a recurring basis. So, let's build it for everyone to use.
date: 2022-11-08
---

Created on: {{page.date}}

_This the first edition of (hopefully) many as I build this app in public._

I'm a forgetful person. Maybe it's just who I am, maybe it's my undiagnosed ADHD like The Algorithms think I have. Either way, I need a self-hostable way to send myself reminders on a recurring basis. Things like: Fill up water bottle, drink water, load/unload dishwasher, etc. So, let's build it for everyone to use.

Sure, I could get this done with just a simple simple script for each task, but what's the fun in that? I want a big project for myself, so this is it!

## How

At home, my own server a set of services in docker containers behind a [Traefik](https://traefik.io/traefik/) proxy. I host things like Nextcloud, ArchiveBox, Wallabag, etc. So, Mindr will be a docker-first, self-hostable application. 

My initial thoughts are to use [Temporal](https://temporal.io) as the backend for the jobs that will be created. Ideally, a user will login, and be able to create a new **remindr**. Each remindr will schedule a new workflow run in Temporal. Each remindr will have, at launch, 3 options for sending remindrs: 

1. SMS - through twilio.
1. Email - through sendgrid. 
1. Webhook - just an HTTP request to a URL. 

## Thoughts of Grandeur

This will, without a doubt, always be a 100% free & open source project and always available for those who want to run & scale their own version. 

I also want to try to run a managed service for this, as well. I don't know how I'd do that, but it's something I'd like to do. 

---

In any case, I always want your input! Hit me up on [Mastodon](https://mastodon.social/@hheath_). Eventually, I'll find a good place to put a repo and start working on it now. 

Maybe [Gitea](https://gitea.io/en-us/)?

Until next time... 
