---
title: "Launch"
date: 2020-10-18T13:31:43-07:00
draft: true
description : "US nation wide rollout cost benchmark"
tags : [ "v0", "launch", "MVP"] 
---

# MOM!!! Netflix is buffering again...

Recently everyday access to broadband has come into direct focus in the United States. This has been an onging discussion. With [false information](https://arstechnica.com/tech-policy/2020/04/att-gave-fcc-false-broadband-coverage-data-in-parts-of-20-states/) in in the Form 477 data through to projects like Google Fiber motivating communities to ask the question. Why can't we get acess to reliable, affordable high speed internet.

Enter COVID-19... In a complete shift of the business pschy work from home is now the norm. Everyone is fluent in atleast two video platforms and reliant on their devices to stay connected to their team. Big tech has told workers to [stay home till 2021](https://www.washingtonpost.com/technology/2020/05/18/facebook-google-work-from-home/), with many other industries and companies also taking similar steps.

There are many barriers in place for communities to be able to start a discussion on how they might build their own network.

It goes something like this: You either end up with a [raging success](https://www.vice.com/en_us/article/ezpk77/chattanooga-gigabit-fiber-network) or a [burning tire mound](http://www.cambridgeday.com/2020/06/05/failures-of-city-owned-internet-elsewhere-show-municipal-broadband-wont-work-in-cambridge/)...

But what is the fulcrum point that can tip a project?

The consenus is that it is the community engagement.

How can you increase community engagement and make a realistic cost estimate in a expedient, transparent and digestable way?

This is the question which has lead to the development of a collaboration between [broadband.cat](broadband.cat) and [unfolded.ai](unfolded.ai).


## Broadband.cat

Is the first opensource opendata software that lets communities quickly estimate the amount of potenital construction to build a broadband network.

Starting with a quick [city wide analysis](http://broadband.cat/westdesmoines.html) of the most recent Google Fiber initative in West Des Moines, IA. But uniquely scalling to be able to asses [whole states](http://broadband.cat/mississippi.html), with the goal of covering the whole Unites States and maybe the world!

You can access the code and run the project [here](https://github.com/fhk/tabby_cat).

## Unfolded.ai

The scale of global ride sharing lead the team at unfolded.ai to rethink what visualization, analytics and decision making meant. Built on the core opensource technologies:

- H3
- deck.gl
- kepler.gl

The platform brings a workflow and unification of large scale visualization of planetary data sets. What was previously not even contemplatable is now interactive and dyamic in the browser.

## The Challenge

It is not possible to quickly asses the cost of deploying a broadband network and it shouldn't be. No one size fits all. There are many nuanced choices, whom to connect, when to connect them, how to raise financing and the list goes on.

But it is possible to get access to data from [Open Street Map](https://www.openstreetmap.org/), [Open Addresses](https://openaddresses.io/), and [Microsoft buildings](https://www.microsoft.com/en-us/maps/building-footprints). But what use is the data if you cannot view it. Further it is a long way from a [OSP network design](https://www.thefoa.org/tech/ref/OSP/design.html).

So why not use these as input into a alogrithm that connects every address location to every other address?

This is what the [tabby cat](https://github.com/fhk/tabby_cat) project is for. But! It still produces Geographic Information System (GIS) output. This is not accessible by everyone.

Further, it is hard to combine it with other data sets!

Enter hexagons and the unfolded.ai platform.

Collaborating it quickly became clear that many insights could be unlocked. How does the density affect the pontential service areas? What is the ideal service percentage coverage. How much installation is required to serve a subset? Can a whole state be analyzed? Are all questoins that could be explored by simply interacting with parameters in the browser.

Further once a region has been analyzed it can be enriched with other data, saved, shared and used to communicate with all stakeholders. Ranging from ISPs, residents, elected officials, utilties, engineering firms, component manufacturers/suppliers and software vendors.

With this solution communities can now answer where and when they want a broadband network. Aswell as begin the converstaion of cost.

Take a look at the accessible data sample from our US National data product.

- 1KM Hex [here](https://studio.unfolded.ai/public/db786871-7e13-4eb1-81f5-643c56331719)
- Street segement hex [here](https://studio.unfolded.ai/public/8dd95cde-9941-4e3a-9853-0ef1f41611b0)

You can sign up for unfloded too [here](https://studio.unfolded.ai).

Send us a [MEOW!](mailto:f.kauker@gmail.com)
