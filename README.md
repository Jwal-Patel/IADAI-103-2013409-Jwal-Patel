# IADAI-103-2013409-Jwal-Patel

# Digital GreenWall – Gamified Eco‑Interaction Companion App

A user‑centred AI‑assisted prototype that reconnects urban youth with nature through daily eco‑challenges, AR experiences, team missions, and rewards. Designed as part of the **CRS: Artificial Intelligence** and **Course: Critical and Creative Thinking** summative assessment:  
**“From Empathy to Execution: Designing User‑Centered AI Digital Solutions Prototype”**.  

- **Scenario:** 1 – Digital GreenWall (GreenBloom Tech Pvt. Ltd.)  
- **Student:** <Your Jwal Patel>  
- **School:** <Your Udgam School For Children>
- **Working Prototype Link:** <Your(https://poodle-folder-98306157.figma.site)>  

---

## 1. Project overview

**Digital GreenWall** is a mobile‑first companion app for students aged 12–18 living in dense urban environments, where greenery is limited and most free time is spent on screens. The app uses short, achievable eco‑missions, calming AR nature overlays, and social features to make daily contact with plants and green spaces feel fun, social, and habit‑forming instead of like extra homework. [file:207][file:208]

The prototype was developed using a full design‑thinking cycle:

1. Empathize & define: Research on how digital lifestyles disconnect youth from nature  
2. Ideate & sketch: “How might we” exploration, personas, and low‑fi wireframes  
3. Prototype: High‑fidelity Figma flows with 5 compulsory core features  
4. Test & iterate: Usability sessions with teens, followed by targeted design changes  
5. Reflect: Evaluation of UX, AI‑assisted ideation, ethics, and behaviour change impact [file:207][file:208]

---

## 2. Scenario & course context

This project responds to **Scenario 1 – Designing Digital GreenWall** from the Year 2 Critical and Creative Thinking summative brief. GreenBloom Tech Pvt. Ltd. is described as a sustainability‑focused innovation company developing a gamified eco‑companion app to re‑engage urban youth with nature using technology they already enjoy. [file:208]

The assignment’s intended learning outcomes include:

- Applying structured creative frameworks and design methodologies to real social and environmental issues  
- Implementing interface design, user journeys, and functional prototypes for human‑centred digital solutions  
- Using feedback and iteration to refine UX via usability evaluation  
- Demonstrating ethical, sustainable, and innovative thinking in AI‑driven products [file:208]

Digital GreenWall is the chosen solution for this brief and this repository contains the artefacts that evidence the full process.

---

## 3. Core features

The prototype implements all **five compulsory features** specified in the Scenario‑1 brief. [file:208]

### 3.1 Daily Eco‑Challenges

Short, guided missions (5–10 minutes) that can be done at home, at school, or outdoors, such as opening a window and noticing three natural sounds or caring for a small plant. Each challenge:  

- Shows time estimate, difficulty, and context tag (Home / School / Outdoors)  
- Includes a simple explanation of “why this matters” for wellbeing and the environment  
- Updates the user’s streak, Eco‑Avatar growth, and eco‑points on completion [file:207]

### 3.2 AR Nature Simulations

An **AR tab** lets students overlay digital plants and greenwalls onto real walls or corners of their room using the device camera. The AR experience:  

- Offers a few curated scenes (e.g., “Calm Corner”, “Jungle Wall”, “Sunrise Garden”) to avoid control overload  
- Connects each virtual scene to real‑world care tips and a tiny recommended action (e.g., where a real plant might thrive)  
- Acts as a bridge between virtual nature and realistic, small‑scale greening at home or school [file:207]

### 3.3 User Progress Dashboard

A visual **Dashboard** helps users see that their tiny actions add up:

- Weekly completion ring and streak tracker  
- Simple charts for challenges completed over time  
- Eco‑Avatar growth timeline (seed → sprout → plant → mini‑greenwall)  
- Optional mood check‑ins after eco‑time to reinforce wellbeing links [file:207]

### 3.4 Team Missions & Leaderboard

The **Teams** section turns sustainability into a cooperative challenge:

- Class / house missions with shared goals (e.g., “100 eco‑missions in 2 weeks”)  
- A leaderboard that highlights **“Your Team”** and tracks improvement, not just rank  
- Softened competitive pressure through options like “personal best” indicators and more supportive messaging [file:207]

### 3.5 Rewards & Recognition

The **Rewards** tab supports long‑term motivation:

- Badge collection (e.g., “First Week Green”, “Balcony Starter”, “Streak Hero”)  
- Level system (Seedling, Sprout, Young Tree, Mini GreenWall)  
- Space to plug into school‑level recognition, such as house points or eco‑leader certificates [file:207]

---

## 4. UX and AI design approach

### 4.1 User research & persona

Research combined an online survey and short semi‑structured interviews with urban students to explore: current nature contact, screen time, stress, and motivations. A primary persona, **Aarav (“Stressed but scrolling”)**, was created to represent a teen who wants calm and meaning but has limited space and time for traditional gardening. [file:207]

An empathy map captured Aarav’s thoughts (“nature is nice, but I have no time/space”), environment (concrete, traffic, screens), pain points (stress, boredom, eye strain) and desired gains (simple, non‑judgemental ways to feel calmer and proud of small eco‑actions). [file:207]

### 4.2 Planned AI‑assisted features

Although the current repository focuses on design and prototyping, the concept explicitly plans for AI in future technical implementation: [file:208]

- **Adaptive challenge engine:** Suggests daily eco‑challenges based on user history, preferences, and difficulty tolerance  
- **Smart mission recommendations:** Clusters users by living context (e.g., balcony vs no balcony) to recommend realistic missions  
- **Personalised AR scenes:** Learns which scenes users choose and adapts recommended “calm corners” and plant types  
- **Engagement nudges:** Uses simple rules or models to adjust challenge difficulty and send constructive “recovery” suggestions when streaks break  

These ideas are documented to show how AI can enhance personalisation and engagement while staying ethical (no dark patterns, minimal data, clear purpose). [file:207][file:208]

---

## 5. Repository structure

Suggested layout for this GitHub repository:

digital-greenwall/
├─ docs/
│ ├─ Scenario-1-Digital-GreenWall-Main-Report.pdf
│ ├─ research-notes.md
│ └─ usability-test-plan-and-findings.md
├─ design/
│ ├─ figma-export-screens/ # PNG/JPEG exports of key prototype screens
│ ├─ user-flows-diagrams/ # Optional journey maps, empathy maps
│ └─ wireframes/ # Early sketches / low-fi wireframes
├─ prototype/
│ └─ (optional) web-prototype/ # Future React/Flutter or web implementation
├─ README.md
└─ LICENSE (optional)


You can adjust this structure based on what you actually commit.

---

## 6. Getting started

### 6.1 View the interactive prototype

The primary deliverable is a Figma prototype:

- **Figma prototype:** `<https://www.figma.com/...>`  

Steps:

1. Open the link above in a browser  
2. Click **Present** to experience the app as a mobile prototype  
3. Use the bottom tabs (Home, AR, Dashboard, Teams, Rewards) to navigate  

### 6.2 Running a coded prototype (optional / future)

If you later implement a web or mobile version (e.g., using React, Flutter, or Streamlit):

1. Clone the repo:  

2. Follow instructions in `prototype/README.md` for environment setup and running the app.  

For now, this repository focuses on **design artefacts, research, and interaction flows**.

---

## 7. Research, testing, and iteration summary

Digital GreenWall was tested with a small sample of students in the target age group (approx. 13–17) using a think‑aloud usability protocol on the Figma prototype. Participants were asked to: [file:207]

- Understand the app’s purpose from the home screen  
- Complete a daily eco‑challenge  
- Launch and adjust an AR nature simulation  
- Interpret their progress on the dashboard  
- Explore team missions and the leaderboard  

Key findings:

- The core concept (“small eco‑tasks and a growing avatar”) was easily understood and generally motivating  
- AR scenes were exciting but initially felt like “just decoration” until linked more clearly to real‑world actions  
- Younger users focused on streaks and badges more than charts, so visual emphasis was shifted towards short‑term wins  
- Some students were worried about always being low on the leaderboard, leading to changes that emphasised improvement and team success instead of pure rank [file:207]

Design changes included clarifying AR purpose, simplifying controls, emphasising streaks and avatar animations on the dashboard, and softening leaderboard pressure through “personal best” indicators and optional anonymity. [file:207]

---

## 8. Roadmap

Planned future enhancements:

- Implement actual AR prototypes using AR frameworks (e.g., WebAR, ARCore/ARKit)  
- Build a working mobile/web MVP using a modern frontend stack  
- Integrate a simple AI rules engine or recommendation model to personalise challenges  
- Extend the testing programme to more schools and run longer‑term behaviour‑change studies  

---

## 9. Acknowledgements

This project was created for the **Year 2 Critical and Creative Thinking** course under the **CRS: Artificial Intelligence** summative assessment at **<Your School Name>**, following the official assignment brief and rubrics. [file:208]

Special thanks to:

- Peers who participated in surveys, interviews, and usability testing  
- Teachers and mentors who provided feedback on design iterations  
- Open‑source tools and resources used for research, wireframing, and prototyping

---

> **Note:** This repository currently documents the design, research, and prototype for Digital GreenWall. Any future AI or AR implementation must follow your institution’s data‑protection, accessibility, and ethical AI guidelines.
