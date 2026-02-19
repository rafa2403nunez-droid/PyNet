<p align="center">
  <img src="https://github.com/rafa2403nunez-droid/PyNet/blob/main/Assets/PyNetLogo.png" width="150"/>
</p>

# PyNet 🐍🖥️

**PyNet** is a Python .NET integration framework designed to embed Python scripting capabilities directly into Autodesk products.  

The goal of PyNet is to provide a unified, extensible foundation for Python-based automation across multiple Autodesk platforms, including **Navisworks**, **Revit**, and **Civil 3D**. Each implementation adapts PyNet to the specific API and workflows of the host application while sharing the same core principles and architecture.  

This repository currently focuses on the **Navisworks** implementation of PyNet.  

PyNet is intended for advanced users, BIM coordinators, computational designers, and technical professionals who want to extend Autodesk functionality using Python.

---

## ✨ Features

* 🐍 Embedded Python .NET interpreter inside Navisworks  
* ▶️ Execute Python scripts directly within the application  
* 🔘 Create custom buttons linked to scripts for quick access  
* 🗂️ Dockable panel to organize and run custom script buttons  
* ⚙️ Configurable script folder and Python installation path  
* 🎛️ Clean integration with the Navisworks ribbon interface  

---

## 📝 Requirements

* Autodesk Navisworks (supported versions depend on the release)  
* A local Python installation compatible with Python .NET  
* Basic knowledge of Python scripting and Navisworks workflows  

---

## 📥 Installation

Navisworks PyNet is distributed through the Autodesk App Store.  

1. Download and install the application from the Autodesk App Store.  
2. Launch Autodesk Navisworks.  
3. The **RAEN Tools** ribbon tab will be available after installation.  

### 🗑️ Uninstallation

* Open Windows **Apps & Features** or **Programs and Features**  
* Locate *Navisworks PyNet* and uninstall it like any other application  

---

## 🚀 Getting Started

### 1️⃣ Configuration

Before running scripts, open the **Configuration** command from the ribbon:  

* Set the folder used to browse Python scripts  
* Define the path to the user’s Python installation  
* Manage existing custom script buttons  

This step is required to ensure scripts execute correctly.

[▶️⚙️Configuration Video ](https://www.youtube.com/watch?v=4FLbLDF3MKQ)

---

### 2️⃣ Browsing and Running Scripts

Use **Browse Scripts** to:  

* 🖱️ Browse Python script files  
* ▶️ Execute scripts directly inside Navisworks  
* 🔘 Create custom buttons linked to selected scripts for quick access  

Scripts are executed locally and can interact with the Navisworks API through Python.  

---

### 3️⃣ Custom Buttons Panel

Use **Show Buttons** to display a dockable panel containing all custom script buttons:  

* 🔘 Each button executes its associated Python script  
* 🗂️ Buttons can be organized and managed through the configuration dialog  
* 📌 The panel can be docked or hidden to fit different workflows  

---

## 💡 Why PyNet

PyNet bridges Python and .NET, enabling advanced use cases far beyond traditional scripting:  

* 📚 **Full access to Python libraries** – NumPy, Pandas, SciPy, and more  
* 🤖 **Machine Learning workflows** – Python-based ML frameworks for model analysis or automation logic  
* 🔄 **Generative design and computational workflows** – combine Python algorithms with Autodesk APIs  
* 📊 **Dashboards and data visualization** – leverage Python visualization frameworks to drive decision-making  

Unlike isolated scripting solutions, PyNet allows Python to operate as a first-class citizen within Autodesk applications, combining:  

* 🐍 Python flexibility and ecosystem  
* ⚡ .NET performance and API access  
* 🏗️ Native integration with Autodesk products  

This enables scalable, future-proof automation strategies that evolve alongside both Python and Autodesk platforms.  

---

## 🛠️ Workflow Overview

A typical workflow using PyNet:  

1. ⚙️ Configure Python path and script folder  
2. 🖱️ Browse and test Python scripts  
3. 🔘 Create custom buttons for frequently used scripts  
4. ▶️ Execute scripts directly from the dockable buttons panel  

This makes automation a seamless part of the daily Autodesk workflow.  

---

## ⚠️ Limitations and Notes

* 🕒 Script execution performance depends on script complexity and model size  
* ❌ Scripts containing errors may raise runtime exceptions  
* 🐞 Advanced debugging tools are not included in the current version  
* ✅ Users are responsible for validating scripts before using them in production  

---

## 🔒 Privacy and Data Usage

Navisworks PyNet does **not** collect, store, or transmit personal or confidential data.  

All scripts are executed locally within the user’s environment. No external servers or third-party services are contacted.  

---

## 🆘 Support

Support is provided on a best-effort basis.  

When requesting support, please include:  

* 🏷️ Navisworks version  
* 🔢 Navisworks PyNet version  
* 📝 A clear description of the issue  
* 🛠️ Steps to reproduce the problem  

---

## 📜 License

The license information for this project should be reviewed before use. Users are responsible for ensuring compliance with all applicable licensing and legal requirements.  

---

## ⚠️ Disclaimer

This project is intended for professional and educational use. Users assume all responsibility for scripts executed using this extension and for validating results produced within Navisworks.  

