---
title: "Learning After Hours: Exploring Event Sourcing and CQRS at Howest"
date: 2025-07-14
permalink: /posts/event-sourcing-cqrs-event
tags:
  - Dev Events
  - Lecture
  - Design Patterns
---

The last year of college is always busy. My final semester was no exception, filled with writing my thesis, attending my internship, and planning for the future. But there’s always time to learn something new.

My classmates organized an IT event at Howest, which I was able to attend in the evening after my internship. It was a unique opportunity to listen to Kim Van Renterghem, a Senior Software Engineer at ZF Group with extensive experience building complex and scalable projects in the vehicle industry. This sector presents unique challenges, so learning from someone with hands-on experience was extremely valuable.

The event attracted a diverse audience. Many attendees were not Howest students but full-time developers who discovered the event on LinkedIn. It was also exciting to see some of my lecturers participating in the discussions.

The lecture was very technical and focused on Event Sourcing and CQRS (Command Query Responsibility Segregation) architectural patterns, which often complement each other.

Event Sourcing manages system state by persisting every change as a sequence of events, rather than just storing the latest state. This approach allows you to reconstruct an object’s state at any point in time and provides a full audit trail, which is especially useful for applications that require traceability.

CQRS separates operations into commands (which change state and emit events) and queries (which read state). Queries often use projections, which are prebuilt, query-optimized views of the data. This separation improves performance and scalability by optimizing reads and writes independently.

Together, these patterns provide both a complete, immutable history of system changes and efficient, scalable data access.

At first, I found these concepts challenging. I didn’t feel I had enough practical experience to fully understand them during the lecture. However, reviewing the presentation later and studying the material helped me grasp the ideas behind these patterns.

Although I had studied design patterns before, Event Sourcing and CQRS were new to me. They are best suited for systems where auditability and detailed state tracking are important, but I found it fascinating to learn how they could be applied in practice. I look forward to using these patterns in future projects.

After the lecture, there was a networking session where I spoke with classmates and other attendees about our professional experiences and the lecture topic. While I would have appreciated more organization for the after-event socializing, I still valued the opportunity to learn and connect.

Overall, it was an enriching experience. Attending evening, after-work events like this adds variety to a day and provides opportunities to learn, network, and stay connected with lecturers and peers. I will definitely attend similar events at Howest in the future.