# Karl-Johan Bailey

**Software Engineer • AI Builder • Systems Engineer • Game & Streaming Technology**

I'm a **Swedish-Jamaican software engineer living in Trinidad & Tobago** who builds software because I genuinely enjoy understanding how things work.

I don't just code for work. **I code for fun.**

A lot of my projects start with a simple question:

> **Can I build this myself?**

That curiosity has taken me across cloud infrastructure, distributed systems, AI, monetization, payment systems, streaming, game engines, 3D applications, automation, and developer tooling.

I'm particularly interested in the parts of software where **performance, architecture, reliability, and scale actually matter.**

---

## What I Work On

My interests sit across several areas of software engineering:

* **Backend & distributed systems**
* **Cloud infrastructure**
* **AI/LLM systems**
* **Payments & monetization**
* **Streaming & real-time systems**
* **Game engines & gameplay architecture**
* **3D systems**
* **Data processing**
* **Developer tooling**
* **Automation**
* **Mobile and web applications**

I enjoy moving between high-level product engineering and lower-level systems work.

One project might involve designing an API and database architecture.

Another might involve figuring out how memory, networking, rendering, or entity systems should work underneath it.

---

# AI & Automation

My interest in AI goes beyond simply calling an LLM API.

I'm particularly interested in the engineering required to turn AI models into reliable software systems.

I've worked with and experimented with:

* LLM applications
* AI agents
* Tool calling
* Context and prompt architecture
* Retrieval pipelines
* Speech and transcription
* Real-time AI
* AI automation
* API orchestration
* Model integration
* Human-in-the-loop systems
* AI-powered educational applications

The interesting part to me isn't just the model.

It's everything around the model:

**data → context → orchestration → tools → infrastructure → application → user**

I'm interested in building AI systems that actually do useful work rather than simply demonstrating that an AI model can generate text.

---

# Monetization, Payments & Revenue Systems

One of my growing areas of interest is **software monetization**.

I've become particularly interested in the engineering problems behind how software actually makes money.

That includes:

* Payment systems
* Subscription billing
* Usage-based pricing
* Revenue tracking
* Billing reconciliation
* Payment failures
* Revenue leakage
* Entitlements
* Pricing infrastructure
* Advertising systems
* Ad mediation
* eCPM and LTV
* In-app purchases
* Subscription lifecycle management
* Payment provider integrations
* Revenue analytics

I'm interested in systems that sit between **software usage and money**.

For example, I've been experimenting with projects around problems such as detecting discrepancies between billing systems, identifying revenue leakage, reconciling Stripe transactions, and making monetization infrastructure easier for developers to reason about.

This area combines several things I enjoy:

**distributed systems + data + payments + APIs + business logic + reliability.**

---

# Streaming & Real-Time Systems

I've also spent time working with **streaming and real-time software**, including cloud-based streaming infrastructure.

That led me to become interested in problems involving:

* Real-time data
* Video streaming
* Low-latency systems
* Data pipelines
* Network communication
* Cloud infrastructure
* Distributed processing
* Event-driven architectures
* Media processing

I'm particularly interested in what happens when software has to process information continuously rather than simply handling one request at a time.

A normal application might look like:

```text
Request → Process → Response
```

Streaming systems are more like:

```text
Data → Data → Data → Data → Data
          ↓
       Processing
          ↓
     Continuous output
```

That difference creates a completely different class of engineering problems.

---

# Game Technology

Games are another major technical rabbit hole for me.

I build games, but I'm often more interested in **the technology underneath the game**.

I've worked with Unity and explored game-engine architecture, including:

* ECS-style architectures
* Entity/component systems
* Gameplay schedulers
* Event systems
* Physics
* Collision systems
* Movement systems
* Projectile systems
* AI behaviors
* Game state management
* Data-oriented design
* Mobile optimization
* Game analytics
* Monetization
* Rendering and 3D systems

I've also been exploring **C++ game-engine development** and lower-level gameplay architecture.

Games are interesting because they force many systems to operate simultaneously:

```text
Input
  ↓
Game Logic
  ↓
Physics
  ↓
AI
  ↓
Animation
  ↓
Rendering
  ↓
Audio
  ↓
Networking
```

And they often have to do all of this under strict performance constraints.

Sometimes I don't actually want to build the game.

**I want to understand the engine underneath it.**

---

# Computer Vision & Video Processing

I'm also interested in extracting structure from video and other unstructured data.

Some of the areas I'm exploring include:

* Object detection
* Image segmentation
* Foreground/background separation
* Depth estimation
* Video understanding
* Temporal tracking
* Scene reconstruction
* Video processing pipelines
* Spatial representations
* Data compression

One idea I'm particularly interested in is transforming video from simply being a sequence of pixels into a **structured representation of the scene**.

Instead of only storing:

```text
Frame → pixels
```

you can think about:

```text
Frame
 ├── Objects
 ├── Depth
 ├── Motion
 ├── Segmentation
 └── Scene relationships
```

This opens interesting questions around how video could be represented, compressed, searched, processed, and reconstructed.

