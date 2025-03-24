# 🐍 Conda Command Guide

This document provides a comprehensive list of Conda commands to manage environments, packages, and configurations. 🚀

---

## 📌 Creating a Conda Environment

### 🔹 Using Name
```bash
conda create --name <env-name>
conda create -n <env-name>
```

### 🔹 Using Path
```bash
conda create --prefix <custom-path/env>
cd <custom-path> && conda create --prefix ./env
conda create -p <custom-path/env>
cd <custom-path> && conda create -p ./env
```

---

## ❌ Removing a Conda Environment

### 🔹 Using Name
```bash
conda env remove --name <env-name>
conda env remove -n <env-name>
```

### 🔹 Using Path
```bash
conda env remove --prefix <custom-path/env>
cd <custom-path> && conda env remove --prefix ./env
conda env remove -p <custom-path/env>
cd <custom-path> && conda env remove -p ./env
```

---

## 📤 Exporting an Environment (YAML File)
```bash
conda env export --name <env-name> > environment.yaml
conda env export -n <env-name> > environment.yaml
```

💡 *Exporting an environment allows replication on another machine!*

---

## 📥 Creating an Environment from YAML File
```bash
conda env create -f environment.yaml
```

### 🔹 With a Custom Name
```bash
conda env create --name <env-name> -f environment.yaml
conda env create -n <env-name> -f environment.yaml
```

---

## 🔄 Activating & Deactivating Environments

### ✅ Activate an Environment
```bash
conda activate <env-name>
conda activate /path/to/custom/env
```

### ❎ Deactivate the Current Environment
```bash
conda deactivate
```

---

## 📋 Listing Available Environments
```bash
conda env list
conda info --envs
```

---

## 📦 Viewing Installed Packages
```bash
conda list -n <env-name>
conda list -p /path/to/custom/env
conda list
conda list | grep <package-name>
```

---

## ⬇️ Installing & Updating Packages

### 🔹 Install a Package
```bash
conda install -n <env-name> <package-name>
conda install -p /path/to/custom/env <package-name>
```

### 🔹 Install from a Specific Channel
```bash
conda install -c conda-forge <package-name>
```

### 🔹 Update a Package
```bash
conda update -n <env-name> <package-name>
conda update --all -n <env-name>
```

---

## ❌ Uninstalling Packages
```bash
conda remove -n <env-name> <package-name>
conda remove -p /path/to/custom/env <package-name>
```

---

## 🔁 Cloning an Existing Environment
```bash
conda create --name <new-env-name> --clone <existing-env-name>
conda create --prefix /path/to/custom/env --clone <existing-env-name>
```

---

## 🧹 Cleaning Up Conda (Freeing Space)
```bash
conda clean --all
conda clean --packages
conda clean --tarballs
conda clean --tempfiles
```

---

## ⚙️ Checking Conda Configuration & Info
```bash
conda --version
conda config --show
conda info
conda info -n <env-name>
```

---

✨ **Happy Coding with Conda!** 🐍🔥
