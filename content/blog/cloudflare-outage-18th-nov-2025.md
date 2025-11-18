---
id: 10
title: 'Cloudflare Outage - 18th November 2025'
slug: 'cloudflare-outage-18th-nov-2025'
description: 'In this blog, we will discuss about the outage Cloudflare experienced on 18th November 2025'
published: true
posted: 2025-11-18
authorSlug: 'anish-ghimire'
banner: '/img/cloudflare-outage.png'
bannerAlt: 'Cloudflare Outage Banner Image'
tags: ['Cloudflare']
featured: true
---

[sarvalekh.com](https://sarvalekh.com) is back online to serve you technical blogs again after a couple of hours of downtime.

One month after the major AWS [outage](https://thundergolfer.com/blog/aws-us-east-1-outage-oct20), today the internet experienced an outage from [Cloudflare](https://www.cloudflare.com/en-gb/), which provides a range of internet services. We use [Cloudflare Pages](https://pages.cloudflare.com/) to deploy our [Nuxt Content](https://content.nuxt.com/) application.

We really don’t realize how many web applications depend on Cloudflare until the service provider stops working. From DNS management to deployments, Cloudflare has reached the point where it can power the complete web infrastructure. Some of the downtime detectors that were supposed to alert site owners about the downtime were impacted as well.

But the good thing is, [Dane Knecht](https://x.com/dok2001), the CTO of Cloudflare, has confirmed on [X](https://x.com/dok2001/status/1990791419653484646) that the issue has been resolved.

Dane writes:

> I won’t mince words: earlier today we failed our customers and the broader Internet when a problem in 
@Cloudflare
network impacted large amounts of traffic that rely on us. The sites, businesses, and organizations that rely on Cloudflare depend on us being available and I apologize for the impact that we caused.

> Transparency about what happened matters, and we plan to share a breakdown with more details in a few hours. In short, a latent bug in a service underpinning our bot mitigation capability started to crash after a routine configuration change we made. That cascaded into a broad degradation to our network and other services. This was not an attack.

> That issue, impact it caused, and time to resolution is unacceptable. Work is already underway to make sure it does not happen again, but I know it caused real pain today. The trust our customers place in us is what we value the most and we are going to do what it takes to earn that back.

The apologetic and regretful tweet clearly shows Dane’s seriousness and sense of accountability.

Such outages impact millions of users, ranging from individuals to businesses. At times, such situations are unavoidable, and what’s important is how we handle these tough periods and our willingness to fix the underlying issues.
