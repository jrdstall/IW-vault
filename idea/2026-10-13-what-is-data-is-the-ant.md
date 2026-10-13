---
id: IDEA-A46
type: idea
title: What is "data" is the ant?
created: '2026-10-13T18:40:03.387303+00:00'
domain: c2
tags:
- c2
- enterpriseorchestration
- aerospace
state: active
last_touched: '2026-10-13T18:40:03.584215+00:00'
author:
  kind: human
  courier: triage-surface
  requested_model: null
  declared_model: null
worth_to_me: medium
worth_to_others: low
---
What if the data is the ant?

First - thoughts on enterprise orchestration

I was involved in several efforts that built layers on top of collection systems and intel systems and tried to orchestrate across collectors or systems or what have you to achieve things like persistent surveillance, etc.  

Common Challenges arose:  Who owns it (enterprise orchestration) in a platform-centric world iwth sparse actors and resources?  Exquisite systems are harder to integrate because they have so many special constraints and rules and things that are hard to abstract away.  Then compound this with the speed of battle is increasing, and things like kill chains need immediate real-time effects and integrations, making them further hard to build.  then we have disparate users and needs trying to use the same system for vastly different things. Then, humans using the system are each only capably of ingesting and understanding so much at a given time to make decisions.  then we have the mass proliferation of resources.  this problem just keeps getting worse. 

**Question 1: Can enterprise orchestration work? Is it the right way to get to the intended result, the right application of the right idea to result in what we really need?**

Existing efforts have often focused on infrastructure things - like a common language (UCI) or how tools can interoperate (OMS).  Others have built single complex planners (M2C2), or layered architectures.  

What about ants?  Simple decentralized actions...

little ants running around independently decorating entiites  
little ants with virtual perceptions of reality
little ants acting with simple logic, with loose coordination
little ants imparting knowledge on an entity (update perceived states).  supporting actors impart supporting needs - like update revisit quality when it knows a confusing event is coming.  

if ants are platforms, can they act indendent of specific needs?  

distributed copies of a search area won't be much of a problem, just means potential over-collection.  However, distributed copies of an entity could be a large problem as old states will get correlated to new observations and end up with multiple conflicting object states...

What if one actor owns the entity state and tasks are what is pushed around in the simple ant comms and negotiated?  

**What if the data is the ant, not the platform or the actor or the effector?**
the entity of interest is the ant, it's trying to figure out with simple logic and simple loose comms who it is, what it is.  it "eats" observations, it "looks" for sensors and effectors to help it be able to consume more, etc.  the logic is centered around the entity, not the resource.

Notes: 
-find/search area task very different from track entity task, are we treating them the same?
- this world had users - direct or abstract, opportunity to sense, observations, virtual perceptions of reality, data products, estimations, entities of interest, space, non-interest entities...