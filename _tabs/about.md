---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---
## Hello Everyone! :wave:
By day I work as a network architect developing and supporting solutions for customers, and by night I bide my
time and curiosity by experimenting in my homelab. The purpose of this blog is to document said testing and 
development, while sharing useful knowledge and configurations with all of you.

In my homelab I have been typically focusing on Docker running in TrueNAS Scale. I also have been messing
around with some VPS instances for hosting some resources and providing remote access to my homelab. Most of my
experience has revolved around enterprise routing, switching, and NAC. I can tell you that I have already learned
so much from setting up my own services, though I still have a ways to go.

If anyone has any questions or comments, please feel free to reach out via any of the included social links.
In the mean time, have fun exploring my blog.

{% assign email_parts = site.social.email | split: '@' %}
<a href="javascript:void(0)" 
   onclick="window.location.href = 'mailto:' + ['{{ email_parts[0] }}','{{ email_parts[1] }}'].join('@');">
  Contact
</a>
{: .text-center }
