# Requirements

**Project:** Sentiment-Aware Traffic Light Scheduling Optimization for Emergency Vehicle Pre-emption

This document lists the functional and non-functional requirements of the proposed system. Each functional requirement contains one idea and can be tested. Each non-functional requirement is measurable.

---

## 1. Functional Requirements

Functional requirements describe **what the system must do**.

| ID | Functional Requirement | How It Is Tested |
|----|------------------------|------------------|
| FR1 | The system shall import historical junction traffic data from a CSV file. | Upload a sample CSV file; the records appear in the database. |
| FR2 | The system shall predict the congestion level (Low, Medium, High) of a junction for a selected time slot. | Select a junction and a time slot; a congestion level is displayed. |
| FR3 | The system shall detect an approaching emergency vehicle at the junction. | Trigger the detection sensor; a detection event is logged. |
| FR4 | The system shall switch all signals at the junction to red when an emergency vehicle is detected. | Trigger detection; all lights on the traffic light model turn red. |
| FR5 | The system shall restore the normal signal cycle after the emergency vehicle has passed. | Send the clear signal; the normal cycle resumes. |
| FR6 | The system shall display predicted congestion levels on a web dashboard. | Open the dashboard; predictions are shown for each junction. |
| FR7 | The system shall record each pre-emption event with its date, time and junction. | Trigger pre-emption; a new log entry is created. |

---

## 2. Non-Functional Requirements

Non-functional requirements describe **how well the system must perform**. Each one is a different type and includes a measurable condition.

| ID | Type | Non-Functional Requirement |
|----|------|----------------------------|
| NFR1 | Performance | The system shall switch all signals to red within **2 seconds** of detecting an emergency vehicle. |
| NFR2 | Accuracy | The selected machine learning model shall achieve at least **85% accuracy** on the test dataset. |
| NFR3 | Usability | The dashboard page shall load in under **3 seconds** on a standard broadband connection. |
| NFR4 | Security | Only logged-in users with the **Authority** or **Admin** role shall be able to view the dashboard and event logs. |
| NFR5 | Reliability | The pre-emption function shall succeed in at least **95 out of 100** test triggers on the prototype. |

---

## 3. Traceability to Project Objectives

| Project Objective | Related Requirements |
|-------------------|----------------------|
| To identify the most suitable machine learning algorithm for predicting traffic congestion | FR1, FR2, NFR2 |
| To develop a sentiment-aware traffic light scheduling optimization that predicts congestion and automates emergency vehicle pre-emption | FR3, FR4, FR5, FR6, NFR1, NFR4 |
| To evaluate prediction accuracy and response time reduction in emergency vehicle pre-emption | FR7, NFR1, NFR2, NFR5 |
