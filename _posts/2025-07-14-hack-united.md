---
title: "Hack United Hackaton Expirience"
date: 2025-07-14
permalink: /posts/hack-united-expirience
tags:
  - Dev Events
  - Hackaton
  - Projects
---

This summer I got a great opportunity to test my skills and build an idea from zero to a proof of concept. I took part in the 5th edition of the  Hack United hackaton. This is an annual online hackaton organized by developers for developers. It lasted for two days full of excitement, ideas flow and coding, coding, coding.

I decided to take on this challenge with my friend Nikita Bystrika. He is currently a webdesign and development student. We decided to split our work so that he is responsible for design and I was responsible for the actual coding. 

All the coordination of the event was made via a Discord server. The organizators were from the USA so imagine our faces when we had to watch the welcome session at 2 a.m. During the live stream we got the topic of the whole hackaton which was entertainment.  Usually I like to solve the problems that can actually help people, so this was something new for me. 

Before we went to sleep we decided to brainstorm the ideas a bit and decide on something for out project. We went through different entertainment sectors like movies, music, games. But eventually we stopped on the crossroads of bringing people together and audio. 

Our idea was to create a social media platform with audio content called "Echoes" where people shouldn't think of how they look or what they wear. The only things that matter are their voices and ideas. It would be a platform for sharing life stories, anecdotes, podcasts, breating practices, stand ups and so much more - the sky is the limit. The main advantage would be that a user wouldn't need to actively look at their phones. They could go for a walk and turn it on like for example Spotify.

Here are a couple more features that are meant to boost the engagement with the platform:
1. Personalized feed with an integrated player
2. Echo button to amplify posts that resonate
3. Filters and editing of the audios to make it stand out
4. Everyday challenges for the community
5. Cut out and share parts of audios for the viral effect

When we marked out the potential concept and features of our application we started building it. Nikita was busy with making the design of the application while I was setting up the backend of our project. 

I decided to go with a simple React webapplication and Vite to be able to deploy it and test fast. As for the backend I used Cloud Firestore. It was my first time using it. During my studies I have already worked with NoSQL databases, but it was the first time working with this service. Apparently it was quite easy to get around with it and start building fast, which was crucial in our situation. 

There is one more thing that I've done for the first time in my life. It was working with audio on the web. To be fair this was a pleasent expirience. I found out about the way to record, play, change and store the audio on web. It was really interesting to make the voice effects like robotic and reverb. I've done it by changing the nature of the sound and its parameters. I've also found out about WaveSurfer.js library that helped me visualize the audio tracks as I wanted. 

The scope of this project proved ambitious for the hackaton, so we tried to deliver the idea in the best manner. Our team created a documentation with the dexcribed features and the prototype of the features. As for the PoC we delivered a fully working home page with the ability to record, customize and post an audio as well as to see the recommendstions feed.

![Echoes project]({{ site.baseurl }}/images/posts/echoes.png)
*The home page of Echoes project*

This was my first hackaton and I'm proud of the accomplishments. There were definitely some mistakes made in terms of planning and focus on the right thing. Next time we should concentrate more on the actual PoC rsther than on the idea itself and choose the smaller scope for the application. Anyway it was really fun to see how two people can build an idea from zero into someting feasible just in two days. I enjoyed this expirience and would definitely try it again.
