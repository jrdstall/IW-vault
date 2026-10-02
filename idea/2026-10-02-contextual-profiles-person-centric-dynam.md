---
id: IDEA-A45
type: idea
title: 'Contextual Profiles: Person-Centric Dynamic Resource and Data Fabric'
created: '2026-10-02T23:55:21.794474+00:00'
domain: computing
tags:
- contextual-profiles
- smart-data
- ambient-computing
- iot
- c2
- privacy
state: active
last_touched: '2026-10-02T23:55:21.794474+00:00'
author:
  kind: human
  courier: triage-surface
  requested_model: null
  declared_model: null
worth_to_me: high
worth_to_others: high
edges:
- from: IDEA-A45
  to: FRI-A53
  relation: addresses
  created: '2026-10-02T23:55:21.794474+00:00'
  author:
    kind: human
    courier: triage-surface
    requested_model: null
    declared_model: null
  confidence: 1.0
  note: ''
- from: IDEA-A45
  to: FRI-A54
  relation: addresses
  created: '2026-10-02T23:55:21.794474+00:00'
  author:
    kind: human
    courier: triage-surface
    requested_model: null
    declared_model: null
  confidence: 1.0
  note: ''
- from: IDEA-A45
  to: FRI-A55
  relation: addresses
  created: '2026-10-02T23:55:21.794474+00:00'
  author:
    kind: human
    courier: triage-surface
    requested_model: null
    declared_model: null
  confidence: 1.0
  note: ''
- from: IDEA-A45
  to: FRI-A56
  relation: addresses
  created: '2026-10-02T23:55:21.794474+00:00'
  author:
    kind: human
    courier: triage-surface
    requested_model: null
    declared_model: null
  confidence: 1.0
  note: ''
- from: IDEA-A45
  to: FRI-A57
  relation: addresses
  created: '2026-10-02T23:55:21.794474+00:00'
  author:
    kind: human
    courier: triage-surface
    requested_model: null
    declared_model: null
  confidence: 1.0
  note: ''
- from: IDEA-A45
  to: FRI-A58
  relation: addresses
  created: '2026-10-02T23:55:21.794474+00:00'
  author:
    kind: human
    courier: triage-surface
    requested_model: null
    declared_model: null
  confidence: 1.0
  note: ''
- from: IDEA-A45
  to: FRI-A59
  relation: addresses
  created: '2026-10-02T23:55:21.794474+00:00'
  author:
    kind: human
    courier: triage-surface
    requested_model: null
    declared_model: null
  confidence: 1.0
  note: ''
---
# Contextual Profiles

## Basis Thnking that started this line of thought:

### Bluetooth pairing

- Why can't my bluetooth headset figure out what I want it to connect to based on context?  When I'm listening to streaming from my phone, and get in the car, the car bluetooth takes over.  When I open my tablet and get out my headphones to watch a movie, the headphones connect to the sleeping laptop, not the awake device i'm currently using.  Why are connections tied to devices first, then profiles, not profiles first then devices?

- What if it was less about devices, logins, pairing and connecting and more about experiences, locations and services?

PERSON + SERVICES / CONTENT + LOCATION + IO

