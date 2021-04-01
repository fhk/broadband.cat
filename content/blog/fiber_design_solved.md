---
title: "Fiber design solved"
date: 2021-04-01T00:00:00-00:01
draft: true
description : "Announcement: Optimal solution found to FTTx network design"
tags : [ "solver", "network", "model"] 
---

# Background

Over the last ten years or more there has been much research into creating models and solvers to create solutions to telecommunication network design problems. However, more generally these models face a key limitation. The solutions can only be as good as the data that is used as input. Further due to the method in which these models are constructed using MILP or Hueristics they tend to hand wave and simplify certain aspects. Therefore till now no general model, framework or software can generate the optimal network for a given set of cables and components. Our solution demonstrates that by using a unique combination of technology we are able to return solutions which are provably optimal with respect to both cost and network topology.

# Problem Defenition

In general a modeling approach defines variables such as nodes and arcs where by a solution must find some subset and combination cofiguation to meet the design topology requirements. A model topoly can be a tree, star or ring and in general it is coputationaly expensive to create all levels of a network, both in the creaton of the model and finding a feasible and close to optimal solution. Further user workflows dictate the parts of a network be adjusted manually. This then requires that the problem be decomposed.

With the new approach all of these are no longer required.

# Solution

As we have seen in [Australia](https://itwire.com/telecoms-and-nbn/coalition-s-mtm-was-a-colossal-mistake,-says-nbn-co-s-first-ceo-quigley.html) and now the [United States](https://www.attpublicpolicy.com/wireless/defining-broadband-for-the-21st-century/) we don't actually need fiber optic networks. Why fix what's not broken. Once examined it is clear that we dont need to design any new network at all. Thus the solution is to just enjoy what we have.

# Impact 

This unique innovation is backed by the evidence in the [FCC maps](https://arstechnica.com/tech-policy/2021/03/fcc-wants-to-hear-from-americans-whove-been-ignored-by-broadband-industry/). Why would you map something that you don't need?

Starting today we don't need to design any FTTx networks!

Below is the map of the solution for new network that needs to be built!

{{< map "../../optimal.html" >}}
