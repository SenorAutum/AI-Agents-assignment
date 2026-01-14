# AI-Agents-assignment
This is a public repository for my final AI for software Engineering assignment 
# 🏭 Smart Manufacturing AI Agents: AutoParts Inc.

**Project:** AI Agent Implementation Strategy & Simulation  
**Course:** PLP Academy  
**Date:** January 2026

![Status](https://img.shields.io/badge/Status-Prototype-green)
![Platform](https://img.shields.io/badge/Platform-Make.com-purple)
![Focus](https://img.shields.io/badge/Focus-Supply%20Chain%20AI-blue)

## 📖 Project Overview
This repository contains the comprehensive proposal and technical simulation for **"AutoFlow Core,"** an AI Agent ecosystem designed for **AutoParts Inc.**

The goal of this project is to address critical manufacturing challenges—specifically high defect rates (15%), unpredictable machine downtime, and labor shortages—by deploying a symbiotic network of autonomous agents.

## 🧠 Strategic Proposal (The Agents)
The solution relies on three specialized AI agents working in tandem:

### 1. 🛡️ The Sentinel (Predictive Maintenance)
* **Role:** IoT Data Monitor
* **Function:** Ingests real-time temperature and vibration data. Instead of waiting for a breakdown, it autonomously schedules maintenance when failure probabilities spike.
* **Target Impact:** Reduce machine downtime by 40%.

### 2. 🦅 Hawk-Eye (Quality Control)
* **Role:** Computer Vision Inspector
* **Function:** Inspects precision components at the end of the assembly line. It learns from human overrides to continuously improve its defect detection accuracy.
* **Target Impact:** Reduce defect rate from 15% to <3%.

### 3. ⏱️ The Dynamic Scheduler (Operations)
* **Role:** Workflow Optimizer
* **Function:** Re-routes production tasks in real-time based on machine availability and rush order status, ensuring optimal labor allocation.

## 🛠️ Simulation Details
To demonstrate the technical feasibility of "The Sentinel," I created a live logic flow using **Make.com**.

### How it Works (The Logic)
1.  **Data Generation:** A specialized module generates randomized synthetic data:
    * `Temperature` (60°C - 100°C)
    * `Vibration` (0 - 10)
2.  **The Brain (Router):** The data flows into a decision engine that evaluates risk:
    * **CRITICAL PATH:** Activates if `Temp > 90` **OR** `Vibration > 8`.
    * **NORMAL PATH:** Activates if all parameters are within safe limits.
3.  **Actuation:**
    * **If Critical:** An emergency email/alert is autonomously drafted and sent to the maintenance lead.
    * **If Normal:** Data is logged to a Google Sheet for long-term trend analysis.

### 📸 Visual Proof
<img width="975" height="591" alt="image" src="https://github.com/user-attachments/assets/a019ff7f-7f15-4f82-a0e9-dac569f904db" />


## 🚀 How to Run the Simulation
Since Make.com scenarios are private by default, I have included the **Blueprint** for the workflow.

1.  Download the `blueprint.json` file from this repository (if applicable).
2.  Log in to [Make.com](https://www.make.com).
3.  Create a new Scenario.
4.  Click **More** (three dots) → **Import Blueprint**.
5.  Click **Run Once** to see the data generation and logic routing in action.

## ⚖️ Ethical & Risk Analysis
* **Worker Displacement:** We propose an "Up-skilling Initiative" to transition assembly workers into "AI Supervisors," mitigating the risk of job loss.
* **Algorithmic Accountability:** All autonomous decisions (especially those halting production) are logged with a "Why-Trace" to ensure explainability.
* **Data Privacy:** Productivity monitoring is anonymized to protect individual worker privacy while still optimizing the overall system.

---
*Developed by Brandon Mwanzia for the PLP Academy assignment.*
