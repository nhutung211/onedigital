---
title: Multiparty Toolkit is here and why it’s awesome!
description: The Vonage Multiparty Toolkit is here! Here are some advantages,
  code samples, demo application and other reasons to give it a try.
author: dwanehemmings
published: true
published_at: 2021-09-08T17:56:10.173Z
updated_at: 2021-09-08T17:56:10.475Z
category: announcement
tags:
  - JavaScript
  - video-api
  - multiparty
comments: true
spotlight: false
redirect: ""
canonical: ""
outdated: false
replacement_url: ""
---
# Multiparty?

Let’s start by defining what Multiparty means. This is when a video call has multiple participants that are both publishing their audio and video streams while simultaneously subscribing to everyone else’s streams.

Previously, it was quite common to have teams of people in the same room and then get on a video call with a team in another room.

![Graphic depicting 2 groups of people passing information back and forth via 2 streams](/content/blog/multiparty-toolkit-is-here-and-why-it’s-awesome/2teams-2streams.jpg "2 teams 2 streams")

As you may have experienced yourself lately, things are shifting towards individuals calling in from different locations.

![Graphic depicting 6 individuals passing information back and forth via 36 streams](/content/blog/multiparty-toolkit-is-here-and-why-it’s-awesome/6people-36streams.jpg "6 people 36 streams")

As you can see from the image above, it can quickly become a complex challenge to keep up with all the connections from the participants.

This is where the [Multiparty Toolkit](https://tokbox.com/developer/multiparty/) comes in. Maybe you are new to developing applications that integrate video or a seasoned developer that wants to focus on other things. The Multiparty Toolkit helps remove the complexity PLUS optimizes for quality, CPU usage, and layout! That’s why it’s awesome!

Here is the Multiparty Toolkit used in a vanilla JavaScript project [Glitch project](https://glitch.com/edit/#!/remix/multiparty-tookit-demo?path=README.md%3A1%3A0) you can view. Just input your API Key and Secret in the .env file and you will have your own working example. This is a bare-bones implementation to highlight the Multiparty Toolkit.

# Removing complexity

See the comparison below of the starter code needed to create a Video Chat.

**Vonage Video API JavaScript Client SDK**

```javascript
const session = OT.initSession(this.apiKey, this.roomId); // Init session
session.on('sessionConnected', ...); // Handle session connected events 
session.on('sessionDisconnected', ...); // Handle session end
session.on('streamCreated', ...); // Subscribe to newly published streams
session.on('streamDestroyed', ...); // Clean up on stream end
session.on('connectionCreated', ...); // Handle connection events (join)
session.on('connectionDestroyed', ...); // Handle disconnect events (leave)

// Build your own UI / Layout
// Active Speaker Detection
// Video / Audio Optimizations
const pub = OT.initPublisher(targetElement, options, (err) => console.error(err)); // Create a publisher
session.publish(pub, undefined, err => { // Try to publish media
 if (err) {
   reject(err);
 } else {
   resolve();
 }
});

```

Vonage Multiparty Toolkit

```javascript
const room = new Room({ apiKey, sessionId, token, roomContainer: 'roomContainer’ });

room.join();

```