# 📘 Team Assignment – Predictive Model Project
### Introduction to Data Science and Machine Learning (Summer Semester 2025)

**Group 4**  
Members: Louis, Malak, Eero, and Lena

---

## Milestones

- **Milestone 1** (25 May 2025): Data loading, cleaning, and early exploration
- **Milestone 2** (22 June 2025): Modeling and initial evaluation
- **Final Submission** (15 July 2025): Final notebook, slide deck, and reflection

---

## TODOs

### Data Cleaning

- [x] Remove rows with `trip_miles == 0` or `trip_seconds == 0`
- [X] Ensure `trip_start_timestamp` is in datetime format (+ handle rows with missing or corrupt values)
- [X] Extract `hour` and `day_of_week` from timestamps
- [ ] Handle missing values in `fare`, `trip_total`, or location fields
- [ ] Other filtering tasks?

### Feature Engineering

- [x] Add `traffic_volume` as a new feature (`trip_seconds / trip_miles`)
- [ ] Add external weather data (e.g., via Meteostat API)
