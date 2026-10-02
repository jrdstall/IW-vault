---
id: FRI-A55
type: friction
title: Full OS bloat and attack surface on simple display and IO endpoints
created: '2026-10-02T23:55:21.794474+00:00'
domain: hardware
tags:
- os
- cybersecurity
- iot
- architecture
- complexity
state: active
last_touched: '2026-10-02T23:55:21.794474+00:00'
author:
  kind: human
  courier: triage-surface
  requested_model: null
  declared_model: null
stem: I don't like...
edges:
- from: FRI-A55
  to: IDEA-A45
  relation: derived_from
  created: '2026-10-02T23:55:21.794474+00:00'
  author:
    kind: human
    courier: triage-surface
    requested_model: null
    declared_model: null
  confidence: 1.0
  note: ''
---
I don't like how devices all have to run a full OS with all features, cybersecurity stack, and large attack surfaces, when many of them just receive streamed content or display simple info (like a recipe screen over a stove). We built the entire ecosystem on the ancient model of standalone devices with heavy local OSs rather than decomposed ambient IO resources.