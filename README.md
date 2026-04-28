# <p align="center"> <img width="350" height="350" alt="Image" src="https://github.com/user-attachments/assets/c89bbdfa-5b7e-412c-868a-d0456bd583e0" /> AUTOBOTs: Autonomous Security Engineer </p>

AUTOBOTs is an **AI-driven, autonomous penetration testing framework** designed to revolutionize how organizations identify, validate, and remediate security vulnerabilities. Built using a **multi-agent architecture** and **Large Language Models (LLMs)**, AUTOBOTs goes beyond traditional automation by introducing adaptive reasoning, real exploit validation, and scalable offensive security operations with minimal human supervision.

## 🚀 Key Features

* **Multi-Agent Architecture**
  Autonomous AI agents collaborate to perform reconnaissance, analysis, exploitation, and reporting.

* **Intelligent Analysis with LLMs**
  Uses fine-tuned Large Language Models to interpret scan results, reason about attack paths, and reduce false positives.

* **End-to-End Autonomous Penetration Testing**
  Covers the full lifecycle: OSINT → reconnaissance → vulnerability scanning → exploit development → PoC validation → reporting.

* **Real-Time Adaptation**
  Dynamically adjusts testing strategies based on intermediate findings and system behavior.

* **Exploit Validation & Proof-of-Concepts**
  Verifies vulnerabilities through reproducible PoCs to eliminate noise and ensure actionable results.

* **Advanced Reporting**
  Generates detailed, compliance-ready reports with mitigation recommendations (PDF, HTML, DOCX).

* **Secure by Design**
  Encrypted communications, role-based access control, and compliance with industry standards.

## 🧠 Supported Security Capabilities

* OSINT Gathering
* Target Reconnaissance
* Vulnerability Scanning
* Exploit Development & Validation
* Web Application Testing
* Cloud Security Assessment
* Authentication & Authorization Testing
* Bug Bounty Workflow Simulation
* CTF Challenge Solving

## Installation

### Quick Setup to Run the AUTOBOTs MCP Server

```bash
# 1. Clone the repository
git clone https://github.com/haseeb557/AUTOBOTs-Autonomous-Security-Engineer.git
cd "AUTOBOTs-Autonomous-Security-Engineer"
cd "FYP 4 - Full Code"

# 2. Create virtual environment
python3 -m venv autobots-env
source autobots-env/bin/activate  # Linux/Mac
# autobots-env\Scripts\activate   # Windows

# 3. Install Python dependencies
pip3 install -r requirements.txt
```
### Start the Server

```bash
# Start the MCP server
python3 hexstrike_server.py

# Optional: Start with debug mode
python3 hexstrike_server.py --debug

# Optional: Custom port configuration
python3 hexstrike_server.py --port 8888
```

