# 🐍 Conda Commands Cheat Sheet

🚀 A **comprehensive Conda cheat sheet** covering environment management, package installations, and system configurations. Perfect for developers, data scientists, and AI researchers!

---

## 📖 Features

✅ **Create & Remove Environments** (by name or custom path)  
✅ **Export & Recreate Environments** from YAML files  
✅ **Activate, Deactivate & List Environments**  
✅ **Install, Update & Remove Packages**  
✅ **Clone, Clean & Configure Conda Environments**  

---

## 📂 File Structure

- **`conda-commands.md`** → Contains all Conda commands neatly categorized.  
- **`README.md`** → This file, explaining features & usage.  
- **`LICENSE`** → Open-source license for this project.  

---

## 🚀 Quick Start Guide

### 🔹 **1. Create a Conda Environment**
```sh
conda create --name my_env python=3.9
```

### 🔹 **2. Activate & Deactivate Environment**
```sh
conda activate my_env
conda deactivate
```

### 🔹 **3. Export Environment to YAML**
```sh
conda env export -n my_env > environment.yaml
```

### 🔹 **4. Create an Environment from YAML**
```sh
conda env create -f environment.yaml
```

---

## 📜 Full Conda Commands List
For a **detailed list of Conda commands**, check out [`conda-commands.md`](./conda-commands.md).

---

## 🌟 Contribute
Have a suggestion or an improvement? Feel free to open an [issue](https://github.com/your-username/conda-commands-cheatsheet/issues) or submit a pull request!

---

## 📄 License
This project is open-source and licensed under the **MIT License**.
