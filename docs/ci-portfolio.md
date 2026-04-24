# Continuous Intelligence Portfolio

**Name/Alias:** Tamia
**Date:** 2026-04

This page summarizes my work on continuous intelligence projects, focusing on signal design, anomaly detection, rolling monitoring, and drift analysis.

---

## 1. Professional Project

**[Repository Link](https://github.com/TGoode01/cintel-01-getting-started):**

**Brief Overview of Project Tools and Choices:**
This project establishes the development environment and introduces the core concepts of continuous intelligence. It focuses on setting up Python environments, organizing project structure, and running a basic data-driven app. The goal is to build familiarity with the workflow used across all later projects, including version control, reproducibility, and documentation practices.

**Key Takeaway**
I learned how to properly structure, run, and manage a data analytics project from scratch.

---

## 3. Signal Design

**Repository Link:**  (https://github.com/TGoode01/cintel-03-signal-design)

### Signals
- `error_rate = errors / requests` → tracks system reliability
- `avg_latency = total_latency / requests` → measures performance efficiency

### Artifacts
(https://github.com/TGoode01/cintel-03-signal-design/tree/main/artifacts)

Includes computed signal datasets and visualizations.

### Insights
Signals made it easier to identify trends such as increasing error rates or rising latency that were not obvious in raw data.

---

## 4. Rolling Monitoring

**Repository Link:**
https://github.com/TGoode01/cintel-04-rolling-monitoring

### Techniques
Used rolling windows (e.g., rolling mean and rolling standard deviation) to smooth noise and observe short-term trends.

### Artifacts
https://github.com/TGoode01/cintel-04-rolling-monitoring/tree/main/artifacts


### Insights
Rolling monitoring revealed short-term trends and changes in volatility, helping identify gradual performance degradation.

---

## 5. Drift Detection

**Repository Link:**
https://github.com/TGoode01/cintel-05-drift-detection

### Techniques
Compared a baseline period (historical data) to a current period using rolling statistics such as mean and standard deviation. Drift was identified through consistent differences.

### Artifacts
https://github.com/TGoode01/cintel-05-drift-detection/tree/main/artifacts

Includes comparison charts and summary statistics.

### Insights
Detected shifts in system behavior such as increased error rates or variability, supporting data-driven decision-making.

---

## 6. Continuous Intelligence Pipeline

**Repository Link:**
https://github.com/TGoode01/cintel-06-continuous-intelligence

### Techniques
Combined all components into a pipeline:
- Read input data
- Generate signals
- Apply rolling monitoring
- Detect anomalies and drift

### Artifacts
https://github.com/TGoode01/cintel-06-continuous-intelligence/tree/main/artifacts

Includes final reports, dashboards, or summary outputs.

### Assessment
The pipeline provides a clear view of system health by combining multiple signals and detection methods. It enables early issue detection and supports informed decision-making.