---

# Systems & Infrastructure

I enjoy working on infrastructure because it exposes the engineering decisions underneath an application.

I've worked with technologies and architectures involving:

* AWS
* EC2
* ECS
* API Gateway
* CloudFront
* S3
* VPC networking
* Load balancers
* WAF
* SQS
* SNS
* PostgreSQL
* Docker
* CI/CD
* Distributed APIs
* Event-driven systems

I'm particularly interested in designing systems that can handle growth without simply throwing more infrastructure at the problem.

That means thinking about:

**latency, throughput, reliability, cost, concurrency, caching, storage, networking, and failure modes.**

---

# Data & Distributed Systems

I've been increasingly interested in the lower-level problems around data itself.

Some of the concepts I've been exploring include:

* Data deduplication
* Distributed storage
* Data sharding
* Memory management
* Caching
* Compression
* Network-based storage
* Data synchronization
* Shared data structures
* Distributed processing
* Fault tolerance

For example, I've explored ideas around identifying common data between multiple objects and storing shared portions once rather than repeatedly.

Another area I'm interested in is what happens when local memory and storage become constrained and a system needs to intelligently move or retrieve data from other nodes.

These aren't always straightforward production solutions.

Sometimes the interesting part is simply asking:

> **What if we designed the system differently?**

---

# Projects

I tend to maintain a collection of technical experiments rather than focusing on a single technology.

Some projects are designed to solve practical problems.

Others are deliberately experimental.

Some are built to understand a technology from the inside.

My projects have included work around:

* AI applications
* Monetization infrastructure
* Stripe/payment systems
* Revenue reconciliation
* Advertising systems
* Game engines
* Mobile games
* Streaming
* Video processing
* Cloud infrastructure
* Distributed systems
* Data structures
* 3D applications
* Developer tools
* Automation

I particularly enjoy projects where I can take an idea from:

**concept → architecture → implementation → measurement → optimization.**

---

# Writing About Technology

I also write about technology, software, and product decisions.

One of my articles is:

### **Usage-Based Pricing Is Killing More Consumer Apps Than It Helps**

I wrote about the trade-offs of usage-based pricing and how pricing models designed for infrastructure businesses can produce very different incentives and experiences when applied to consumer applications.

[Read on Medium](https://medium.com/startup-stash/usage-based-pricing-is-killing-more-consumer-apps-than-it-helps-a9b6e131f0eb)

I'm interested in writing about the technical and product problems I encounter while building, rather than simply writing about technologies because they're popular.

---

# How I Think About Software

I'm interested in the entire stack.

I can work at the application layer:

```text
UI
 ↓
API
 ↓
Database
```

But I also enjoy going deeper:

```text
Application
 ↓
Runtime
 ↓
Memory
 ↓
CPU
 ↓
Network
 ↓
Storage
```

And then back up again into:

```text
Infrastructure
 ↓
Product
 ↓
Users
 ↓
Revenue
```

That's one of the things I enjoy most about software engineering.

A technical decision at one layer can create consequences several layers away.

A database decision affects latency.

Latency affects user experience.

User experience affects retention.

Retention affects monetization.

Monetization affects infrastructure economics.

**Everything is connected.**

---

# Why I Build

I'm naturally curious about systems.

If I use something interesting, I often want to understand what happens underneath it.

If I see a limitation, I want to know whether there's another way to solve it.

If I find an interesting technical problem, I'll probably build a prototype just to see what happens.

That has led me to work across a pretty unusual range of technologies.

**AI.
Payments.
Streaming.
Cloud infrastructure.
Games.
3D.
Distributed systems.
Data.
Automation.**

The common thread isn't the industry.

It's the engineering problem.

---

# Building From Trinidad

I'm a **Swedish-Jamaican software engineer living in Trinidad & Tobago**, building for a global audience.

I'm interested in technology regardless of where the problem originates or where the solution eventually gets used.

I'm particularly interested in working with engineers who enjoy going deep into difficult technical problems and building systems that have to work in the real world.

---

# What's Next?

I'm continuing to explore the intersection of:

**AI × Systems × Monetization × Infrastructure × Games × Streaming × Data**

That means building more open-source projects, experimenting with new architectures, contributing to existing systems, and going deeper into C++, Go, cloud infrastructure, distributed systems, and AI.

I'm still trying to answer the same question I've always had:

> **How does this actually work underneath?**

And if I can't find a good answer,

**I'll probably build it myself.**

---

## Connect With Me

**X / Twitter:**
https://x.com/iamkarlbailey

**LinkedIn:**
https://www.linkedin.com/in/karl-johan-bailey-a96481201/

**GitHub:**
https://github.com/Karl-maker

**Writing:**
https://medium.com/startup-stash/usage-based-pricing-is-killing-more-consumer-apps-than-it-helps-a9b6e131f0eb

**Email:**
[karljohanbailey98@gmail.com](mailto:karljohanbailey98@gmail.com)

> **I build because I'm curious.
> I code because it's fun.
> And I want to understand how far I can take an idea.**
