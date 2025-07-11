


To create a Python environment (clean, isolated workspace with only the libraries you need), follow these steps using **venv** or **conda** (your choice):

---

## 🧪 **Option 1: Using `venv` (standard Python tool)**

### ✅ Requirements:

- Python 3.6+ already installed (check with `python --version`)
    

### 📦 Create Environment:

```bash
python -m venv name_of_my_env
```

> `myenv` is the name of your environment. You can name it anything.

### ▶️ Activate Environment:

- **Windows:**
    
    ```bash
    myenv\Scripts\activate
    ```
    
- **macOS/Linux:**
    
    ```bash
    source myenv/bin/activate
    ```
    

### 📥 Install Packages:

```bash
pip install xarray netCDF4 matplotlib
```

### ❌ Deactivate When Done:

```bash
deactivate
```

---

## 🐍 **Option 2: Using `conda` (if Anaconda/Miniconda is installed)**

### 🛠 Create Environment:

```bash
conda create -n myenv python=3.10
```

### ▶️ Activate Environment:

```bash
conda activate myenv
```

### 📥 Install Packages:

```bash
conda install xarray netcdf4 matplotlib
```

> Or mix with pip:

```bash
pip install extra-package
```

### ❌ Deactivate:

```bash
conda deactivate
```

---

## 🗂 Tip: Save & Share Environment

```bash
pip freeze > requirements.txt         # venv
conda env export > environment.yml    # conda
```

Let me know if you're using Windows, Linux, or macOS and whether you prefer `venv` or `conda`. I can give you a ready-to-copy setup for your system.