I am a person, I have a device, 

 i want to access content and services (music, movies, podcasts, email, calendar, social media, shopping, maps, etc)

 I can be in my home, my car, a hotel room, outside, at work

 Each location has speakers, touchscreens, computers, and all kinds of networked devices in between.

 ### Example

 4 guys get into a car.  rather than the phone infotainment system or a single person's paired phone drives stuff, the car senses who is there, and downloads each user's profile and those profiles are visible on the car screen.  Rider 1 can pick his profile and his available content that fits the situation (playlists, podcasts, map locations, etc) are immediately available.  and not tied to an app, they are general data and info available to be used or rendered by the situation, not to be silo-ed by a specific app.   So, it's less about apps and more about content readily available to be used given the situation.  the people are identified by some "BioMarker"

 ### Paradigm shift

 The central idea should be a PERSON not a device, not an account, not an app.  

 the trouble with this is our current technology economy driven by profit centers around apps and proprietary content.  this is because that is how they make money.  if content were independent of apps, there are serveral problems, who would pay for the infrastructure and management of data and information that isn't tied to and cna be consumed by any service...

 ### More Questions

 - Does the app provider need to own the content?
 - Does the mapping app have to control or own the locations of interest of a person?
 - Does the video streaming app have to own the streamed ocntent?

 Currently: 

 Content, Info Data    <->   Apps/Services  <-> Devices <->  Person

 Can we alter these relationships?  Do apps have to be "tied to" specific devces?  Does the person have to own a device to be able to use it?   Why can't apps be transient?  Can settings and content and things be more tied to the person and not the app/device pair?

 Does every device have to be self-contained?  Could we decompose it into components - screens (I/O), compute, speakers, memory, buttons that can be just resources that can be used dynamically?  Like for example, could there be simple screens in the kitchen above the cook surface and you just push content to it (like the recipe you're cooking).  Or if you move around the house, the speakers in the room can be found and used to play content?  all this without having to for example have an app and a full OS on the screen in the kitchen and messaging beteen apps, but just there is an IO device and i dynamically discover it and push my current context to it?  Or without having to explicitly pair speakers? etc.

 ### I don't like

 I dont like how content is tied to services.  
 
 I don't like how these amazing tools and technologies we have are dominated by apps that are focused on and designed to pull you in for the purpose of making money resulting in super silo'ed data, compute, etc.

 I don't like how devices all have to have a full OS with all the features and cybersecurity and attack surfaces, when many of them just receive streamed content.  We built the whole way things work based on the ancient way of having devices with OSs....

 ### Use case

 I'm sitting in my living room right now.  In this room or nearby i have a Smart TV, a Roku Device, a laptop, a tablet, a phone, a thermostat,  a pellet grill (bluetooth and wifi enabled), speakers connected to a Sonos system.  All these are designed and act very independently, mostly accessed by apps, and mostly designed to stream or facilitate consumption of media for entertainment.  and  as such, it is designed to suck you in (e.g. continual scrolling) rather than be healthy.  But as i sit here, is the only things i really want to do is consume content?  With all this IO and compute at my fingertips, what if I could checkin on my kids, grandkids out of state, what trails i could go offroading on tomorrow in the time i have available on my calendar, find a trail partner to go offroading with, make a shopping list for tomorrow's grocery run, call someone on their birthday, practice songs i'm singing in my choir, review my spanish vocabulary, watch a specific game, kickoff an Innovator's workspace task, check headlines relevant to me.  etc.  i have around me cameras, screens, speakers, a tablet i can draw on, a keyboard i can type in, but all of these are independent.  What if I could draw some notes on the tablet and they beocme part of my profile and available however i need them without having to save to specific shared folder then go to a specific app on another device and pull it up...  there are so many examples of how much better it could be.

### Counter Example

Apps like youtube started as a way to provide a marketplace for content providers and content seekers to find each other (although now it is all about making money - companies and influencers dominate)...  but what would change about this model if the nature of apps changed?  would we not have "apps" like youtube and instead have content services that just serve content, not packaged in an app?  

### Personal compute

we built a world of compute around a specific device and app driven use case, but could we envision something else where your virtual life is based on your profile, and has access to data and services you need, and everything is built around that as the centeral concept and what you do with that data and services...

### I don't know what this is yet, but...

it feels like we have something like roaming and dynamic contextual profiles - contextual because the profile serves up the type of data / info relevant to what you are doing, where you are and what compute and IO resources are available.  then you have a matrixed set of HW and SW resources, a fabric that weaves HW, SW, content, IO based on your proximity, provide, and activity at the time

You then have content services, and IO services, and AI to understand what you're doing and helping you find and work.

### From Formgiving book

1.  the WWW was the first platform that collected info and subjected it to algorithms
2.  social media was the second platform subjecting relationships to algorithms
3.  IoT will be the third platform when physical objects and things will be subject to algorithms

I add 4.  AI will allow a revolution in the algorithmic side to use this data at a speed and scale never thought possible

### NOT APPS AND DEVICES

All this opportunity and potential is best not organized and managed in apps and devices in the current way we do things!!!!

Apps organize things and align revenue streams with how the current tech stack was built, but it is so limiting to what we could do in the next few years!!!

### More questioning:

What is our digatal life now?  
what could it be?
What should it be?

Why is ENTERTAINMENT such a huge driver of how thing are being and will be built?   - this is less so with AI as we are now building tools people use to do real work, but entertainment is still a key driver...

Profit-driven approaches to HW/SW/Content means stove pipes / silos
Open standards driven approaches (think OMS/UCI) can be slow, burdensome, inefficient, -> motivation dies

what if it wasn't just about connections, but data?  we spend so much time moving data around, organizging it, etc.  now AI needs data and tools to access the data, could we build "databases" in real-time, in a "universal" data format that is self-describing and built based on contextual awareness of what's happening at the time?  maybe this isn't a database so much as a contextual profile?  some of this idea is getting the right data and behaviors and services to the right compute and IO resources...

### Brainstorming

I walk into a room like my living room with the various devices and IO resources.  something in the room detects i am there, and a discovery allows these to become usable by me (obviously some permission layer would need to exist, but for this case, I own the house and they belong to the house so that should just work for me).  do the devices figure out who i am and configure themselves or make themselves available to me?  or does my phone detect them and push configurations to them?  or do we need a "phone" to be the driver?  what is the key organizing element that brings the actions on my behalf together?  is it decentralized and collective across the resources or so i need a single device to be the master controller of sorts?


### Example

I have used Google Maps for years and didn't see a reason why a car company would ever need to build their own.  Then i got my Mini Cooper and used the map, and it integrates the cameras all over the vehicle into the map directions displays and shows a camera view overlayed with arrows on where to turn.  Google maps on the phone doens't know about all these cameras, but the car is specifically designed with the map to know about them.  could we get to a time when you don't have to pre-know stuff like that and can take advantage of whatever resources exist dynamically with AI figuring out how to bring the data and info and service together to meeet a dynamic need?

### Scriptures

There are things that act, and things that are acted upon.  i still think this applies to compute, data and AI

### Green Angle

We have so much duplication - wasting so much resources - like i have 1 work laptop, one personal laptop, 1 work tablet, one personal tablet, one work phone, one personal phone, one workstation for the tinkerspace to do 3d modeling and such, 3 computer monitors across those, 5 TVs, wife's laptop and phone and tablet, kids workstation and each has a school computer, each has a phone.  all those take resources to build and power and network.  but they all have the smae stuff, compute, memory, disk, etc. and rarely do i use all at once.  how do we make it more green by reusing this stuff contextually.  i can pull my my work profile or my personal profile on the same hardware instead of having different hardware. etc.....

### Getting rid of apps

we need to consdier how to separate the functions of doing things (one example: like separating the viewing video from the video itself).  this didn't work in the past (remember Windows Media Player)?  now apps each tie this all together

### App examples

If i want to see where my son is, i have to open the Bouncie app to see where the car is.  If i want to see where my wife is I have to open Google maps (she shares location with me).  If i want to see how long my morning bike ride is, i have to open the strava app.  each of these has a map display and shows location info, but each is silo-ed.  what if i could just ask where JJ is, that is data i have access to, and it is displayed on a "common" map, then i ask where deleen is and it's put on the same map.  or i just ask - show my today's geo data, and it shows the live location of my family, where my bike ride was, where i drove, where they drove, etc... 

### the internet

the internet is a network of networks that allows any node to talk to any other node. Data is the opposite, it is all silo-ed by app and hidden behind apps.  could data become more standalone or independent of apps ?  what if data not apps were the driver?

### Personal Feelings

I feel disconnected from my perosnal profile and my data spread across the web.  It paints a picture of me as a person that is not really generated by me or controlled by me, but made by algorithms watching my behavior under certain circumstances, and going through algorithms that are trying to learn how to best profit from me vs having my best interests at heart.  I also can't see thse profiles.  They own so many parts of my profile.  they have defined me according to their own measuring sticks.  why can't i control it?  largely now  because many of these services are free to me, and because they are free i don't get much of a say in how they are setup or use me.

## What is all this

I'm trying to envision a new way to think about data, compute, ownership, business, and living.  Overlay all this with AI - where does it fit?  where should it fit?  what does it see? what should it see?  how does / should it interact with me and my data and compute resources, and other people and their ecosystems?   If data is not tied to platforms and AI is in the cloud, how do you manage me and my context and my data and my AI?

# Second Layer of thinking: Contextual Profiles for Warfighters

## my background thinking on this

### the entities 

we have an ecosystem of data, processing, visualization, sensors, effectors, people, roles, decisions, policies, ROE, compute, IO, needs, tasks, situational awareness.

we still need to get rid of "platforms" and OS and system and INTs and intel type thinking and move to needs, questions, decisions, awareness, actions

### idea 

can data be "smart"?  meaning it's wrapped with logic that acts for itself to find out where it's needed and can be used insted of people finding it to use?  can it also have its own processing instructions bundled with it, so you don't need a specific computer with a specific algorithm to process it, wherever it goes it can be processed?  

### once again, people

people still need to be the central focus.  not apps, not devices.  that person has things they do and therefore things that they care about that help them do what they do:  locations they care about, enemies they care about, objectives they have, leaders and subordinates, missions they are assigned to etc.  all this is part of their dynamic living contextual profile.  

We still have this paradigm today:

person <->  device <->  app <-> data

could it be?

person <->  { data <-> virtual resources }


the virtual resources might include compute, IO, connetivity, and the data you need is available when you need it.  no emails, file shares, messaging apps, logins, databases, etc.  when a person goes in a conf room, or a humvee, based on their profile, they get the data they need, the ability to act on that data (services, algorithms, etc) without having to pre-configure, pre-install, pre-load...  smart data, contextual profiles, generic compute and IO that can act however needed dynamically

### Dissemination

ABI and OBP are all about the tasking and data processing to discover entities and gather good intel on them.  what are we doing to advance the ability to disseminate and use this data?  

With AI, AI is just another role - like a human that also needs access to data relevant to their role and job without having to find it, ask for it etc.  

