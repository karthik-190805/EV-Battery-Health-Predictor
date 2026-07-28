# EV Battery Health Predictor

A smart EV battery health monitoring, prediction and visualization system developed using MATLAB, Simulink, Java and a web-based dashboard.

The system analyzes battery operating parameters and estimates:

- State of Health — SOH
- Remaining Useful Life — RUL
- Battery health status
- Battery alarm condition

It supports three lithium-ion battery chemistries:

- Lithium Iron Phosphate — LFP
- Nickel Manganese Cobalt — NMC
- Nickel Cobalt Aluminium — NCA

---

## Project Overview

Electric vehicle performance, safety, efficiency and driving range depend heavily on the condition of the battery.

EV batteries gradually degrade because of factors such as:

- High operating temperature
- Deep charging and discharging
- State-of-charge limits
- Number of battery cycles
- Battery operating time
- Battery chemistry
- Repeated thermal and electrical stress

This project develops a data-driven battery monitoring and prediction system.

MATLAB and Simulink are used to simulate battery operating conditions and generate a structured dataset. The generated data is then used to calculate battery health indicators such as SOH, RUL, health status and alarm condition.

A web-based dashboard displays the battery parameters and allows users to compare the performance of LFP, NMC and NCA battery chemistries.

The project can support:

- Predictive battery maintenance
- Battery degradation analysis
- Early fault identification
- Battery replacement planning
- Battery chemistry comparison
- EV battery lifecycle management

---

## Project Objectives

The main objectives of this project are:

1. Monitor important EV battery parameters.
2. Generate realistic battery operating data using MATLAB and Simulink.
3. Estimate the State of Health of the battery.
4. Predict the Remaining Useful Life of the battery.
5. Classify the battery condition as Good, Warning or End of Life.
6. Generate alarms when the battery operates outside safe limits.
7. Compare LFP, NMC and NCA battery chemistries.
8. Export the generated data into an Excel dataset.
9. Display the battery information through a user-friendly dashboard.
10. Prepare a structured dataset for future machine-learning applications.

---

## Main Features

- Supports LFP, NMC and NCA batteries
- Battery chemistry selection
- Battery chemistry-specific operating limits
- State-of-Charge generation
- SOC stress calculation
- Average temperature monitoring
- Maximum temperature monitoring
- Thermal stress calculation
- Battery cycle-count generation
- State-of-Health estimation
- Remaining Useful Life estimation
- Battery health classification
- Battery alarm generation
- Simulink-based dataset generation
- Excel dataset export
- Web-based dashboard
- Battery degradation visualization
- Battery chemistry comparison
- Predictive-maintenance support
- Machine-learning-ready dataset

---

## System Workflow

The complete project follows this process:

1. Select the required battery chemistry.
2. Load the operating limits for the selected chemistry.
3. Generate battery SOC values.
4. Compare SOC values with the recommended limits.
5. Calculate SOC-related battery stress.
6. Generate average and maximum battery temperature.
7. Calculate temperature-related stress.
8. Generate the battery cycle count.
9. Estimate battery degradation.
10. Calculate the State of Health.
11. Estimate the Remaining Useful Life.
12. Classify the battery health.
13. Generate warning and alarm signals.
14. Collect all battery parameters.
15. Export the results into an Excel dataset.
16. Display the results through the battery analytics dashboard.

---

## System Architecture

```text
Battery Chemistry Selection
            │
            ▼
Battery Chemistry Limits
            │
            ├───────────────┐
            ▼               ▼
     SOC Generator    Temperature Generator
            │               │
            ▼               ▼
      SOC Stress      Temperature Stress
            │               │
            └───────┬───────┘
                    ▼
             Cycle Generator
                    │
                    ▼
              SOH Estimator
                    │
                    ▼
              RUL Estimator
                    │
                    ▼
            Health Classification
                    │
                    ▼
             Alarm Generation
                    │
                    ▼
              Data Collector
                    │
                    ▼
        Excel Dataset and Dashboard
