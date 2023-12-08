---
categories: ["Computer Science", "Systems"]
date: 2023-12-08T00:15:00-05:00
description: "Why we need complicated systems for (seemingly) simple apps"
link: ""
tags: ["systems", "blockchain"]
title: "A case for distributed systems"
---

People often ask me what a "blockchain" is and what it's used for. And I find it very hard to explain the "why" without explaining "why" something like a simple internet search requires massive computing architectures behind the scenes.

## Why businesses distribute labor 🏭

Let’s start with an approachable example: One day, you got sick of cooking in your own kitchen and decided to eat out. 🚗💨

You pull up to your local restaurant and hurriedly take a seat so you can order your food. 🙋🧑‍🍳

After you (the client) put your request into the kitchen, the server comes back with a response and with the food. 🤤 🍽 💁🍗

As you happily eat your food, you notice that people start flooding into the restaurant. By the time you're finished, you realize that there’s a line in front of the door to get in. 🚪🚶🚶‍♂️🚶‍♀️

You try to get up and pay for your food before the rush, but there’s only one server in the restaurant, and it takes ages just to get their attention. 🙋 🏃💨 🥺

The solution to you is obvious: the restaurant needs to hire more servers (or more efficient servers)! After all, if you have more servers, you can handle more clients and requests. 🤤🤤🤤 💁🍗💁🍗💁🍗

## Back to the computer 🖥️

Hopefully I made the case why we need a similar system for computers. When you try to access a particular website, your computer or smartphone acts as a client, and sends a request to a server somewhere in the world. 📱➡️🌐➡️🖥️

Popular websites get tons of traffic - their servers become overloaded. Just like in a restaurant, you can start scaling up (buy supercomputers to process requests faster) or start scaling out (buy more computers to respond to different requests in parallel). 🌐↗️🖥️ 🌐➡️🖥️ 🌐↘️🖥️

## Complexity of distributed organizations and systems 🌍🌎🌏

Unfortunately, it turns out building large and distributed teams of people (or computers!) is challenging. As your crew grows in a business, you often need managers and standardized processes in order to keep things running smoothly. For instance, you don’t want multiple servers asking the same person for their orders or delivering orders to the wrong people. 😡🤬😠 🏃💨🏃💨

Similarly, distributed computers require managerial overhead to coordinate requests and responses. There have been lots of research around how computers can communicate with each other, achieve consensus, and even handle crashes or hackers [^1]. But that will be a topic for another blogpost. For now, we can appreciate that despite complicated algorithms running on [supercomputers under the sea](https://news.microsoft.com/source/features/sustainability/project-natick-underwater-datacenter/), a simple web search or playing our favorite videos remains to be a relatively ordinary task for most of us.

Discussions welcomed on [Github](https://github.com/andrewjeminchoi/ajchoi.xyz/issues/new/choose).

#### Notes

[^1]: [Paxos](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf) and [PBFT](http://pmg.csail.mit.edu/papers/osdi99.pdf) to name a few.
