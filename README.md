# Kenan Kaddoura

Full stack software engineer.  
I build production features at Diet Loop, and I previously led Sky Guards, a six person robotics team that shipped an autonomous drone detection swarm.

📍 Eastern Province, Saudi Arabia • ✉️ [kenangazwan@gmail.com](mailto:kenangazwan@gmail.com) • 💼 [LinkedIn](https://www.linkedin.com/in/kenan-kaddoura) • 📄 [Resume](https://drive.google.com/file/d/1Yn1vwnOAbtj5JoKnl4YfpWoFFxTq3v2A/view?usp=share_link)

---

## About

I like thinking in problems and solutions, not just code and features: shaping an idea, sketching user flows, prototyping, then building and refining it until it works for real users. The software, the domain, and the business all matter to me equally.

I prefer to build things that work, then make them better. Sometimes that is a full product from scratch; other times it is the one detail that changes the whole experience. Lately that has looked like shipping a dual app food delivery product to Google Play, building dashboards inside a startup design sprint, and leading a team of six engineers on an autonomous drone swarm with a custom ground control station.

I work across the stack, web, mobile, backend, UI and UX, because each layer tells part of the story, and I like that story to stay fast, simple, and meaningful.

---

## Selected Work

### Diet Loop, Food Subscription Ecosystem
**Full Stack Software Engineer, Dec 2025 to present**

A food subscription platform live on Google Play and the App Store, built across four codebases I work in day to day: Flutter for the user app, Kotlin for the restaurant app, Angular for the admin console, Node.js and MongoDB underneath.

#### User App (Flutter)
* OTP login and account management
* Multi restaurant browsing with weekly and monthly subscription plans
* Order tracking, plan renewal, and a calorie calculator

<p align="center">
  <img src="assets/user_app_screens.jpeg" alt="Diet Loop user app screens"/>
</p>

#### Restaurant App (Kotlin)
* Order management across ongoing, pickup, and past orders
* Sides and meal availability management
* Meals calendar for scheduling, with Firebase push notifications on new orders

<p align="center">
<img src="assets/restaurant_app_screens.jpeg" alt="Diet Loop restaurant app screens"/>
</p>

#### Admin App (Angular)
* Custom subscription builder: live Saudi phone validation, conflict checks against active plans, one form for duration, meals, snacks, and pricing
* Purchased subscription management with prefilled, editable customer SMS notifications
* Central control over restaurants, meal and snack plans, promo codes, payments, and orders across the platform

<p align="center">
  <img src="assets/admin_app_screens.png" alt="Diet Loop admin app screens"/>
</p>

### Barri Solutions, Orders Management Redesign
**Full Stack Software Engineer Intern, Jun 2025 to Aug 2025**

Order management was spread across four separate pages that mirrored the database rather than how dispatch actually worked: trucks, POD, invoices, and transfers, each its own screen. In a five day design sprint with the business team, we rebuilt it as one order centric view with tabbed sub actions, so every part of an order is now reachable in three clicks or fewer. I built the Angular frontend against a .NET and C# service layer and tuned the underlying queries so the live dashboards held sub second latency under real load.

<p align="center">
  <img src="assets/barri_app_screens.png" alt="Barri orders management redesign, unified dashboard and single order view"/>
</p>

### Sky Guards, Cooperative UAV Swarm
**Project & Software Lead, Aug 2025 to May 2026**

A senior capstone that grew into a six engineer team across four departments, which I recruited and led. The system is two drones that patrol a defined airspace and localize an intruding drone in real time. I built the Ground Control Station in Python and Flask (swarm control, live drone state, a return to home safety net under 15% battery), and worked with the team on a coverage model, the Shared Probability Grid Map, that lets the two drones split the airspace instead of duplicating each other's paths. We tested three routing strategies on top of it; inward spiral won on coverage and became the final system.

**Result:** 8,500 SAR total build, 5 minute deployment, 24 minute flight time, drone detection at 0.95 precision, 0.95 recall, 0.97 mAP@0.5.

<p align="center">
  <img src="assets/GCS%202.png" alt="Sky Guards Ground Control Station"/>
</p>
<p align="center">
  <img src="assets/SPGM%20Comparison%203%20Alogrithms.png" alt="Shared Probability Grid Map, routing algorithm comparison"/>
</p>

**▶️ [Watch a demo video](https://www.youtube.com/watch?v=5gTlGVEdDx0)**

<br>

<details>
<summary><b>📊 See the full project poster</b></summary>
<br>
<img src="assets/sky-guards-poster.png" alt="Sky Guards project poster" width="100%">
</details>

---

## Stack

| | |
|---|---|
| **Frontend** | React, Angular, TypeScript, Flutter and Dart, Kotlin, Tailwind CSS, Bootstrap |
| **Backend** | Node.js, Python (Flask), C# and .NET, REST APIs, MVC |
| **Data** | MongoDB, PostgreSQL, MySQL |
| **Tooling** | Git & GitHub, Bitrise, Docker, Figma, Design Sprints |

---

<sub>P.S. outside of client work I've been slowly picking up computer vision, mostly curiosity for now, not a pitch.</sub>
