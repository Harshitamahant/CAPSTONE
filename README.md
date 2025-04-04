# 🤖 AI-Powered Real-Time Task Scheduling for Efficient and Scalable Distributed Systems

This project implements an **AI-driven real-time task scheduler** designed for **distributed environments**, such as edge-cloud systems. It uses intelligent prioritization and dynamic scheduling techniques to optimize task execution, reduce latency, and improve scalability.

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



---

## 📄 Final Report

The full project report includes:
- Overview of scheduler logic
- Sample execution scenarios
- Tables summarizing execution time, priorities, and start/end times
- Visualization of task flow

📁[Download Report (Enhanced_AI_Task_Scheduling_Report.docx)](Report/Enhanced_AI_Task_Scheduling_Report.docx)

---

## 📂 File Structure

## 💻 Tools & Libraries

- Python 3.x
- Jupyter Notebook
- Matplotlib / Plotly (Gantt chart)
- heapq, queue
- python-docx

---

## 🤝 Contributions & Contact

Developed as part of an academic/research project.

📧 Email: harshitamahant09@gmail.com
🔗 GitHub: Harshitamahant(https://github.com/Harshitamahant)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE)


