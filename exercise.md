---
layout: ex
title: Google Design Exercise
permalink: /exercise/
---

## Introduction

The goal of the Wait Staff Reviews design exercise was to design an experience where diners can submit positive comments and constructive suggestions for the wait staff, and servers can use this feedback to both improve and help to secure new employment.
This exercise was interesting to me because it meant I could consider multiple user perspectives, multiple environments and multiple contexts. It also felt like a fun problem to tackle :)

## Identifying users

Design starts with the people I am designing for: the user. I try to immerse myself in their lives and come to deeply understand their needs. I identified three key users from the exercise instructions:

1. **Diners** - diners can submit positive comments and constructive suggestions (reviews) for servers
2. **Servers** - servers can view reviews for self improvement and job hunting
3. **Hiring managers** - hiring managers can view server information and reviews in the hiring process

## Research

I wanted to uncover some facts about diners, servers and hiring managers. The Bureau of Labor Statistics [estimates](https://www.bls.gov/oes/current/oes353031.htm) **nearly 2.6 million waiters and waitress** employed in the United States (2016). That’s a decent-sized market of servers.

A restaurant [customer survey analysis](http://www.expressdissertation.com/document/Statistics-analysis.pdf) reveals, "**customer perception of employee service is most important factor impacting their satisfaction**.” This implies the importance of hiring managers selecting servers that deliver customer satisfaction.

A Yelp user [posted the question](https://www.yelp.com/topic/los-angeles-whats-defines-a-good-waiter-waitress-to-you), "What defines a good waiter or waitress?" A selection from over a dozen respondents shows diners care about:

- Prioritizes patron happiness/delight
- Friendliness, personal connection, special attention
- Instinctive timing, attentive but not bothersome
- Knows the menu and what to recommend
- Remembers orders, not forgetful

With more time and resources, I would dive much deeper into research. First, I would visit servers in their environment. Interviewing them would let me learn more about their wants and needs. Second, I would interview hiring managers and dig into what they look for in prospective servers. Last, I would learn more about the diner review/survey experience. This is a key first step in a product focused on review content.

## Assumptions

Now that I’ve identified the users and learned a little more about them in my research, I made some assumptions about them which sets some constraints around the product. In the real world, these assumptions can be tested early on with the people we’re designing for. For this exercise, I made these assumptions:

- Diners care about reviewing a server
- Diners will see a call to action and respond
- Diners have a mobile device with them
- Diners will stop to write a review after a dining experience
- Servers that care about their career likely work at higher-end restaurants, etc.
- Servers want to deliver an outstanding experience and improve their service skills
- Servers are willing to share some level of their evaluations with prospective employers (hiring managers)
- Hiring managers value server work history and reviews
- Hiring managers will use server reviews/profiles as a hiring tool

## Ideation
With a baseline of knowledge about the users and some constraints uncovered through assumptions, I start jotting down thoughts and questions. I think about each user and where they are in their life in light of this product. I generate as many ideas as possible, attempting to “get them out” through writing and sketches.

{: .wider .mt5}
[![Photos of the work in progress](/assets/img/exercise/proof.jpg "Photos of the work in progress")](/assets/img/exercise/proof.jpg)

## Product Focus
I chose to focus my work primarily on the server. My secondary focus was the diner, but I also considered the needs of hiring managers and how a server might anticipate them. I wrote these stories to help guide my thinking toward product features.

### The Dining Experience
Shane and his girlfriend just finished an outstanding dining experience. He is willing to review the server afterwards. What's the easiest route for Shane to write a review? I considered a few things:

1. Shane sees a call-to-action and QR code on his receipt and scans the QR code, which opens his mobile web browser and brings him to the review experience. The problem with this solution is Shane may not understand the interaction and probably doesn't have an app that reads and interprets QR codes.

2. Shane sees a call-to-action and URL on his receipt, types it in to his mobile web browser which brings him to the review experience. The problem with this solution is links can be hard to read and often frustrating to type.

3. The best solution I identified is for Shane to see a texting call-to-action on his receipt. Shane texts a short code "Maren" to 51515 and instantly receives a text back including a link to review Maren. He taps the link to open his mobile web browser which brings him to the review experience. This solution is best because it leverages texting (a common, everyday experience), requires only a few letters of typing and tapping a link. It requires the least amount of effort from Shane and is also the speediest route to the review experience.

Based on this story, we can identify the following tasks a diner can perform using their mobile device:

- Text a short code
- Receive a text with a link to write a review
- Write a review

### The Server Experience

Maren works all evening delivering outstanding service to dozens of guests. She focused her night on delighting patrons by serving them the best dining experience at a well-known, dimly-lit resort restaurant.

On her way home from work, she gets a notification on her Pixel from ServeBetter, an app she's been using the last few months. The notification tells her she has a new review from Shane G. She taps the notification to open the app and read the review details. It shows a 4.5 rating and mentions her delicious wine recommendation. She favorites the review to remember it later.

Maren thinks about the conversation she had last week with a hiring manager at a new resort restaurant. One of the things he was looking for was someone knowledgeable of wine. Maren decides to view and edit her ServeBetter profile to highlight her affinity for wine. Then she taps to her favorites to view Shane's review again. She shares it with the new resort restaurant hiring manager via email.

Based on this story, we can identify the following tasks a server can perform using the ServeBetter app:

- View a list of reviews
- View the details of a review
- Favorite or share a review
- View and edit a profile
- Share a profile that includes a bio, a high-level view of reviews, and work history


## User Flows
Based on these stories and tasks, I can start to play around with how I’ll organize key screens in an intuitive experience. I considered mobile navigation patterns when thinking of how to  connect these screens.

{: .mt4}
### Diner User Flow

{: .wider}
[![Diner User Flow](/assets/img/exercise/flow-diner.jpg "Diner Flow")](/assets/img/exercise/flow-diner.jpg)

{: .mt4}
### Server User Flow

{: .wider}
[![Server User Flow](/assets/img/exercise/flow-server.jpg "Server Flow")](/assets/img/exercise/flow-server.jpg)

## Wireframes
Based on this flow, I can start thoughtfully organizing elements on each screen to guide users to each task they need to complete. I further considered mobile UI patterns, transitions between screens and additional opportunities like gestures, voice interaction, etc.

{: .mt4}
### Diner Wireframes

{: .wider}
[![Diner Wireframes](/assets/img/exercise/wireframes-diner.jpg "Diner Wireframes")](/assets/img/exercise/wireframes-diner.jpg)

{: .mt6}
### Server Wireframes

{: .wider}
[![Server Wireframes](/assets/img/exercise/wireframes-server-01.jpg "Server Wireframes")](/assets/img/exercise/wireframes-server-01.jpg)

{: .wider}
[![Server Wireframes](/assets/img/exercise/wireframes-server-02.jpg "Server Wireframes")](/assets/img/exercise/wireframes-server-02.jpg)

{: .wider}
[![Server Wireframes](/assets/img/exercise/wireframes-server-03.jpg "Server Wireframes")](/assets/img/exercise/wireframes-server-03.jpg)

## Visual Design
I chose to focus on visual design of the native mobile app for servers since it's at the core of the product. I used Material Design UI patterns because it leaves little guesswork for Android users. I changed up the typography to insert some creativity and set it apart from other apps. A bottom navigation approach clarifies the organization of the app and keeps each key part a tap (sometimes 2) away.

{: .wider .mt4}
[![Visual Design](/assets/img/exercise/visual-01.jpg "Visual Design")](/assets/img/exercise/visual-01.jpg)

{: .wider}
[![Visual Design](/assets/img/exercise/visual-02.jpg "Visual Design")](/assets/img/exercise/visual-02.jpg)

{: .wider}
[![Visual Design](/assets/img/exercise/visual-03.jpg "Visual Design")](/assets/img/exercise/visual-03.jpg)

## 2.0
With more time, I would have focused on three things:

1. The diner’s experience. There is an opportunity to delight the diner with the review experience and make it memorable, increasing the likelihood they engage in the experience again.

2. Creative visual design. I would have looked for opportunities to leverage artwork or illustrations to add some additional personality to the product.

3. The hiring manager experience. I would have explored the best way for a hiring manager to receive a shared review or profile. I would have also illustrated the conversation between a hiring manager and server, including this product and the role it plays there.

Some bigger thinking uncovers even more ideas on where I could take the product:

- What if a server came home from a busy night at work and asked Google Home to read it’s latest ServeBetter reviews?

- What if hiring managers could open a web app and search for all servers in a region with a rating greater than 4.0 and 5 years experience?

- What if servers could customize the review questions a diner sees? This would allow servers to identify a weakness, take a new approach to improve it and gather data on how they are improving.

- What if diners could complete a survey completely from their messages app via an automated conversation/bot?

- What if restaurants rewarded diners for writing reviews for their servers? This benefits the diner (cost savings), the server (more learning, denser data set of track record through higher review count) and the restaurant (better service through stronger wait staff)


## Conclusion
This exercise allowed me to explore problem solving for a unique collection of users, express my design process and thinking, and have some fun dreaming in the process. Thanks for reading!

{: .mt5}
[&larr; nathanroberts.com](/)
