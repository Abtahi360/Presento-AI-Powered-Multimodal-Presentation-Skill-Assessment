# Presento – AI-Powered Multimodal Presentation Skill Assessment

## Project Overview

**Presento** is a software engineering project designed to provide **automated, multimodal feedback** on students’ presentation skills.
It leverages **computer vision, speech analysis, and slide evaluation** to give learners objective, data-driven insights while reducing instructor workload.

This repository contains the **full project documentation**, following all phases of the **Software Development Life Cycle (SDLC)**, except the coding/implementation phase.

---

## Features

* **Multimodal Feedback**: Posture, gestures, voice delivery, and slide quality.
* **Dashboards**: Student progress tracking and instructor cohort overview.
* **AI Integration**: Whisper, BlazePose, CNN, and BERT-based models for feedback.
* **Report Generation**: Annotated visuals, transcripts, and shareable PDFs.
* **Privacy & Consent**: Role-based access, encryption, and data deletion flow.

---

## SDLC Phases Covered

* **Requirement Analysis**: Detailed PRD (Functional & Non-Functional Requirements).
* **Planning**: Effort estimation, COCOMO analysis, scheduling, and risk management.
* **Design**:

  * Use Case, Class, Activity, and Data Flow Diagrams
  * UI Wireframes (Figma)
  * Trello-based workflow planning
* **Testing**: Conducted against **acceptance criteria from the PRD**, including signup, login, file uploads, multimodal analysis, and reporting modules.
* **Metrics**: Object-oriented metrics (WMC, LCOM, DIT, NOC) and product metrics.
* **Documentation**: Comprehensive SDLC documentation and future work roadmap.

---

## Testing Approach

All testing was **acceptance-driven**, meaning each test case was derived from the **Product Requirement Document (PRD)**.

* **Unit & Integration Testing**: Modules like signup, login, and upload.
* **Functional Testing**: Based on user stories & acceptance criteria.
* **System Testing**: Verified workflows such as report generation and privacy compliance.
* **Result**: Most core functionalities passed expected outcomes; a few edge cases (e.g., filtering, slide predictions) were flagged for refinement.

---

## Project Management

* **Model Used**: Agile (Scrum framework)
* **Effort Estimation**: Function Point Analysis + COCOMO (\~16,781 LOC, \~71 PM effort).
* **Scheduling**: Gantt chart milestones across Analysis → Planning → Design → Implementation → Testing → Documentation.
* **Risk Management**: Identified risks such as AI accuracy, privacy issues, and scalability.

---

## Future Work

* Real-time feedback during live presentations.
* Cloud-native scalability for large cohorts.
* Emotion detection & engagement measurement.
* Adaptive coaching with progress-aware feedback.
* Multilingual support for broader accessibility.
