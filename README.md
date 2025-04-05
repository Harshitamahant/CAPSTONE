# 🤖 AI-Powered Real-Time Task Scheduling for Efficient and Scalable Distributed Systems
![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Jupyter%20Notebook-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)


This project implements an **AI-driven real-time task scheduler** designed for **distributed environments**, such as edge-cloud systems. It uses intelligent prioritization and dynamic scheduling techniques to optimize task execution, reduce latency, and improve scalability.

![Data Flow Diagram - visual selection](https://github.com/user-attachments/assets/6b84ee9c-2d2b-491d-a860-71e5bcaf474d)



---

## 🚀 Project Objectives

- ⚙️ Efficient resource allocation in distributed environments
- 🔁 Dynamic task prioritization based on complexity, deadlines, and system state
- ⏱️ Real-time decision-making using AI algorithms
- 🌐 Designed for scalability across multi-core and cloud-edge infrastructures

---

## 🛠️ Implementation Overview

The implementation is provided in Jupyter Notebooks using Python.

### 🔹 Task Representation

Each task includes the following parameters:
- `arrival_time`: When the task is introduced into the system
- `priority`: High / Medium / Low
- `execution_time`: Estimated run time
- `deadline`: Optional deadline (used in EDF strategies)

### 🔹 Scheduling Algorithm

An AI-based custom scheduler that includes:
- Priority queues (min-heaps, max-heaps)
- Earliest Deadline First (EDF) or Shortest Job First (SJF)
- Real-time queue updates and decisions

### 🔹 Execution Simulation

Tasks are scheduled and executed using simulated time slots:
- Context switching is tracked
- Execution logs are maintained
- Gantt chart visualizes execution order

---

## 📊 Outputs and Visualizations

### ✅ Performance Metrics Captured
- Turnaround Time
- Waiting Time
- Completion Time
- Execution Order Log
- Priority Scheduling Accuracy

### 📈 Gantt Chart (Execution Timeline)

> Visualizes real-time execution timeline with task ID, start time, and duration, color-coded by priority.

| Color  | Priority |
|--------|----------|
| 🟥 Red | High     |
| 🟧 Orange | Medium   |
| 🟩 Green | Low      |

![image](https://github.com/user-attachments/assets/3fda5719-bfcf-40a5-ad28-ba035e4445ce)


### ✅ Sample Task Execution Summary

The system executed a set of tasks based on their priorities, arrival times, and deadlines. Below is a sample execution summary extracted from the simulation:

| **Task ID** | **Priority** | **Arrival Time** | **Start Time** | **Execution Time (s)** | **End Time** | **Waiting Time** |
|------------|--------------|------------------|----------------|------------------------|--------------|------------------|
| Task-1     | High         | 12:00:00         | 12:00:00       | 6                      | 12:00:06     | 0                |
| Task-2     | Medium       | 12:00:10         | 12:00:10       | 8                      | 12:00:18     | 0                |
| Task-3     | Low          | 12:00:20         | 12:00:20       | 9                      | 12:00:29     | 0                |

These results demonstrate the system's ability to assign and execute tasks promptly with minimal delay.

### 🚀 CONCLUSION FROM RESULTS

- ✅ The AI Scheduler effectively prioritizes critical tasks while maintaining low overhead.
- 📊 Gantt charts and performance metrics demonstrate strong execution efficiency compared to static scheduling methods.
- 🌐 The system is ready for real-world deployment in edge-cloud or distributed computing environments where scalability and responsiveness are key.
--- 

## 📄 Final Report

The full project report includes:
- Overview of scheduler logic
- Sample execution scenarios
- Tables summarizing execution time, priorities, and start/end times
- Visualization of task flow

  ![Screenshot 2025-04-04 200530](https://github.com/user-attachments/assets/9af547c4-110a-4ced-8001-fda1d9223ee3)


📁[Download Report (AI_Task_Scheduling_Report.docx)](Report/AI_Task_Scheduling_Report.docx)

---

## 💻 Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Matplotlib / Plotly (Gantt chart)
- heapq, queue
- python-docx

---

## 🤝 Contributions & Contact

Developed as part of an academic/research CAPSTONE project.

📧 Email: harshitamahant09@gmail.com
🔗 GitHub: Harshitamahant(https://github.com/Harshitamahant)


🔗 GitHub: https://github.com/vedant-9999


---

## 📜 License

This project is licensed under the [MIT License](LICENSE)


