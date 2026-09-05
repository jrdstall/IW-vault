---
id: ART-A01
type: artifact
title: deliverable.md for UOW-A01
created: '2026-09-05T23:42:51.725588+00:00'
domain: artifacts
tags:
- artifact
state: active
last_touched: '2026-09-05T23:42:51.851525+00:00'
author:
  kind: human
  courier: web-ui
  requested_model: null
  declared_model: null
file_name: deliverable.md
path: work/UOW-A01/deliverable.md
unit: UOW-A01
edges:
- from: ART-A01
  to: UOW-A01
  relation: produced_by
  created: '2026-09-05T23:42:51.725588+00:00'
  author:
    kind: human
    courier: web-ui
    requested_model: null
    declared_model: null
  confidence: 1.0
  note: deliverable.md
---
# Prior-Art & Patent Landscape Survey

## Executive Summary
The Smart Cycling Helmet concept overlaps heavily with shipping commercial products. **Livall (BH60SE, BH51M)** and **Lumos (Ultra/Firefly)** already combine integrated front/rear LEDs, ambient-light auto-activation, and accelerometer-triggered brake flashing. **Classon** attempted the "senses cars" feature specifically via rear radar/camera + blind-spot LEDs, but stalled after a beta program — a signal that this sub-feature is the hard part. The two details in your idea that aren't well-covered anywhere: (1) manual side buttons with **tactile position feedback** (you can feel/see if a light is on/off without looking at an app), and (2) a **big, rarely-charged battery** as an explicit design goal rather than a daily-charge afterthought. Recommendation: don't build from scratch — remix an open-source DIY lighting base and bolt on the tactile-switch UX, and treat car-detection as a stretch goal using a cheap Doppler radar module rather than camera/AI.

## Detailed Analysis & Findings

### Closest Prior Art

1. **LIVALL BH60SE / BH51M** — [livall.com](https://livall.com/products/bh60se-neo-smart-helmet)
   - No Integrated front light, rear brake-warning LED strip, and turn signals (triggered via handlebar remote).
   - Has speakers - but this is dumb.  if there is wind noise, you couldn't hear anyways.
   - "Automatic sensor lighting" on BH51M — ambient light sensor turns lights on/off.
   - Magnetic charging cradle, non-removable battery, Bluetooth speaker, fall detection + SOS.

2. **Lumos Ultra / Firefly** — [ridelumos.com](https://ridelumos.com/products/lumos-ultra)
   - 30 front white LEDs, 64 rear red LEDs, up to 284 lumens.
   - includes turn signals, which is overkill
   - Automatic brake lights via accelerometer detecting rapid deceleration (requires optional remote/accessory to enable).
   - Magnetic dock + Qi wireless charging cradle.

3. **Classon Smart Helmet** — [Bikerumor](https://bikerumor.com/will-classon-hi-tech-helmet-yet/), [New Atlas](https://newatlas.com/bicycles/classon-bicycle-helmet-beta/)
   - Rear-facing camera + detection algorithm for blind-spot vehicle warning, lighting an LED in the visor.
   - Gesture-controlled turn signals (arm extension) and accelerometer-based automatic brake light.
   - Kickstarter-funded, reached beta testers (~$399 target retail) — no evidence of sustained mass-market availability, suggesting the camera/AI blind-spot detection was hard to productionize cheaply.

4. **UNIT 1 AURA** — [unit1gear.com](https://www.unit1gear.com/products/aura-mips)
   - E-bike certified helmet with integrated lights and turn signals, MIPS protection.

5. **Open-source DIY base projects:**
   - **Hackaday "Automatic Bike Lighting System"** — [hackaday.io/project/8472](https://hackaday.io/project/8472-automatic-bike-lighting-system) — uses a TMG3993 ambient light sensor + BLE to auto-activate lights in low light. Directly reusable for your headlight auto-off logic.
   - **Instructables "Open Source DIY Automatic Bike Tail Light 2.0"** — [instructables.com](https://www.instructables.com/Open-Source-Light-Sensor-Kit-20/) — OPT101P photodiode with a supercap to prevent flicker under trees/bridges; open Gerbers + BOM under CC-BY-SA.

### Similarities to Your Concept
- Front headlight + rear taillight built into the helmet shell: **Livall, Lumos, UNIT1** all do this.
- Ambient light sensor auto-off for the headlight: **Livall BH51M**, and both DIY projects.
- "Senses cars, blinks lights" behavior: **Classon** is the direct analog (radar/camera → LED response), though it reacts with blind-spot warning LEDs rather than blinking the head/tail lights themselves.
- Dock-and-charge big battery: **Livall/Lumos magnetic cradle charging** — pattern already standardized in the category.

### Key Differences / Open Ground
- **Tactile manual switches**: Every commercial competitor found uses app/remote/touch controls for on/off state, with LED or app indication of status — not a physical toggle whose *position* itself is the on/off indicator. This is a genuine, unclaimed UX niche (think a rocker or slide switch you can feel through a glove, no app needed).
- **Battery philosophy**: Competitors optimize for slim/light builds with frequent charging; explicitly designing for a large-capacity pack and long charge intervals is a legitimate, distinct trade-off (heavier helmet, less charging hassle) not marketed as a headline feature elsewhere.
- **Car-detection via cheap Doppler radar vs. camera/AI**: Classon used a camera + vision algorithm (compute-heavy, likely a factor in its stalled rollout). A cheap Doppler radar module (e.g., HB100/CDM324, ~$3–8) pointed rearward could achieve simple "vehicle approaching" blink-alerting far more cheaply than Classon's approach, and hasn't shown up in any helmet product found in this search.

### Patent/IP Note
No formal patent search was run (that's a bigger, separate effort); this was a maker/product landscape scan as scoped. If you get serious about the radar-detection feature specifically, worth a follow-up search on Classon's own patent filings (they did draft blind-spot detection IP — see USPTO ref found: [Patent 8,552,848 "Combined blind spot detection and rear crossing path collision warning"](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/8552848), though this appears to be an automotive-context filing, not confirmed as Classon's own).

## Recommendations & Next Steps
- **Novelty Score: 2** — Very similar existing products (Livall, Lumos) cover the core mechanism (integrated lights + ambient sensing + motion-triggered brake flash + dock charging) almost feature-for-feature. Not a 1 only because no single product bundles *all* your elements (esp. tactile switches + oversized battery) together.
- **Feasibility Score: 4** — Every sub-component is proven and buildable: ambient light sensors, accelerometer-triggered brake logic, and magnetic dock charging are all well-documented in open-source projects with BOMs/Gerbers available. Radar-based car detection is the one part with real prior difficulty (Classon's struggles), so treat it as a stretch goal, not a v1 requirement.
- **Recommendation: Adapt/Remix, don't build from zero.**
  1. Start from the Hackaday/Instructables open-source ambient-light auto-tail-light circuit as your lighting core (saves the sensor + driver design work).
  2. Differentiate with a genuinely tactile mechanical switch (a real SPDT toggle/slide switch, not a capacitive button) — this is your actual novel angle and costs nothing extra in complexity.
  3. Size the battery deliberately larger than competitors (they optimize for weight; you're optimizing for charge-interval) — easy differentiation, no engineering risk.
  4. Defer the "senses cars" feature to a v2 experiment using a cheap Doppler radar module rather than a camera — much lower complexity than Classon's approach, and worth a dedicated feasibility unit of work if you want to pursue it.
