🧠 Smart Task Planner
🔍 Overview

The Smart Task Planner is an AI-powered system that breaks down a user’s goal into actionable tasks with timelines, dependencies, and recommendations.
It helps users move from high-level goals like “Launch a product in 2 weeks” to detailed, structured action plans using intelligent reasoning.

🎯 Objective

Break user goals into actionable tasks with suggested timelines and dependencies using AI reasoning.

⚙️ Features

📝 Goal Input – Enter any goal (e.g., Build a website in 10 days).

🤖 AI Planning Engine – Uses LLM reasoning to break down the goal into structured tasks.

⏱️ Timeline Estimation – Suggests deadlines based on the complexity of tasks.

🌐 Frontend Interface – Simple HTML + Tailwind UI for submitting goals and viewing results.

🔄 Modes Supported

Auto: Default mode, uses best available reasoning.

Local: Uses local AI model for offline inference.

OpenAI: Connects with OpenAI API for higher reasoning quality.

🧩 Tech Stack
Layer	Technology
Frontend	HTML, Tailwind CSS, JavaScript
Backend	FastAPI (Python)
AI Engine	LLM Reasoning (Local/OpenAI-based)
Environment	Jupyter Notebook / API Deployment
🧠 LLM Usage Guidance

Prompt Example:

“Break down this goal into actionable tasks with suggested deadlines and dependencies.”

🚀 How to Run
1️⃣ Backend Setup

Install dependencies:

pip install fastapi uvicorn openai


Run the FastAPI server:

uvicorn app:app --reload


(Ensure the /generate_plan endpoint is implemented in your backend file)

2️⃣ Frontend Setup

Open indexx.html in your browser.

Enter your goal and select the mode (Auto/Local/OpenAI).

Click “Generate Plan” to view the AI-generated task breakdown.

📂 Project Structure
Smart_Task_Planner/
│
├── smart_task_planner.ipynb     # Core AI logic & backend prototype
├── indexx.html                  # Frontend UI
├── _Smart Task Planner_13.pdf   # Project documentation
├── README.md                    # (This file)

🧾 Example Usage

Input Goal:

"Launch a new mobile app in 3 weeks"

Output:

<img width="959" height="785" alt="image" src="https://github.com/user-attachments/assets/3518cad4-0d61-4c4e-9456-36a2a86d5f43" />

📹 Deliverables

✅ GitHub repository (with README)

🎥 Demo video showcasing goal input → plan generation

🧠 Clear documentation of reasoning and design

