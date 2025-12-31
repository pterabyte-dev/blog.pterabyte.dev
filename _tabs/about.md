---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---
## Hello Everyone! 👋

By day, I work as a **Network Architect** developing and supporting solutions for customers. By night, I satisfy my curiosity by experimenting in my homelab. 
The purpose of this blog is to document my testing and development journey while sharing useful knowledge and configurations with all of you.

### My Homelab Focus

Most of my professional experience revolves around enterprise routing, switching, and NAC, but my homelab allows me to branch out. Currently, I am focusing on:

* **Docker** running in **TrueNAS Scale**
* **VPS instances** for hosting resources and remote access
* **Static Site Generation** (like this site built with Jekyll & Chirpy!)

I have already learned so much from setting up my own services, though I still have a ways to go.

### Get in Touch
If you have any questions or comments, please feel free to reach out via the social links in the sidebar or send me an email directly below.

{% assign email_parts = site.social.email | split: '@' %}
<a href="javascript:void(0)" 
   onclick="window.open('mailto:' + ['{{ email_parts[0] }}','{{ email_parts[1] }}'].join('@'), '_blank'); return false;"
   class="btn"
   style="background-color: var(--sidebar-active-color); color: var(--card-bg); border: none;">
  <i class="fas fa-envelope"></i> Email Me
</a>
{: .text-center }
