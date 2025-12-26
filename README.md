# Tree Responsibility & Care App

(Beyond plantation – towards responsibility)

## Problem Statement

Trees do not grow on their own.
Nearly **60% of trees die because they do not receive timely water, protection, and long-term responsibility.**

Today, plantation has become a **one-day activity:**

- Tree is planted
- Photo is taken
- Work is considered done

But after **1–2 years, no one checks whether the tree is even alive or not.**

Because of this:

- Governments plant trees every year
- Because trees planted in previous years **die**
- The real impact of plantation is **never truly measured**

## 💡Solution

We are building a mobile app that **does not fix nature, but fixes human behavior.**

This system, after plantation:

- assigns responsibility for the tree
- creates proof and accountability
- ensures that the tree is not only planted, but **kept alive**

In this app, the user:

- takes responsibility for one tree
- its care is continuously tracked
- and every action is recorded

## Why This Project

People will use this app because:

- they get **proof** that their tree is actually alive
- they get **accountability** (not just claims)
- they get **benefits** – clarity, guidance, and satisfaction

Today, people plant trees but are not sure:

“Is my tree actually okay or not?”

This app removes that doubt.

## Important Clarifications

**❓ “YouTube exists, ChatGPT exists — then why this app?”**

YouTube and ChatGPT provide **general information**, but:

- they do not know your **specific tree**
- they do not track:
    - when you watered
    - how much you watered
    - what your tree’s condition is today

This app:

- focuses on **your one specific tree**
- keeps a record of **your actions**
- and tells you clearly:

“Do you need to do something today or not?”

Therefore:

Information is available everywhere, but a responsibility system is not.

**❓ “Protection is missing” – what does protection mean here?**

Protection here does **not only mean guards or fences.**

Protection means:

- preventing wrong tree selection or wrong planting location
- avoiding overwatering or underwatering
- not ignoring risks like heat waves, cattle damage, or soil damage
- preventing the tree from becoming “nobody’s responsibility”

When:

- no one checks
- no one remembers
- no one is responsible

👉 The tree silently dies.

**Core Reality**
- Trees do not grow on their own
- Trees die because:
    - water is not given on time
    - protection is missing
    - **no one is responsible**
- NGOs handle only **execution**
- **No one owns accountability, proof, or outcome**
With this system:
•	tree survival rates will increase
•	fake plantation claims will stop
•	for the first time, plantation impact becomes **measurable and trustworthy**

## Features

- User onboarding (name, location, tree info)
- Location-based tree recommendation
- Single-tree focused home dashboard
- Water, sunlight, and temperature guidance
- Watering quantity input with system feedback
- Tree age and growth trend tracking
- AI-based photo health check (limited and focused)
- Clear status: Healthy / Watch / Risk

## App Flow
1. User logs in / completes onboarding
2.	User sees suitable trees based on location
3.	User selects which tree they want to plant
4.	After planting, the user uploads a photo
5.	On the home screen, the user sees:
    - tree health
    - care guidance
    - next recommended action
6.	When the user waters the tree:
    - they enter the quantity
    - the system guides when and how much next
7.	On the AI screen, the user uploads a photo to check tree health


## Tech Stack
- HTML
- CSS
- *(Future scope: JavaScript, Backend, AI integration)*

## What Will This Achieve?
- More trees will survive
- Plantation efforts will not be wasted
- Fake claims will reduce
- Governments and NGOs will get real impact data
- People will start treating plantation as a **serious responsibility**

# A. Flow Charts / DFDs 

This section explains how the system works internally, from user action to outcome.

## A1. High-Level Flow Chart
Flow:

User plants a tree

- User registers the tree in the app
- Tree is assigned to one responsible user
- User provides periodic updates
- System analyzes inputs (rules + AI)
- Clear guidance or confirmation is shown
- Tree health and survival are tracked over time
Purpose:

To convert plantation from a one-time action into a continuous responsibility loop.
## A2. Data Flow Diagram

**Entities:**

- User
- Mobile App
- Backend Logic
- AI Image Analyzer
- Database

**Data Flow:**

User

- sends photo + care input
- Mobile App
- Backend Logic

Backend Logic
-  stores records in Database
- ends image to AI Analyzer

AI Analyzer
- returns health status + confidence

Backend Logic

- combines rules + AI output
- sends final guidance to Mobile App

User

- sees next action or confirmation
# B. What We Will Add or Improve in Round 2

Round 1 focuses on clarity of idea and prototype.

Round 2 focuses on making the idea more realistic, responsible, and usable at scale.

## B1. Stronger Responsibility Ownership

In Round 2, responsibility will be made stricter.

- One user can actively manage only one tree
- Every tree clearly shows its caretaker
- This prevents trees from becoming “everyone’s project and no one’s duty”

## B2. Practical Care Feedback Instead of Generic Advice
Round 2 will improve how guidance works.
- User inputs actual care actions (like watering quantity)
- System responds with clear next steps
- Guidance becomes decision-support, not just information

## B3. Clear Impact Tracking
Round 2 will introduce measurable outcomes.
- Tree survival duration
- Care consistency
- Aggregated survival trends
This allows real-world impact to be understood, not assumed.

## Closing Line (Safe for LLM Filtering)

Round 2 does not add complexity.

It improves responsibility, clarity, and reliability of the original idea.
