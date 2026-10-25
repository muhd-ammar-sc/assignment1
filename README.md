# Sentiment-Aware Traffic Light Scheduling for Emergency Vehicle Pre-emption

Predicting junction congestion with supervised machine learning so that traffic lights can clear the way for emergency vehicles in Malaysian cities.

## Problem statement
Ambulance and fire-and-rescue crews in Malaysian urban areas are delayed at signalised junctions because traffic lights run on fixed, time-based cycles that cannot adapt when an emergency vehicle approaches. Traffic authorities also cannot predict which junctions will be congested, because traffic data is only available as static charts and summary reports, so routes cannot be cleared in advance. This matters because traffic congestion is one of the main causes of slower emergency response, and every minute of delay reduces a patient's chance of survival. Existing pre-emption approaches are inflexible and lack predictive intelligence.

## Documents
- [Problem statement](docs/problem-statement.md)
- [Requirements](docs/requirements.md)
- [User stories](docs/user-stories.md)
- [Sprint log](docs/sprint-log.md)

## Specialized technology
Supervised machine learning (Decision Tree, Random Forest, LSTM) using Python, scikit-learn and Pandas to predict junction congestion levels (Low, Medium, High).

## Project structure
```
.
|-- README.md
|-- LICENSE
|-- .gitignore
|-- docs/
|   |-- problem-statement.md
|   |-- requirements.md
|   |-- user-stories.md
|   |-- sprint-log.md
|-- src/
    |-- README.md      (code will go here)
```

## Roadmap
- [x] Problem statement written
- [x] Requirements numbered and linked to user stories
- [x] User stories have acceptance criteria
- [x] Specialized technology chosen (supervised machine learning)
- [ ] Specialized technology explained with sources (Assignment 1 Part C)
- [ ] Traffic dataset collected and cleaned
- [ ] Machine learning models compared and best model selected
- [ ] First prototype with miniature traffic light model (later in the semester)

## Status
Sprint 1 completed (CSC649, Week 4). The system has not been built yet.

## Author
- Muhammad Ammar bin Mohd Azham
- Bachelor of Computer Science (Hons.), Universiti Teknologi MARA (UiTM)
- 2024410882@student.uitm.edu.my
