# Kenan Kaddoura

Full stack software engineer (web and mobile) who also leads and builds robotics systems from zero.
Currently deepening computer vision and edge AI: building my own detector, tracker, and edge deployment pipeline. Open to full stack, computer vision, and edge AI roles.

📍 Eastern Province, Saudi Arabia • ✉️ [kenangazwan@gmail.com](mailto:kenangazwan@gmail.com) • 💼 [LinkedIn](#) • 📄 [Resume](docs/Kenan_Kaddoura_Resume.pdf)

---

## About

I own features end to end: UI, API, data model, and rollout, across Flutter, Kotlin, Angular, and Node.js.   
Outside client work I lead and build systems from zero, most recently a two drone autonomous swarm that detects and localizes hostile drones with onboard inference under 50 milliseconds.

Most of what I ship lives in private, company owned repositories, so this page works as a project brief instead of a repo list: real products, real screens, real numbers, in place of a stars and forks feed.

---

## Selected Work

### Diet Loop, Food Subscription Ecosystem
**Full Stack Software Engineer, Dec 2025 to present**   
Four surfaces, one product: User app (Flutter), Restaurant app (Kotlin), Admin platform (Angular), backend on Node.js and MongoDB. Live on Google Play and the App Store.

* Own 10+ production features end to end, such as: OTP auth, subscriptions, payments, plans, meal categories, orders, and scheduling.
* Built the admin subscription flow: live Saudi phone validation, conflict checks against active plans, one form resolving duration, meals, snacks, and pricing.
* Refactored REST endpoints to return purpose scoped response shapes instead of full model dumps, cutting payload size across all four clients.

#### User App (Flutter): 

<p align="center">
  <img src="assets/user_app_screens.jpeg" alt="Diet Loop user app screens"/>
</p>

#### Restaurant App (Kotlin): 

<p align="center">
<img src="assets/restaurant_app_screens.jpeg" alt="Diet Loop restaurant app screens"/>
</p>

#### Admin App (Angular):  

<p align="center">
  <img src="assets/admin_app_screens.png" alt="Diet Loop admin app screens"/>
</p>

### Barri Solutions, Orders Management Redesign
**Full Stack Software Engineer Intern, Jun 2025 to Aug 2025**   
Four separate pages, unified into one order centric workflow.

* Ran a five person Design Sprint with business stakeholders and prototyped in Figma.
* Consolidated trucks, POD, invoice, and transfer requests into a single Orders page with tabbed sub actions; every part of an order now reached in three clicks or fewer.
* Built the frontend in Angular (TypeScript, RxJS) against a .NET and C# service layer; optimized queries for sub second latency on real time dashboards.

<p align="center">
  <img src="assets/barri_app_screens.png" alt="Barri orders management redesign, unified dashboard and single order view"/>
</p>

### Sky Guards, Cooperative UAV Swarm
**Project & Software Lead, Aug 2025 to May 2026**   
Multidisciplinary senior capstone (EE, COE, ICS, SWE). Six engineers, one system: patrol, detect, and localize hostile drones.

* Led the team end to end: originated the concept, recruited six engineers across four departments, ran the meeting cadence, unblocked subteams.
* Built the Ground Control Station (Python, Flask): swarm control, live drone state, protection area definition, return to home under 15% battery.
* Designed the Shared Probability Grid Map with the team, then implemented and benchmarked three routing algorithms; inward spiral won on mean minimum coverage.
* Results: 8,500 SAR total build, 5 minute deployment, 24 minute flight, YOLO26s detection at 0.95 precision, 0.95 recall, 0.97 mAP@0.5.

<p align="center">
  <img src="assets/GCS%202.png" alt="Sky Guards Ground Control Station"/>
</p>
<p align="center">
  <img src="assets/SPGM%20Comparison%203%20Alogrithms.png" alt="Shared Probability Grid Map, routing algorithm comparison"/>
</p>
 
**▶️ [Watch A Demo Video](https://www.youtube.com/watch?v=5gTlGVEdDx0)**

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
| **Tooling** | Git and GitHub, Docker, Figma, Design Sprints |

---

## Now

Extending Sky Guards into a solo computer vision project. I build, train, and deploy the detector myself, add multi object tracking and monocular range estimation, generate synthetic training data in Unreal Engine to close the sim to real gap, then quantize and optimize for edge inference with ONNX and TensorRT. Repo and writeup land here as it ships.

---

## Get In Touch

✉️ [kenangazwan@gmail.com](mailto:kenangazwan@gmail.com)
💼 [LinkedIn](#)
📄 [Full project brief](docs/Kenan_Kaddoura_Brief_v2.pdf): screens, decisions, and numbers behind every project above.
📍 Eastern Province, Saudi Arabia, open to relocation
