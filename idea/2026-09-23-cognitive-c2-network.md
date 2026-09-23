---
id: IDEA-A41
type: idea
title: Cognitive c2 network
created: '2026-09-23T21:18:25.666182+00:00'
domain: C2
tags:
- C2
- AI
state: active
last_touched: '2026-09-23T21:19:15.766962+00:00'
author:
  kind: human
  courier: web-ui
  requested_model: null
  declared_model: null
rendered_file: drop/cognitive-c2-network.md
worth_to_me: high
worth_to_others: high
---
In C2, we have sensors, effectors, decision makers, process, ROE, command authority, etc.  

Right now the cognitive "fabric" is mostly humans with data flowing into them and commands and decisions flowing out.  

At the observe and orient layers, you have perception, decision, learning, prediction. At the observe and act you have fusion, correlation, and processes or algorithms that feed up. Under this, you have a physical layer with compute, storage, networking, and under that you have the sensors and effectors.

C2 happens in the combinatorial space, where people use COAs and TTPs as baseline, and then their own creativity and experience to decide what to do and how to do it to achieve mission objectives.

How might we make AI part of this? What is the harness or set of constructs and capabilities that fit in the right places between these layers to provide meaningful support to C2. Basically a **COGNITION NETWORK** with the following:
- A way to share information between humans and agents (any combination of these) at the cognition level.
- Need a way to form teams dynamically.
- Need a way so you just don't have a set of prompt engineers, but real cognitive teams.
- Need a shared world model.

This is like a collaborative cognitive architecture composed of humans and AI agents with support services and command languages and services:
- It allows humans and AI to work at the cognitive layer thinking in terms of tasks, needs, intent — it focuses human cognitive load and preserves initiative and acts within ROE. AI helps filter, rank, explain, summarize, find uncertainty, test hypothesis, detect anomalies, suggest, recommend, connect observations, remember things, provide alternate plans, etc. Humans and AI together orient, sensemake, judge, decide, act.
- At the info layer, you have fusion, correlation, reports, analysis, planning, scheduling. These are more deterministic things called by the layer above.
- At the data or command layer you have command and control. This is where plans are turned into commands. Also the cognitive layer can skip the info layer and directly interact with the command layer.
- Then you have the sensor and effector layer which sit above the real world.

AI starts with helping in orientation, but then it becomes a collaborator, helping humans reason and coordinate and act.  

Cognition needs to be distributed. Humans lead and own. AI is delegated scoped functions.

In the end, it's an ecosystem, not just a harness, where you have the necessary services that allow you to work like a team, interact with each other, share data, request help, delegate and assign work, etc. — shared team awareness and C2.

*Example*: Satellites with this layer can report "I found a threat", others can say "I can maneuver" or "I can image it" or "I can do an electronic survey" or "I can take it out". Sometimes you could what-if: "what if I maneuver". This goes back to the ants idea, where each acts independently with a simple set of logic resulting in bigger emergent behaviors.

### Open Questions:
1. How do you give a "license" to AI to only act within a certain set of bounds?
2. How do you work at a "language" level on a platform?
3. How do you keep enough context current and synchronized?

---
*Reference file: [cognitive-c2-network.md](drop/cognitive-c2-network.md)*