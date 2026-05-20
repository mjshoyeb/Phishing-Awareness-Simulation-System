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
├── index.html         # High-fidelity landing interface incorporating interactive UI
├── login.html         # Conceptual gateway interface simulating third-party authentication
└── awareness.html     # Security debriefing module and mitigation instruction layout

⚙️ Technical Specifications & Privacy Guardrails
Unlike malicious production-level exploitation kits, this educational model implements rigid safety constraints natively embedded within the core logic:

Zero-Server Footprint: Completely decoupled from backend routing servers (Flask, Django, Node.js, or PHP), ensuring no capability for external data exfiltration.

Client-Side Interception: Implements standard browser-level event handlers (event.preventDefault()) to intercept input variables inside local runtime memory.

Volatile Data Lifecycle: Input parameters are instantly terminated upon event firing. No telemetry or plain-text strings are cached, stored locally (localStorage/sessionStorage), or written to persistent logs.

🚀 Execution Guide
This framework is designed as a standalone "Plug-and-Play" architecture, removing runtime environment overheads.

Prerequisites
Any standard compliant modern web browser (e.g., Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).

Local Initialization
Clone the repository into your secure local directory:

Bash:

git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
Access the root directory of the project.

Execute index.html via a direct double-click or by dragging the file into an active browser window.

Step through the simulation sequence during academic workshops, IT compliance training, or defense demonstrations.

🧠 Strategic Mitigation Takeaways
The simulated workflow explicitly reinforces three pillars of digital hygiene:

Differentiating UI Trust vs. Domain Trust: Training users to structurally parse hostnames in the URL bar rather than relying on design aesthetics.

Cognitive Awareness of Pretexting: Spotting psychological hooks such as artificial scarcity or high-value rewards ("1-Year Premium Free").

Defense-in-Depth: Visualizing the absolute necessity of Multi-Factor Authentication (MFA/2FA) to render intercepted credentials useless to threat actors.

⚖️ Regulatory Compliance & Disclaimer
This framework is distributed strictly for academic research, institutional training, and non-profit cyber security awareness initiatives. The codebase is explicitly restricted from commercial deployment or unauthorized modifications targeting real-world entities. The author disclaims all liability for downstream misuse or policy violations stemming from negligent configurations of this educational template.

Developed for Cyber Security Educational Reference. Distributed under the MIT License.