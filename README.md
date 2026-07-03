# SIR Model of COVID-19 Dynamics

## Overview

This project implements the classical **Susceptible–Infected–Recovered (SIR)** epidemiological model to simulate the spread of COVID-19. Using publicly reported case data, the model estimates disease transmission dynamics and compares theoretical epidemic behavior with observed infection trends.

The project demonstrates how compartmental mathematical models can be used to analyze infectious disease outbreaks and evaluate the impact of epidemiological parameters such as the transmission rate, recovery rate, and basic reproduction number.

---

## Background

Mathematical epidemiology provides a framework for understanding how infectious diseases spread through populations. One of the most widely used compartmental models is the **SIR model**, which divides a population into three groups:

* **Susceptible (S):** Individuals who can become infected.
* **Infected (I):** Individuals capable of transmitting the disease.
* **Recovered (R):** Individuals who have recovered or are no longer infectious.

The model describes the movement of individuals between these compartments using a system of differential equations, allowing researchers to study epidemic growth, peak infections, and disease decline.

---

## Objectives

This project aims to:

* Simulate COVID-19 transmission using the SIR model.
* Compare modeled infections with observed case data.
* Estimate epidemic parameters such as transmission and recovery rates.
* Analyze disease progression over time.
* Demonstrate the application of mathematical modeling to public health.

---

## Methodology

The model follows the standard SIR system of differential equations:

* Susceptible individuals become infected through contact with infected individuals.
* Infected individuals recover at a constant recovery rate.
* The total population remains constant throughout the simulation.

Model parameters include:

* **Transmission rate (β)**
* **Recovery rate (γ)**
* **Basic reproduction number (R₀ = β/γ)**
* **Initial susceptible, infected, and recovered populations**

The spreadsheet iteratively computes daily changes in each compartment and compares the modeled number of new infections against reported COVID-19 case data.

---

## Dataset

The model uses reported COVID-19 case counts together with moving averages to reduce short-term reporting fluctuations.

The spreadsheet contains:

* Daily reported cases
* 7-day moving average
* Cumulative cases
* Susceptible population
* Infected population
* Recovered population
* Daily compartment changes (dS, dI, dR)
* Modeled new infections

---

## Analysis

The analysis examines:

* Epidemic growth over time
* Changes in susceptible, infected, and recovered populations
* Model-predicted infections versus observed cases
* Trends in daily reported infections
* Effects of transmission and recovery parameters

The comparison between observed and modeled cases provides insight into how well the classical SIR framework captures the overall dynamics of the outbreak.

---

## Key Mathematical Concepts

* Ordinary Differential Equations (ODEs)
* Compartmental Epidemiological Models
* Disease Transmission Dynamics
* Basic Reproduction Number (R₀)
* Numerical Simulation
* Time-Series Analysis

---

## Tools Used

* Microsoft Excel
* Mathematical Modeling
* Data Analysis

---

## Skills Demonstrated

* Mathematical Modeling
* Epidemiological Modeling
* Time-Series Analysis
* Data Interpretation
* Statistical Analysis
* Spreadsheet Modeling
* Model Validation

---

## Repository Contents

```text
├── SIR Model of COVID-19 Dynamics.xlsx
├── README.md
```

---

## Future Improvements

Potential extensions include:

* SEIR (Susceptible–Exposed–Infected–Recovered) model
* Time-varying transmission rates
* Parameter estimation through optimization
* Vaccination and intervention scenarios
* Sensitivity analysis
* Interactive visualizations using Python

---

## Author

**Jerick L. Garcia**

Bachelor of Science in Mathematics
University of the Philippines Diliman
