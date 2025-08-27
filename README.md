# 📘 Learning Roadmap Generator

## 🚀 Project Overview
This project generates **personalized learning roadmaps** for skills like Data Science and Web Development.  
It takes inputs such as **goal, duration (months), and level (beginner/intermediate/advanced)**, and produces:  
- 📅 **Weekly timeline** with milestones  
- 📝 **Detailed tasks** and 📚 **resources** (tutorials, docs, YouTube links)  
- 📊 **Feasibility check** (estimated hours per week)  

The project is **fully extensible** – to add new domains or tasks, simply edit the JSON files (`roadmap_data.json` and `tasks_map.json`).

---

## 📂 Project Structure
📦 Roadmap-Generator
┣ roadmap_data.json 
┗ tasks_map.json 
┣ 📓 roadmap_generator.ipynb
┣ README.md
┗ requirements.txt

---

## ⚡ Features
- **Roadmap Generator** → Creates a week-by-week learning plan.  
- **Feasibility Check** → Estimates workload per week and warns if unrealistic.  
- **Extensible** → Easily add new domains, levels, and tasks via JSON.  

---

## 🛠️ Installation
1. Clone this repository:
   git clone https://github.com/amanv13/Roadmap-Generator.git
   cd Roadmap-Generator
   
3. Install dependencies:
   pip install -r requirements.txt
   
5. Open the Jupyter Notebook:
   jupyter notebook roadmap_generator.ipynb
   

## 🧪 Example Roadmaps
Example 1: Data Science (Beginner, 3 months)

📘 Weeks 1–2: Python Basics
📝 Tasks: Install Python, learn loops, write 2 scripts
📚 Resources: Automate the Boring Stuff, YouTube Tutorial

Feasibility → ~4 hrs/week ✅ Balanced

Example 2: Web Development (Beginner, 2 months)

📘 Weeks 1–2: HTML & CSS
📘 Weeks 3–4: JavaScript Basics
...

Feasibility → ~6 hrs/week ✅ Good pace

Example 3: Data Science (Intermediate, 6 months)

⚠️ Note: This looks less detailed because only beginner tasks have been filled in the JSON.
Shows that the framework is extensible – intermediate/advanced can be enriched later.

## 👨‍💻 Author

Developed by amanv13 (Aman Vatsa)
