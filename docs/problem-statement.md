# Problem Statement

Ambulance and fire-and-rescue crews in Malaysian urban areas are delayed at signalised junctions because traffic lights run on fixed, time-based cycles that cannot adapt when an emergency vehicle approaches (Omar et al., 2025).

Traffic authorities also have no tool to predict which junctions will be congested. Available traffic data is presented only as static charts and annual summary reports, so routes cannot be cleared in advance.

This matters because traffic congestion is one of the main external factors that increases emergency response time, and every minute of delay significantly reduces a patient's chance of survival (Alshebani et al., 2025).

Existing pre-emption approaches are inflexible in handling unpredictable events such as emergency vehicle arrivals and lack predictive intelligence (Trehan & Sharma, 2026).

### 1.1 Social Problem
- Emergency vehicles are delayed at intersections, which harms public safety and survival rates in Malaysia.
- Responders and authorities cannot anticipate high-risk congestion zones, so they cannot clear routes ahead of time.
- AI traffic tools used by enforcement agencies remain internal and are not accessible to emergency responders.

### 1.2 Technical Problem
- Traffic signals run on fixed-time schedules and cannot adapt to emergencies in real time.
- There is no automated traffic control system that responds to congestion patterns or triggers pre-emption.
- Previous studies on congestion in Kuala Lumpur and Selangor were descriptive rather than predictive.

## 2. Users and Stakeholders

| User / Stakeholder | Type | Role and Interest |
|--------------------|------|-------------------|
| Emergency responders (ambulance drivers, Bomba crews) | Primary user | Need junctions to be cleared quickly when they approach, so they can reach patients and incidents faster. |
| Traffic authorities (local council traffic unit, PDRM traffic) | Primary user | Monitor predicted congestion levels and pre-emption events on the dashboard to plan emergency routes. |
| System administrator | Secondary user | Manages user accounts, junction settings and updates to the machine learning model. |
| Patients and the public | Indirect stakeholder | Benefit from faster emergency response. Other road users are affected by all-red phases. |

## 3. Evidence

- **Omar et al. (2025)** report that in Malaysia, rapid urban growth and rising vehicle numbers cause persistent congestion, and that existing time-based signal systems fail to clear emergency vehicles caught in this congestion, resulting in poor travel times.
- **Alshebani et al. (2025)** identify traffic congestion as one of the most significant external factors affecting emergency response times, and state that every minute of delay is linked to a significant reduction in survival probability.
- **Trehan & Sharma (2026)** state that traditional signal systems are inflexible in handling unpredictable events such as emergency vehicle arrivals.

---

## 4. Project Scope

### 4.1 In Scope
- Analysing **junction-level traffic data** from **urban areas in Malaysia**, using publicly accessible datasets.
- Studying **historical congestion patterns** to generate **future congestion predictions**.
- Comparing and selecting the **most suitable supervised machine learning algorithm** for congestion prediction.
- Implementing the selected model into a signal control system that **turns all lights red** at the junction when an emergency vehicle is detected, so it can pass without obstruction.
- Building a **prototype** using a **miniature traffic light model** or a **single controlled junction**, with a web dashboard for authorities.

### 4.2 Out of Scope
- Real-time traffic reporting from enforcement agencies.
- Public deployment of the system on real roads.
- Multi-junction or city-wide network control.
- Rural areas and traffic data from outside Malaysia.
- Integration with official national emergency dispatch systems.
