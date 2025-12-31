---
title: Hello World!
date: 2025-12-31 01:38:00 -0500
categories: [General]
tags: [homelab, networking, truenas]
description: Look at that, a new site where I can share my configurations, testing, and thoughts on different topics relating to Docker, TrueNAS, networking, and homelab in general
toc: true
comments: true
media_subpath: /assets/posts/2025-12-31-Hello-World!/
image:
  path: img/preview.webp
  lqip: img/preview-lqip.webp
---
**Hello Everyone!** 👋
Welcome to my new blog. The purpose of this site is to document my testing and development journey while sharing useful configurations, scripts, and "lessons learned" with the homelab community.
By day, I work as a Network Architect, but by night, I am usually breaking (and fixing) things in my homelab. My primary focus lately has been on **TrueNAS Scale**, **Docker**, and advanced networking configurations.
If you have ever spent hours searching for a specific configuration only to find a forum post from 2013 that *almost* helps, this blog is for you. My goal is to share the information I wish I had when I originally ran into these issues.

## How Was This Site Made?
This site is built as a static site using **[Jekyll](https://jekyllrb.com/)** and hosted for free on **GitHub Pages**.
I am using the **[Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)** theme, which provides a clean, responsive design with built-in dark mode, tagging, and category support. It is a fantastic template for documentation and technical writing.
In a future post, I plan to write a full guide on how to host your own static website on GitHub Pages and how to customize the Chirpy theme to fit your needs.

## Future Topics and Projects
Most of the content here will revolve around the technologies I am currently deploying or testing. Lately, I have been deep-diving into Docker networking behaviors, `iptables`, and TrueNAS scale idiosyncrasies.
Here is a sneak peek at some upcoming topics:
* **Docker MACVLAN Networks**: Getting containers to appear as physical devices on your network.
* **Docker IPVLAN Networks**: A lighter-weight alternative to MACVLAN.
* **TrueNAS Networking**: Deep dives into VLANs, Trunks, and Bridge interfaces.
* **Isolated Networks**: Creating "One-to-Many" internal networks for secure container communication.
* **Persistent `iptables` on TrueNAS**: How to make firewall rules survive a reboot.
* **Managing Custom Applications**: Going beyond the official TrueNAS catalog.

I will also be sharing `docker-compose.yml` files and various automation scripts I create along the way.
Thanks for stopping by, and I hope you find something useful here!
