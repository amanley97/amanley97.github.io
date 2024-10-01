---
layout: post
title: How does OpenShift hold up?
date: 2024-09-30 4:59:00-0400
description: Utilizing the RedHat OpenShift platform as a newbie to cloud development.
tags: learning
categories: opinion-posts
giscus_comments: false
related_posts: false
toc:
  sidebar: left
thumbnail: assets/img/redhat/openshift.png
---

## Introduction

I recently had the opportunity to utilize RedHat's [OpenShift](https://www.redhat.com/en/technologies/cloud-computing/openshift) Cloud platform when I attended [Hack Midwest](https://hackmidwest.com/) - a 24-hour competition in which students and industry folks rapidly develop a project, demo it to judges, and attempt to win prizes! During the competition, my fellow teammate Momin and I decided to enter the [RedHat and Intel](https://hackmidwest.com/#prizes) AI challenge.

### What is RedHat's OpenShift Platform?

According to their website, they describe the platform as:
> Red Hat® OpenShift® is a trusted, comprehensive, and consistent platform to develop, modernize, and deploy applications at scale, including today’s AI-enabled apps. Innovate faster with a complete set of services for bringing apps to market on your choice of infrastructure.

As a beginner to all things in cloud development, the OpenShift platform simplifies the entire stack. From the inner loop for local testing, deploying model servers, and even deploying an outer loop server - they can do it all much simpler!

## OpenShift Features

### Project Management

The main menu of the OpenShift software. Allows for us to create the project, manage resources, create pipelines, and view the networking routes!

{% include figure.liquid loading="eager" path="assets/img/redhat/redhat-project.png" class="img-fluid rounded z-depth-1" %}

### Managing the Inner Loop

Projects utilize Git and an integrated IDE to allow for the project to easily be worked on! Openshift takes care of all the necessary setup, allowing the developer to just put together the application like running a Python Flask server!

{% include figure.liquid loading="eager" path="assets/img/redhat/redhat-inner-loop.png" class="img-fluid rounded z-depth-1" %}

### Running AI Model Servers

With the push to utilize AI, it becomes necessary to provide adequate resources to run them. OpenShift AI allows for models to be deployed from S3 Object Storage buckets and then deployed. The model servers are unaffected by the application server and can be easily utilized through a REST API! Integrated Intel AMX support makes the model servers' response time very snappy!

{% include figure.liquid loading="eager" path="assets/img/redhat/redhat-models.png" class="img-fluid rounded z-depth-1" %}

### Deploying to the Outer Loop

The OpenShift platform easily allows the developed application to be deployed from the inner loop. Once satisfied with their program, a pipeline can be created that generates a public url to your new cloud service!

{% include figure.liquid loading="eager" path="assets/img/redhat/redhat-deploy.png" class="img-fluid rounded z-depth-1" %}

## Final Thoughts

### Cons of Using OpenShift
As I mentioned earlier, I had zero initial knowledge on cloud architecture and development. I have never used Kubernetes and therefore there was a high learning curve to the platform.

My overall comment would be to suggest that RedHat works toward a unified documentation for the OpenShift platform. It's clear that the software itself is very well thought out and not too difficult to grasp, but better documentation would take it to the next level!

After discussions with the OpenShift representative [Daniel Schimpfoessl](https://sessionize.com/schimpfoessl/) at the event, he wanted to remind us that OpenShift is still in its infancy. The platform will only continue to improve.

### Pros of Using OpenShift
The project itself really are what shines for the platform, go check out my write-up on my projects page [here](/projects). What impressed me most was what my team and I were able to accomplish in 24 hours. To reiterate, I had no prior experience in cloud development and yet I was able to build and deploy a working application from scratch.

Overall, I was very pleased with the OpenShift platform. It has a wide range of features, most of which I barely even touched on. I am excited to see what the platform becomes in the future!

> Please note, I was in no way sponsored by RedHat or OpenShift. I simply had an impressive experience with software and wished to share. Thank you for reading!

## TL;DR
As a beginner to cloud development, I utilized RedHat's OpenShift platform during the Hack Midwest software competition and found it simplified many aspects of the cloud stack, from local testing to deploying AI model servers. 

While there was a steep learning curve, the platform's integration of tools made it easy to deploy a working application all within 24 hours. OpenShift's AI features and pipelines were especially impressive, though improved documentation would enhance the user experience. 

Despite its infancy, OpenShift shows promise for future developments and is definitely worth checking out!