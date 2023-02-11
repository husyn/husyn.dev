---
layout: post
author: husyn
title:  "Is Cloud Expensive?"
categories: [ youtube, cloud, aws ]
image: assets/images/is-cloud-expensive.png
tags: []
---

The Cloud (Computing) is one of the latest trends in Software industry. Well yes it's not so latest as AWS was launched in mid 2000s and since then has become a monster of its own. There was a famous iPhone commercial [There's an app for that][iphone-commercial]. And now we can say that for any use-case there's a "[Service for that!][aws-services]" AWS is the Cloud services provider which has the majority market cap in this space. Still it is small compared with the whole software industry. 

There are millions of applications of every kind which are not using any Cloud services. Specially in developing and under developed countries the hesitation to adopt cloud is because of it's cost. These markets being so cost sensitive don't consider the total cost of ownership concept, heavily marketed by cloud vendors of all types. I've tried to remove this misconception and came up with 10 reasons of my own on why cloud is cheap.

## Utility Pricing

Same like we have billing for our house utilities, cloud services are charged on usage. If you don't use any services then don't have to pay anything.

## Free Tier

When we sign-up for a new AWS account, it comes with lot of free stuff. Some of these free tier services are for 12 months and some others are forever free (again based on usage). Get the details of all such services [here][aws-free-services].

## Student Program / AWS Education

If you're student then access AWS (limited) services for free via [AWS Educate][aws-educate] program. One must have active ".edu" email address. I received $100+ in credits when I was a student and learned a lot with those.
 

## Startup Program / AWS Activate

AWS specially love startups, not only they might be next Netflix app but it's all free promotion and adoption of AWS. A startup can get up to $100,000 in AWS credits. More details [here][aws-startup].
 

## Reserve Instances

If the application is compute intensive or just require stable EC2 instances then [Reserving instances][aws-ri] for 1 or 3 years is a good idea to save some bucks. It is up to 72% cheaper then on-demand (utility) price. 

## Savings Plan

[Savings plan][savings-plan] is similar to Reserved Instances where the purchase is not based on server per year but $ per hour.

## Spot Instances

The magic behind the AWS on-demand capacity is _Redundancy_! But it also means that resource utilization is not optimal most of the time. This extra capacity is available to the consumers via [SPOT Instances][spot-instances].

## AWS Lightsail

Not every application is using Microservices Architecture. In fact majority of the web is working on PHP language and 35% is just [WordPress][wordpress-statistics]. To setup such server should not take few clicks and few minutes. That's what LightSail does! It has lot of templates to create servers with a fixed pricing model. LightSail is perfect entry point to the cloud for lot of users.

## Economy of Scale

This point applies for someone who is thinking long-term. As your cloud usage grows, the cost doesn't spikes up linearly. It goes down actually. The higher the AWS bill, the more discount you'll get. 

## Commitment Free

This is my favorite point and consideration with the cloud. There are just no commitments at all and anyone can mix and match any services with any provider. One can stop any service and not have to worry about the bills from that point onwards.

### YouTube Video

I also happen to make a video on the topic in case if anyone wants to hear all of my love for AWS! If you've made it so far then here's the [slides][slides] I used in the video for you.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xUC8jkVuhwA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[iphone-commercial]: https://www.youtube.com/watch?v=szrsfeyLzyg
[aws-services]: https://aws.amazon.com/products/
[aws-free-services]: https://aws.amazon.com/free/
[aws-educate]: https://aws.amazon.com/education/
[aws-startup]: https://aws.amazon.com/activate/
[aws-ri]: https://aws.amazon.com/ec2/pricing/reserved-instances/
[savings-plan]: https://aws.amazon.com/savingsplans/
[spot-instances]: https://aws.amazon.com/ec2/spot/
[aws-lightsail]: https://aws.amazon.com/lightsail/
[wordpress-statistics]: https://hostingtribunal.com/blog/wordpress-statistics/
[slides]: https://husyn.dev/assets/pdf/AllAboutCloud-Cost.pdf
