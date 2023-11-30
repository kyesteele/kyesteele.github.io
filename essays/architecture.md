---
layout: essay
type: essay
title: "Architecture Blueprints for Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2023-11-29
published: true
labels:
  - Design Patterns
  - Software Engineering
  - Architecture & Construction
---

<img width="400px" class="rounded float-start pe-4" src="https://raw.githubusercontent.com/kyesteele/kyesteele.github.io/main/architecture.jpg">

When constructing and designing new buildings, architects use blueprints as a guide and way to map everything out. In software engineering, design patterns act like virtual blueprints. They are structured approaches to solving common problems and challenges in software design. This allows developers to follow tried and true methods when creating robust and scalable systems. Although blueprints and design patterns are not the same, both provide a foundation and strong starting point as well as an efficient approach to each problem.

## Versatility with Reusability

In the construction of buildings, there are many reusable tools involved throughout the process. For instance, having a hammer that can be reused for a variety of tasks. For instance, it can be reused many times to put in a nail or pull one out. In my software engineering endeavors, one of the common design patterns I have utilized is known as the prototype pattern. The prototype pattern essentially allows objects to “inherit” properties and methods from other ones. For my use case, I created a car prototype for a web application that allowed me to create different instances of cars, with different makes, models, form factors, etc.

## Real-Time Adaptation

In the architectural realm, the observer pattern aligns with the collaborative and dynamic nature of construction projects. In my software development journey, I implemented the Observer pattern in a Meteor application to define how data is published to the client in real-time. Much like the various teams on a construction site need to be informed promptly of changes, the observer pattern ensured that any alterations made by one user were immediately reflected for all collaborators. In the previously mentioned app, I needed to ensure that server-side changes are observed and reflected on the client-side promptly.

## Consistency in Global Accessibility

In the construction of buildings, there are instances where a single, globally accessible tool is essential, like an on-site crane to move a variety of heavy materials. Similarly, in software engineering, the Singleton pattern plays a crucial role. In a recent project, I employed the Singleton pattern to create a centralized manager handling the authorization of users for a web application. This singleton ensured that user authorizations were consistent across the entire application. It also offered a single point of access for checking authorization status of a user with an included method. In whole, this is similar to the role of a centralized tool in construction that uniformly addresses diverse material-moving needs.

## Blueprints to Navigate Complexity

In the construction of both physical and digital realms, architects and software engineers alike rely on structured plans to navigate complexity. Design patterns, similarly to blueprints, offer a systematic approach in software engineering. In a variety of applications, I’ve personally found myself using the prototype, observer, and singleton design patterns. Together, these patterns enable me to streamline processes and ensure efficiency, much like blueprints used in the complex construction of buildings.
