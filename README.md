# Hypervisor Scheduler

The Hypervisor Scheduler is a dynamic partition-based scheduling tool designed to manage and simulate scheduling for multiple partitions. It allows users to define partition durations, periodicities, and priorities, while also visualizing the results. The tool is built using Python with a GUI powered by Tkinter.

---

## Features
- Dynamic input of partition parameters (e.g., duration, periodicity).
- Handles scheduling conflicts with priority-based resolution.
- Generates scheduling logs in CSV and XML formats for VxWorks and PikeOS.
- Visualizes partition activity over time using 3D bar graphs.

---

## Prerequisites
To run the project, ensure you have the following installed:
- Python 3.7 or higher
- Required Python libraries:
  - `tkinter`
  - `pandas`
  - `matplotlib`
  - `numpy`

Install the required libraries using:
```bash
pip install -r requirements.txt
