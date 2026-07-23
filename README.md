# 📊 DataSense Navigator | Multi-Agent Business Intelligence System

An AI-powered Business Intelligence solution designed to eliminate dashboard fatigue. Built using **Lyzr Agent Studio** and powered by **gpt-5.4-mini**, DataSense Navigator translates complex, raw data into clear, actionable executive summaries in real time.

---

## 🎯 The Problem & Solution

* **The Problem:** Executives and decision-makers often spend hours navigating cluttered dashboards to extract critical insights and spot operational risks.
* **The Solution:** A conversational multi-agent system where users can ask questions in plain English (e.g., assessing customer risk profiles or regional variances) and instantly receive a structured executive performance report.

---

## 🏗️ System Architecture

DataSense Navigator operates using a **Manager-Worker Multi-Agent Architecture**:

* 🧠 **Strategic Orchestrator (Manager Agent):** Powered by `gpt-5.4-mini`, it interprets user intent, delegates analytical tasks, and synthesizes final insights.
* 🔍 **Core Metrics Verifier (Worker Agent):** Validates raw numeric data and ensures accurate baseline KPI reporting.
* 📈 **Trend & Anomaly Detector (Worker Agent):** Identifies performance patterns, outliers, and operational risks.
* ⚡ **Action Trigger (Worker Agent):** Generates concrete, step-by-step recommendations and automated operational alerts.

---

## 🚀 Key Output Features

The system returns a standardized 4-part report for every query:
1. **Executive Summary:** Clear, high-level summary of findings.
2. **Verified Metrics Table:** Clean Markdown tables summarizing exact numbers.
3. **Strategic Recommendations:** Simple, non-technical next steps.
4. **Operational Alert Logs:** Real-time flagging of urgent risks or anomalies.

---

## 🛠️ Tech Stack & Acknowledgments

* **Platform:** Lyzr Agent Studio
* **Core Model:** gpt-5.4-mini
* **Mentorship:** Beat Educations & Prasad Sawant

---

## 📌 Demonstration & Screenshots

*(Note: Public live deployment is currently undergoing environment checks.)*

### 1. Multi-Agent Orchestration Flow
![Orchestration Canvas Flow](./Screenshot%20(605).png)

### 2. Strategic Manager Configuration & Prompt Logic
![Manager Instructions Setup](./Screenshot%20(606).jpg)

### 3. Deployment & API Endpoint Setup
![Deployment Page](./Screenshot%20(607).jpg)

### 4. Agent Studio Registry
![Agent Overview List](./Screenshot%20(608).png)
