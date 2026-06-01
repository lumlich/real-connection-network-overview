# Real Connection Network

**Real Connection Network (RCN)** is a digital product focused on local communities, real-world events and healthier online interaction.

The purpose of RCN is simple:

> Help people find others nearby, build communities around real interests and turn online coordination into real-life meetings.

Website: https://www.realconnectionnetwork.com  
Crunchbase: https://crunchbase.com/organization/real-connection-network  
Creator / product lead: [Lumír Lichý](https://www.linkedin.com/in/lumir-lichy-166342a)

This repository is a **public product and architecture overview** of Real Connection Network.

The production source code is intentionally kept private for security, privacy and product-protection reasons.

---

## Product idea

Most social platforms are optimized for attention, visibility and constant engagement.

Real Connection Network is designed around a different idea:

- fewer empty online interactions,
- more local relevance,
- more real-world meetings,
- calmer communication,
- stronger local communities,
- healthier online habits.

RCN is not meant to be another endless feed. It is meant to help people discover local communities, organize real-world activities and build trust over time.

---

## What RCN is built for

RCN helps users:

- discover local communities,
- join groups based on real interests,
- create and participate in community events,
- share posts and updates inside communities,
- coordinate real-life meetings,
- receive relevant notifications,
- interact in a calmer and more focused environment,
- build meaningful relationships with people nearby.

The product is especially focused on the bridge between **online coordination** and **offline community life**.

---

## Core product areas

### Local communities

Users can discover and join communities connected to interests, topics, activities and local areas.

Communities are intended to support real-world activity, not just online discussion.

### Community posts

Communities can publish posts, updates and discussions in a more focused environment than traditional social feeds.

The goal is to support useful communication without unnecessary noise.

### Real-world events

Communities can organize events connected to real places, dates and activities.

Events are an important part of the product because they move the platform from passive online interaction toward real participation.

### Attendance and check-in

RCN includes an event attendance flow designed around actual participation.

The organizer has control over attendance confirmation, including PIN-based check-in logic for real-world events.

This avoids treating every online RSVP as real participation.

### Location-aware discovery

RCN uses location-related logic to help people find nearby communities and events.

The product avoids requiring exact public addresses where they are not necessary. The goal is local relevance without unnecessary exposure of precise personal location.

### Hex-based map areas

One of the product ideas is to use map-based area logic instead of relying only on exact points or administrative borders.

Hex-style geographic areas can help represent approximate community coverage, local relevance and nearby discovery in a way that is more privacy-conscious and visually understandable.

This approach is useful because communities are often not defined by exact addresses. They are usually connected to neighborhoods, walking distance, local regions or practical meeting areas.

### Notifications

RCN includes notification flows for important community and event updates.

The notification concept is designed to support real participation without creating unnecessary distraction.

### Media and photos

The product is being developed with support for image uploads connected to posts, communities and public presentation.

Media handling requires practical limits, compression, retention rules and storage-efficient design.

### Safety, moderation and privacy

RCN is designed with attention to account safety, community trust, location privacy, access control and careful handling of user data.

Because the product works with real people, real communities and real places, safety and privacy are part of the product design rather than an afterthought.

---

## Product principles

Real Connection Network is built around these principles:

### Real-world connection first

Online tools should help people meet, build trust and do things together in real life.

### Local relevance

Communities and events should be connected to real places and nearby people.

### Calmer online environment

The product should avoid unnecessary noise, addictive interaction patterns and algorithmic pressure.

### Practical community tools

The platform should focus on useful features: communities, posts, events, attendance, notifications, media and moderation.

### Privacy-conscious location design

Location should support discovery and relevance without exposing more personal information than needed.

### Trust and safety

Community tools need clear permissions, access rules, moderation concepts and secure account flows.

---

## My role in the project

Real Connection Network is my own product.

My work on the project includes:

- product vision and positioning,
- feature planning and prioritization,
- community and event flow design,
- product copy and public communication,
- UX logic and user-flow decisions,
- backend architecture coordination,
- frontend behavior coordination,
- database and data-model decisions,
- API structure and endpoint planning,
- authentication and account-flow improvements,
- event attendance and PIN check-in logic,
- location and map-related product decisions,
- media and image-handling planning,
- notification-flow planning,
- privacy and security hardening,
- deployment and production-readiness planning,
- testing and quality control,
- documentation and public presentation.

The project combines product management, software delivery, architecture thinking, security awareness and hands-on technical work.

---

## Technology overview

The production implementation is private, but RCN is built as a modern web application with backend, frontend, database, media and deployment layers.

High-level technology areas include:

- Rust backend development,
- API design,
- PostgreSQL database,
- frontend web application,
- authentication and session handling,
- community and event data models,
- role-based access logic,
- event attendance and check-in logic,
- location-aware discovery,
- map and area selection logic,
- media upload planning,
- notification flows,
- Docker-based deployment,
- production infrastructure planning,
- security hardening,
- automated testing,
- iterative development workflow.

The product is not only a static website. It is a full application with user accounts, communities, events, permissions, notifications, media considerations and production deployment architecture.

---

## Architecture focus

RCN is developed with attention to:

- clear separation between frontend and backend responsibilities,
- structured API endpoints,
- database-backed community and event logic,
- organizer and participant roles,
- access control for community and event actions,
- secure handling of authentication flows,
- careful handling of location-related data,
- maintainable event lifecycle rules,
- scalable media handling,
- production deployment readiness,
- incremental improvement without unnecessary rewrites.

---

## Event model

Events are one of the most important product areas in RCN.

The event model includes concepts such as:

- community-based event creation,
- organizer role,
- participant RSVP,
- time-based event state,
- attendance visibility,
- PIN-based check-in,
- organizer-controlled confirmation,
- post-event archive logic,
- attendance summary,
- protection against unrealistic or late participation changes.

The goal is to make events useful for real-world communities, not just online declarations of interest.

---

## Community model

Communities are designed as local or interest-based groups where people can coordinate activities and communicate in a focused way.

Important community concepts include:

- membership,
- community posts,
- community events,
- local discovery,
- public presentation,
- moderation and ownership logic,
- location or area context,
- long-term community identity.

The community model is meant to support groups that already exist as well as people who want to create new local communities from scratch.

---

## Location and map concept

Location is important for RCN, but exact location is sensitive.

The product therefore focuses on practical local relevance rather than unnecessary precision.

Location-related ideas include:

- approximate home-place logic,
- nearby community discovery,
- map-based community areas,
- event location selection,
- avoiding unnecessary exposure of precise personal addresses,
- using geographic areas where exact points are not needed,
- making local discovery understandable to users.

The hex-based area concept is part of this thinking: it can help represent local zones in a clean, consistent and privacy-conscious way.

---

## Security and privacy approach

Because RCN works with users, communities, events and location-related information, security and privacy are central to the product.

Important principles include:

- keeping production source code private,
- avoiding public exposure of sensitive implementation details,
- minimizing personal data where possible,
- careful handling of user location information,
- secure authentication and password-reset flows,
- access control for community and event actions,
- organizer-only event management where appropriate,
- controlled media handling,
- production logging without unnecessary personal data,
- retention and deletion planning,
- gradual hardening before broader public rollout.

---

## Why the source code is private

This repository does not contain the production source code.

The source code is private because the product includes:

- authentication logic,
- user data handling,
- community and event permissions,
- location-related logic,
- deployment configuration,
- infrastructure details,
- security-sensitive workflows,
- product-specific implementation decisions.

This public repository provides a high-level overview of the product, architecture, technology choices and development direction without exposing sensitive implementation details.

---

## Current development focus

Current development focus includes:

- improving onboarding and public presentation,
- refining community discovery,
- improving event flows,
- strengthening safety and privacy,
- preparing image and media handling,
- improving deployment and production readiness,
- improving documentation,
- building a stronger public digital footprint for the project,
- preparing the product for broader real-user testing.

---

## Public presence

Main website:

https://www.realconnectionnetwork.com

Crunchbase:

https://crunchbase.com/organization/real-connection-network

GitHub profile:

https://github.com/lumlich

LinkedIn:

https://www.linkedin.com/in/lumir-lichy-166342a

This public overview helps connect the technical, product and public identity of Real Connection Network across the web.

---

## Professional context

Real Connection Network connects my long-term background in project, portfolio and operations management with hands-on digital product development.

The project involves:

- product thinking,
- prioritization,
- technical coordination,
- software architecture decisions,
- backend and frontend delivery,
- security and privacy work,
- deployment planning,
- public communication,
- iterative improvement,
- long-term product ownership.

It is a real product built to become useful, not a coding exercise.

---

## Contact

Lumír Lichý  
GitHub: https://github.com/lumlich  
LinkedIn: https://www.linkedin.com/in/lumir-lichy-166342a  
Crunchbase: https://crunchbase.com/organization/real-connection-network  
Website: https://www.realconnectionnetwork.com
