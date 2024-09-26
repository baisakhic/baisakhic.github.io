---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<hr/>
{% include base_path %}

Unmanned Aerial Vehicles (UAV) are surging in popularity as a result of the versatility of their usage. The FAA estimates that millions of autonomous UAVs will soon take to the skies, performing various tasks, both individually and in groups. With a dense network of vehicles expected, dynamic planning based on real-time sensed data is of vital importance. The FAA has proposed UAS Traffic Management (UTM) as an overarching framework in order to ensure safe and secure mission planning which maintains equitable use of the National Airspace System (NAS). 

The UTM framework is a set of goals that would allow multiple UAV groups to safely take to the air. Agents would need to communicate with a variety of stakeholders in order to share state information for a coordinated task, either directly or via another UAS (Unmanned Aerial System). Thus, latency of channel or packet drop due to a lossy system are important concerns. Another challenge encountered in my research is that of limited communication range. UAVs are expected to be able to perform in remote, infrastructure-less locations and, in many cases, might not have access to high ranged transmitters. my research has been focused on mitigating these issues which arise in practical real world problems. To do this, I have selected an exemplar problem of plume wrapping to study effects of network latency on UAV coordination. I then developed an algorithm to guarantee bounded synchronization despite information loss and system failure, leading to agents exiting the group. I have also worked on adapting my initial assumptions of the plume shape and modified my algorithm to be able to surround plumes with some variety in its structure. I have further explored how coordination and formation may be maintained in a moving group of agents who must remain at relative distance to each other for communication.

The goal of my future research is to analyze the  requirements stated by the UTM framework and work towards integrating multi-UAV groups into the wider aerial ecosystem such that the vision of an unified airspace can be realized. In my proposed work, I wish to extend my previous research and investigate coordination in UAV groups which may split up and later rejoin the group. Finally, with multiple groups of UAVs flying through the air, collision-free trajectory planning is imperative. my future work also aims to propose strategies allowing disparate groups of UAVs to avoid each other in 3D environments. 
