+++
date = 2025-10-20T01:14:54-08:00
draft = true
title = 'AWS Outage Explained,  What it Tells Us.'
weight = 10
[params]
  author = 'Hadi Al Hassan'
+++

Today's "Productive Monday" was off to a weird start, with Amazong Web Services (AWS) facing a severe outage affecting various apps, services, and games, examples include The Bank of Scotland, Mcdonalds, Fortnite, Docker, Vercel, Snapchat, Coinbase, and many more.

What seemed as a promising day ended up as a day of sending outage memes on slack and not being able to merge our code to production.

But why did AWS crash? and what should this outage serve as? 

---

### What Caused it?

According to AWS's [service health page](https://health.aws.amazon.com/health/status), a DNS resolution error was the culprit behind the internet crashing into oblivion.

>  We have identified a potential root cause for error rates for the DynamoDB APIs in the US-EAST-1 Region. Based on our investigation, the issue appears to be related to DNS resolution of the DynamoDB API endpoint in US-EAST-1

For you non-tech folks, allow me to explain:
- AWS's oldest server is in North Virginia, and is referred to as `US-EAST-1`.
- `DynamoDB` is a service offered by amazong where data is stored, and used by many customers of AWS.
- `Domain Name Service`, or `DNS` for short, is like a table, which takes the url that you type. for example `www.google.com` and translates it to an ip address `142.250.201.14` and is how your machine finds the website it wants to visit.

> You can try this yourself by typing `nslookup` then any url in your `cmd` or `zsh`


So some error that occured at US-EAST-1, could not let systems that use DyanmoDB to find the ip address, so instead of your machine reaching the website, it would get an error like: `Could not resolve host: dynamodb.us-east-1.amazonaws.com`

And many of Amazon's tools, including their own website, use DyanmoDB, so their request ended up not reaching, leading to services crashing.

Docker's package registry was down, vercel's deployment went offline, and many other services went down. The lucky people were the ones whose companies use google cloud and microsoft azure.


---
### What Does This Tell Us?

The most obvious observation is comapnies depend on AWS (and in general) way too much, one outage was enough to take down most of services we use. You know what they say about putting your eggs in one basket.

Services must have a business continuity plan should anything happen to the infrastructure they use.

Moving forward, l
---
### Lesson from Today

{{< typeit 
  lifeLike=true
>}}
The Cloud is just someone else's computer, and it too can crash.
{{< /typeit >}}


---
### Sources
- https://en.wikipedia.org/wiki/Enshittification
- https://health.aws.amazon.com/health/status
- https://www.dockerstatus.com/
- https://www.aljazeera.com/news/2025/10/20/amazon-cloud-problems-spur-outage-of-global-websites-and-apps