# User Stories

**Project:** Sentiment-Aware Traffic Light Scheduling Optimization for Emergency Vehicle Pre-emption

---

## US1 – Clearing the Junction for an Ambulance

> **As an** ambulance driver,
> **I want** the junction lights to clear when I approach,
> **so that** I can pass through without stopping and reach the patient faster.

**Linked requirements:** FR3, FR4

**Acceptance criteria:**
1. When an emergency vehicle is detected, all lanes at the junction turn red within 2 seconds.
2. The pre-emption is **not** triggered when no emergency vehicle is detected.
3. The normal signal cycle resumes after the emergency vehicle has passed.

---

## US2 – Viewing Predicted Congestion

> **As a** traffic authority officer,
> **I want** to see the predicted congestion level of each junction,
> **so that** I can plan routes for emergency vehicles in advance.

**Linked requirements:** FR2, FR6

**Acceptance criteria:**
1. Choosing a junction and a time slot shows a congestion level of Low, Medium or High.
2. The prediction is displayed on the dashboard in under 3 seconds.
3. Only logged-in authority users can access the dashboard.

---

## US3 – Reviewing Pre-emption Events

> **As a** traffic authority officer,
> **I want** each pre-emption event to be recorded,
> **so that** I can review how often and where emergency vehicles were given priority.

**Linked requirements:** FR7

**Acceptance criteria:**
1. Each recorded event shows the date, time and junction.
2. Events can be filtered by junction.
3. A new event appears in the log immediately after a pre-emption is triggered.

---

## Summary

| User Story | User | Linked Requirements |
|------------|------|---------------------|
| US1 | Ambulance driver | FR3, FR4 |
| US2 | Traffic authority officer | FR2, FR6 |
| US3 | Traffic authority officer | FR7 |
