<p align="center">
  <img src="https://github.com/rafa2403nunez-droid/PyNet/blob/main/Assets/PyNetLogo.png" width="150"/>
</p>

# PyNET Platform 🧠🐍

**PyNET Platform** is an AI-driven BIM automation platform that connects natural language, Python execution, and Autodesk Navisworks into a unified workflow.

### PyNET Platform Ecosystem

PyNET platform use the following Ecosistem to automate BIM tasks using AI.

<p align="center">
  <img src="https://github.com/rafa2403nunez-droid/PyNet/blob/main/Assets/PyNetPlatformStructure.png" width="1000"/>
  <br>
  
</p>

| Component | Repository | Purpose |
| :--- | :--- | :--- |
| **PyNet Platform** | [rafa2403nunez-droid/PyNet](https://github.com/rafa2403nunez-droid/PyNet) | Navisworks/Revit/Civil 3D plugin that hosts the Python.NET engine providing UI Layer and AI integration with BIM Models |
| **PyNet Bridge (MCP)** | [rafa2403nunez-droid/PyNetBridge](https://github.com/rafa2403nunez-droid/PyNetBridge) | MCP server that connects AI models to PyNET with including secure scripts validation |
| **PyNet Library** | [rafa2403nunez-droid/PyNetLibrary](https://github.com/rafa2403nunez-droid/PyNetLibrary) | Python Scripts reference library for Revit, Navisworks and Civil 3D and AI context|


---

## ✨ FEATURE HIGHLIGHT: 🤖 AI Integration

This example demonstrates how an AI model translates natural language into executable Python .NET scripts in real time.

> **Watch how PyNET transforms Natural Language into complex Navisworks scripts in real-time.**

[▶️🤖 PyNET Claude Integration](https://www.youtube.com/watch?v=2uHfR1x1DQk)

*In this showcase, we demonstrate the core power of the platform: using Claude AI as a co-pilot to translate user intent into high-performance Python .NET code.*

---

## 🚀 The AI-Powered BIM Loop

**PyNET Platform** introduces a closed-loop AI-assisted execution system, turning Navisworks into an intelligent, conversational co-pilot. Unlike static plugins, PyNET Platform learns and adapts to the specific needs of your BIM model.

### 🔄 How it works:
* **Intent:** The user requests an action in natural language (e.g., *"Find all clashes in Level 1 and export them to Excel"*).
* **Generation:** The AI generates a specialized Python script using the Navisworks API.
* **Execution:** The script is processed via the PyNET Platform .NET listener and executed locally.
* **Self-Correction:** If a script fails, the system captures the exception and can optionally feed the error back to the AI for iterative correction, depending on the configured workflow.
* **Structured Results:** Final data is returned via the `ia_Result` contract, ensuring consistent and validated feedback.

---

## ✨ Key Features

* 🧠 **AI Self-Correction:** Automated debugging and iterative refinement of automation workflows.
* 🐍 **Embedded Python .NET:** Run a full Python interpreter directly inside Navisworks.
* 📚 **Data Science Ready:** Supports integration with libraries such as NumPy, Pandas, and Scikit-Learn for advanced data processing and analysis.
* 🔘 **Custom UI Engine:** Create dockable panels and connect Python scripts to custom ribbon buttons for deployment within Navisworks.
* ⚙️ **Configurable Environment:** Define your own Python installation path and script repositories.

---

## 📽️ Video Tutorials & Guides

Master the PyNET Platform workflow with these step-by-step video resources:

| Feature | Description | Link |
| :--- | :--- | :--- |
| **Navisworks Initial Setup** | Configure Python paths and script folders | [▶️⚙️ Configuration Guide](https://www.youtube.com/watch?v=4FLbLDF3MKQ) |
| **Navisworks Scripting** | Browsing and running local Python scripts | [▶️🐍 Running Scripts](https://www.youtube.com/watch?v=IG0KOaFVKPk) |
| **Navisworks UI Management** | Creating and managing custom script buttons | [▶️📝 Management Video](https://www.youtube.com/watch?v=pHNa_wb3GwI) |

---

## 🏗️ Core Use Cases

* **Intelligent Model Interrogation:** Query complex BIM metadata using natural language.
* **Automated Clash Management:** Custom analysis pipelines beyond native Navisworks capabilities.
* **Machine Learning in BIM:** Apply ML frameworks for predictive auditing and risk assessment.
* **Rule-Based Validation:** Highly complex, Python-driven logic for BIM standard enforcement.
* **Automated Reporting:** Generate structured data outputs directly from model geometry.

---

## 📥 Installation & Licensing

### 1️⃣ Availability
PyNET Platform will be distributed via the Fremius platform to ensure secure licensing and controlled access.
> ⚠️ **Status:** The platform is currently in final review and is not yet publicly available.

<p align="center">
  <img src="https://github.com/rafa2403nunez-droid/PyNet/blob/main/Assets/PyNETPlans.png" width="500"/>
</p>

### 2️⃣ Configuration
Upon first launch in Navisworks (under the **RAEN Tools** tab):
* Activate your license via the secure activation window.
* Set your local Python installation path.
* Define the folder where your Python scripts are stored.

---

## 🤖 AI Integration via MCP (Model Context Protocol)

PyNET Platform connects to AI models through **[PyNet Bridge](https://github.com/rafa2403nunez-droid/PyNetBridge)**, an MCP server that exposes PyNET tools to compatible AI clients.

This allows AI systems to generate and execute scripts that interact directly with Navisworks, Revit, and Civil 3D.

### ⚡ One-line install

> ⚠️ **Prerequisites:** Python must be installed on your system (3.10 to 3.13). **Python 3.14 is not yet supported** — the `pythonnet` runtime currently supports Python 3.7 through 3.13. For VS Code extensions (Claude Code, Cline, Roo Code), **Git** must also be installed → [git-scm.com](https://git-scm.com/downloads). For detailed instructions and requirements, see the [PyNet Bridge repository](https://github.com/rafa2403nunez-droid/PyNetBridge).

Open PowerShell and run:

```powershell
irm https://raw.githubusercontent.com/rafa2403nunez-droid/PyNetBridge/main/install.ps1 | iex
```

This installs the MCP server and auto-detects all supported AI clients:
- **Claude Desktop** (standard and Microsoft Store)
- **Claude Code** (VS Code extension / CLI)
- **Cline** (VS Code extension)
- **Roo Code** (VS Code extension)

> For manual setup or other clients, see the [PyNet Bridge repository](https://github.com/rafa2403nunez-droid/PyNetBridge).

**Important Note on AI Providers:**
PyNET Platform acts as the integration bridge between AI models and Autodesk tools. **Access to AI models (such as Claude AI, OpenAI, etc.) is not included with the tool.** Users must provide their own integration or use the platform to bridge their existing AI workflows into the Autodesk ecosystem. PyNET Platform is the engine that enables these AIs to "understand" and "operate" Navisworks, Revit, and Civil 3D.

---

## 🔒 Privacy & Security

* **Local Execution:** All Python scripts are executed within your local environment.
* **Data Sovereignty:** No BIM data is transmitted externally during script runtime.
* **Controlled AI:** While AI generates the code, the execution remains under the user's local security protocols.
* **AI-generated code** may be processed by external AI providers depending on the user's chosen integration.

---

## ❓ FAQs

Have questions about installation, configuration, or usage? Check the full FAQ page:

👉 [PyNet FAQs](https://github.com/rafa2403nunez-droid/PyNet/wiki/FAQs)

---

## ⚠️ Disclaimer

PyNET Platform is intended for professional use in BIM automation. Users are responsible for reviewing, validating, and ensuring the correctness of AI-generated scripts before applying them in production environments.

---

<p align="center">
  Developed by <b>RAEN Digital Tools</b>
  <br/><br/>
  <img src="https://github.com/rafa2403nunez-droid/PyNet/blob/main/Assets/RAENDigitalTools.png" alt="RAEN Digital Tools" width="200">
</p>
