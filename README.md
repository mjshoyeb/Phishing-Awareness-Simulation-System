# Phishing Awareness Simulation System (PASS) 🛡️

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Architecture: Serverless/Frontend](https://img.shields.io/badge/Architecture-Frontend%20Only-success.svg)]()
[![Target Audience: Cyber Security Educators](https://img.shields.io/badge/Audience-Educators%20%26%20Students-orange.svg)]()

A formal, client-side educational simulation architecture engineered to visually demonstrate the structural mechanics of modern credential-harvesting (phishing) vectors. This platform operates entirely on an isolated frontend framework to guarantee **Zero Data Retention** and comply with **Ethical Security Training** benchmarks.

---

## 🎯 Executive Objectives
Social Engineering and Phishing remain primary entry vectors for organizational data breaches. This project serves as a **Controlled Demonstration Environment** designed to train end-users, students, and corporate personnel. By interacting with a realistic premium portal layout, participants learn to prioritize domain name validation over visual UI/UX trust cues (such as Glassmorphism, dynamic menus, and brand replication).

---

## 📂 Architectural Components
The repository contains a fully decoupled, zero-dependency static file structure:

```text
.
├── index.html         # High-fidelity landing interface incorporating interactive UI & CDN styling
├── login.html         # Conceptual gateway interface simulating third-party authentication via JavaScript interception
└── awareness.html     # Security debriefing module and mitigation instruction layout
