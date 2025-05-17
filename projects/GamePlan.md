---
layout: project
type: project
image: img/gameplan/gameplan-square.png
title: "GamePlan - Web App"
date: 2025
published: true
labels:
  - Next.js
  - PostgreSQL
  - Prisma
  - Vercel
summary: "A web app that enables UH Mānoa students to reserve volleyball or basketball courts."
---

<p align="center">
  <img src="img/gameplan/gameplan-full.png" alt="GamePlan Screenshot" width="80%">
</p>

## GamePlan - Web App

**Overview**  
GamePlan is a web app that allows students to reserve basketball and volleyball court space at the University of Hawaiʻi Warrior Recreation Center. The idea came from one of our group members who was frustrated with how hard it was to secure playing time during peak hours. GamePlan includes separate pages for basketball and volleyball games, live scores for today's matches, an all-days schedule, and user authentication (sign in/sign up).

The app was developed using **Next.js**, **React**, **PostgreSQL**, **Prisma**, and deployed via **Vercel**. Although not officially used by the Rec Center, it was built as a functional educational tool in ICS 314 (Spring 2025).



**Pages I Helped Build**
- Landing page (refined layout, style, and button logic)
- Volleyball schedule page
- Basketball schedule page
- Reservation form logic

## My Contribution

I focused primarily on the **backend/database integration** and the **deployment pipeline**:

- Wrote and tested the **Prisma schema** for reservations and users
- Built the **reservation submission flow** to store court info in the database
- Set up and maintained **Vercel deployment**, including environment configuration and build troubleshooting
- Updated the **Playwright tests** for the reservation workflow
- Assisted with landing page design, adding small UI/UX improvements for better user onboarding

## What I Learned

- How to configure and troubleshoot **PostgreSQL** database connections with Prisma and Vercel
- Learned the **limitations of Prisma**, especially when filtering or validating inputs
- Gained confidence with **CI/CD pipelines**, environmental variables, and deployment debugging
- Practiced **issue-driven project management**, helping break down tasks and coordinate with teammates
- Learned how small UI decisions (like button clarity or spacing) can affect a user’s first impression

## Source Code / Organization

- 🌐 [Deployed App on Vercel](https://gameplanz.vercel.app)  
- 💻 [Source Code on GitHub](https://github.com/TheC-es/GamePlan)  
- 📄 [Project Organization Page](https://thec-es.github.io/)
