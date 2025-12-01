# GeneralStudyAI-Kaggle-Capstone
Agentic Multi-Subject Study Planner submitted to the Kaggle Agents Intensive Hackathon.
# 🤖 GeneralStudyAI: Agentic Multi-Subject Study Planner

## 🏆 Kaggle Agents Intensive - Capstone Project
This project implements a simple multi-agent system designed to act as a **personalized study planner** and **concierge agent**. It addresses the common challenge students face in manually organizing complex, multi-subject study schedules and finding quick answers to basic academic doubts.

**Submission Link**: [View the Original Kaggle Submission Notebook Here](<-- PASTE YOUR PUBLIC KAGGLE URL HERE -->)

## ✨ Core Agent Architecture

GeneralStudyAI utilizes a flow of three distinct Python class-based agents that leverage a shared memory system:

| Agent Name | Functionality | Key Output |
| :--- | :--- | :--- |
| **PlanningAgent** | Generates a 7-day, day-wise study schedule across the user's defined subjects (e.g., Math, Physics, Computer Science). | Structured JSON study plan. |
| **TaskAgent** | Takes a planned subject and suggests a specific, actionable task along with curated, relevant learning resources. | Specific task (e.g., "Complete 10 problems") and resource links. |
| **DoubtAgent** | Provides quick, explanatory answers to user-submitted academic questions, simulating immediate doubt resolution. | Simulated answer and explanation. |

### Memory & Observability
All agents interact with a central `MemoryBank` to track execution logs, store user profiles (subjects, level, hours available), and maintain continuity across the planning and study phases.

## 💻 Repository Contents

This repository contains the complete code and write-up submitted for the hackathon.

* `notebookfbdb01370d.ipynb`: The primary Jupyter Notebook containing all the code for the agent framework, tools, memory, and the multi-agent execution example.
* `README.md`: This document.
* The system generates artifacts such as `memory.json` (agent state) and `VIDEO_SCRIPT.txt` (for the required submission video).

## ▶️ How to Run the Project
1.  Clone this repository.
2.  Open the `notebookfbdb01370d.ipynb` file in a Jupyter environment (like Kaggle, Colab, or local VS Code).
3.  Run all cells sequentially.
4.  The output will display the generated study plan, a specific task with resources, and the simulated doubt resolution.

5.  View the Original Kaggle Submission Notebook Here:https://www.kaggle.com/code/skpragadeeswar/notebookfbdb01370d
