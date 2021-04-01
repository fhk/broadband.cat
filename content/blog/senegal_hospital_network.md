---
title: "Senegal | Healthsites.io"
date: 2021-03-07T13:31:43-07:00
draft: true
description : "Create a potential cable route for medical care locations"
tags : [ "hospital", "broadband", "Senegal"] 
---

# Access to health care is a human right

Over the past year we have experienced a bifrication of peoples ability to access the medical system. This has been acute in the most vulnerable areas with over representation of COVID deaths nine times higher than in more affluent regions [1](https://www.ama-assn.org/delivering-care/health-equity/data-10-cities-show-covid-19-impact-based-poverty-race). Now this shows that even in developed countries what impact a struggling healthcare system can have. Emerging nations have it even tougher. From recent research published in Nature we can observe that many parts of the world are still more than a day away from a health/clinic/hospital location [2](https://www.nature.com/articles/s41591-020-1059-1).

Now what does this have to do with broadband?

Medical treatment and diseases prevention/containment is all about the data. The work by DiSARM creates risk maps for malaria which are then converted into plans to mitigate outbreaks. This is only possible via the ability to communicate. [3](https://www.blog.google/products/maps/how-maps-and-machine-learning-are-helping-eliminate-malaria/)

It follows that hospitals/clinics/health locatons require access to broadband.

What if we could build a network that connected the locations for medical treatment and also improved the access for communities at large. Given the estimate of ~4.66 Billion people on the internet there is still a far way to go. [4](https://www.statista.com/statistics/617136/digital-population-worldwide/) Further not all access is equivalent.

There are many moonshot projects that seek to deploy broadband networks and delivery in Africa. See [Wing](https://qz.com/1712200/google-wing-launching-us-drone-deliveries-with-fedex-walgreens/), [Loon](https://www.nytimes.com/2020/07/07/world/africa/google-loon-balloon-kenya.html), [connectivity](https://connectivity.fb.com/), and [airband](https://www.microsoft.com/en-us/corporate-responsibility/airband) just to mention a few.

But what is needed to plan a project?

# Base map data

1. Where should the network go?

One goal might be to connect all the hospitals to one another. This backbone network could be a building block which communities could leverage too. However, what data is there?

Senegal for example has great data in [healthsites.io](healthsites.io)

Combine this with the data from [OSM](https://download.geofabrik.de/africa/senegal-and-gambia.html) and also the [Facebook AI street data](https://github.com/facebookincubator/RapiD).

# Design

Finally run this through [tabby_cat](https://github.com/fhk/tabby_cat/) and you can visualize a network to connect all the medical locations.

Now the first thing that comes to mind is that there must be gaps in the data! The street network is not fully connected.

You can run the code [here](https://colab.research.google.com/drive/13Rwt8LsW0W5iu7zVey1Q_Rn0UtrnqnXP?usp=sharing)


{{< map "../../senegal.html" >}}