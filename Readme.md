<!-- ## NETFLIX EDA -->
## ⚙️ Setup & Installation
Follow the steps below to set up and run this project locally.

### 🧩 1. Clone the Repository
```bash
git clone https://github.com/Amandeep-winner/Netflix-EDA.git
cd Netflix-EDA
```

### 🐍 2. Create a Virtual Environment
It’s a best practice to use an isolated environment for each project.

For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

For macOS / Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```
### 📦 3. Install Dependencies
Install all required libraries listed in requirements.txt:
```bash
pip install -r requirements.txt
```
If you want to modify or add libraries, update requirements.in first, then re-freeze:
```bash
pip freeze > requirements.txt
```
### 🧠 4. (Optional) Register Environment as a Jupyter Kernel
To make your virtual environment appear in Jupyter Notebook:
```bash
python -m ipykernel install --user --name=netflix_eda --display-name "Python (Netflix EDA)"
```
Then, inside Jupyter, select the kernel:
Kernel → Change Kernel → Python (Netflix EDA)
### 📓 5. Launch Jupyter Notebook
Start your notebook session:
```bash
jupyter notebook
```
Open:
```bash
notebooks/netflix_analysis.ipynb
```
### 🧹 6. Deactivate the Environment (When Done)
Once you’re finished working:
```bash
deactivate
```
### 🛠️ 7. Optional – Reproducibility Tips
Freeze your environment after installing new packages:
```bash
pip freeze > requirements.txt
```
Exclude unnecessary files from Git using .gitignore:
```bash
venv/
__pycache__/
.ipynb_checkpoints/
```
For dependency visualization:
```bash
pip install pipdeptree
pipdeptree
```
### ✅ 8. You’re Ready!

Now you can explore, analyze, and visualize Netflix data.
If you face issues with library versions, recreate your environment using:
```bash
pip install -r requirements.txt
```

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-orange)
