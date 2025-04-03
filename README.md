# capstone-stonerogers
Capstone Project for M.S. Data Analytics Program

Melissa Stone Rogers, [GitHub](https://github.com/meldstonerogers/capstone-stonerogers)

## Introduction

This is a professional project exaiming trends in suicide rates over time. Data has been gathered from Center for Disease Control using
the Web-based Injury Statistics Query and Reporting System [(WISQARS)](https://wisqars.cdc.gov/about/fatal-injury-data/). 

---
## How to Install and Run the Project
**1. Create a new project repository in Github, copy the repository URL, then clone to your machine:**
```zsh
git clone project.url
```

**2. Verify Python version of Python 3:**
Mac/Linux:
```zsh
python3 --version
```

Windows: 
```shell
py --version
```
If Python 3 is not installed, install it before proceeding.

**3. Create your .venv and activate it.**
Mac/Linux:
```zsh
python3.11 -m venv .venv
source .venv/bin/activate
```

Windows: 
```shell
py -3.11 -m venv .venv
.venv\Scripts\activate
```

**4. Install the required dependencies:**
Mac/Linux:
```zsh
pip install jupyterlab pandas matplotlib scikit-learn numpy
python3 -m pip install -U scikit-learn
```

Windows: 
```shell
py -m pip install jupyterlab pandas matplotlib scikit-learn numpy
py -m pip install --upgrade scikit-learn
```

**5. Freeze Dependencies into requirements.txt** 
Mac/Linux:
```zsh
python3 -m pip freeze > requirements.txt
```

Windows: 
```shell
py -m pip freeze > requirements.txt
```

**6. Add .gitignore File**
Add .gitignore file to the root project folder if not created during repo set up.
```zsh
touch .gitignore
```
Add the following lines to ignore unnecessary files: 
- .venv/
- .vscode/
- .ipynb_checkpoints/

**7. Initial Project Save**
Enable autosave in VS Code (File > Auto Save). Push changes to GitHub frequently to effectively track changes. Update the commit message to a meaningful note for your changes. 
```zsh
git add .
git commit -m "initial project set up"                         
git push origin main
```
---
## Actual project




**Final Project Commit** 
Insure all final changes are committed to GitHub.
```zsh
git add .
git commit -m "final"                         
git push origin main
```
---
## Discussion

---


## Save Space
To save disk space, you can delete the .venv folder when not actively working on this project.
You can always recreate it, activate it, and reinstall the necessary packages later. 
Managing Python virtual environments is a valuable skill. 
