<p align="center">
  <img src="https://github.com/rafa2403nunez-droid/PyNet/blob/main/Assets/PyNetLogo.png" width="150"/>
</p>

# PyNet Platform 🧠🐍🏗️

**PyNet Platform** is an AI-powered BIM automation ecosystem designed to bridge the gap between Natural Language, Python flexibility, and Autodesk's deterministic environment.

It operates as a dual-layer system:
1.  **The Brain (AI Layer):** An intelligent agent that translates user intent into code, executes it, and self-corrects through automated feedback loops.
2.  **The Muscle (Integration Layer):** A high-performance Python .NET framework embedded directly into Autodesk products, starting with **Navisworks** (with upcoming support for Revit and Civil 3D).

---

## 🚀 The AI-Powered BIM Loop

PyNet introduces a **closed-loop AI execution system**, turning Navisworks into an intelligent, conversational co-pilot. Unlike static plugins, PyNet learns and adapts to the specific needs of your BIM model.

### 🔄 How it works:
- **Intent:** The user requests an action in natural language (e.g., *"Find all clashes in Level 1 and export them to Excel"*).
- **Generation:** The AI generates a specialized Python script using the Navisworks API.
- **Execution:** The script is processed via the PyNet .NET listener and executed locally.
- **Self-Correction:** If a script fails, the system captures the exception. The AI analyzes the error, revises the code, and requeues it automatically.
- **Structured Results:** Final data is returned via the `ia_Result` contract, ensuring consistent and validated feedback.

---

## ✨ Key Features

* 🧠 **AI Self-Correction:** Automated debugging and iterative refinement of automation workflows.
* 🐍 **Embedded Python .NET:** Run a full Python interpreter directly inside Navisworks.
* 📚 **Data Science Ready:** Full access to libraries like `NumPy`, `Pandas`, and `Scikit-Learn` for advanced model analysis.
* 🔘 **Custom UI Engine:** Create dockable panels and link Python scripts to custom ribbon buttons for team-wide deployment.
* ⚙️ **Configurable Environment:** Define your own Python installation path and script repositories.

---

## 📽️ Video Tutorials & Guides

Master the PyNet Platform workflow with these step-by-step video resources:

| Feature | Description | Link |
| :--- | :--- | :--- |
| **Navisworks Initial Setup** | Configure Python paths and script folders | [▶️⚙️ Configuration Guide](https://www.youtube.com/watch?v=4FLbLDF3MKQ) |
| **Navisworks Scripting** | Browsing and running local Python scripts | [▶️🐍 Running Scripts](https://www.youtube.com/watch?v=IG0KOaFVKPk) |
| **Navisworks UI Management** | Creating and managing custom script buttons | [▶️📝 Management Video](https://www.youtube.com/watch?v=pHNa_wb3GwI) |

---

## 🏗️ Core Use Cases

- **Intelligent Model Interrogation:** Query complex BIM metadata using natural language.
- **Automated Clash Management:** Custom analysis pipelines beyond native Navisworks capabilities.
- **Machine Learning in BIM:** Apply ML frameworks for predictive auditing and risk assessment.
- **Rule-Based Validation:** Highly complex, Python-driven logic for BIM standard enforcement.
- **Automated Reporting:** Generate structured data outputs directly from model geometry.

---

## 📥 Installation & Getting Started

### 1️⃣ Download
PyNet is distributed through the **Autodesk App Store**. Download the installer and follow the prompts.

### 2️⃣ Configuration
Upon first launch in Navisworks (under the **RAEN Tools** tab):
* Set your local Python installation path.
* Define the folder where your Python scripts are stored.

### 3️⃣ First Execution
Browse your scripts, test their execution, and pin the most used ones to the **Custom Buttons Panel** for quick access.

---

## 🧠 Why PyNet?

Traditional scripting is often static and hard to maintain. PyNet combines **AI reasoning** with **deterministic execution**. This bridges the gap between engineering data and intelligent automation, providing a scalable, future-proof strategy for BIM Coordinators and Technical Leads.

---

## 🔒 Privacy & Security

* **Local Execution:** All Python scripts are executed within your local environment.
* **Data Sovereignty:** No BIM data is transmitted externally during script runtime.
* **Controlled AI:** While AI generates the code, the execution remains under the user's local security protocols.

---

## ⚠️ Disclaimer

PyNet is intended for professional use in BIM automation. Users are responsible for validating AI-generated scripts and ensuring results are correct before applying them to production environments. Performance depends on model size and script complexity.

---
<p align="center">
  Developed by <b>RAEN Tools</b>
</p>
