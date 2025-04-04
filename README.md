# capstone-stonerogers
Capstone Project for M.S. Data Analytics Program

Melissa Stone Rogers, [GitHub](https://github.com/meldstonerogers/capstone-stonerogers)

## Introduction

This is a professional project exaiming trends in suicide over time. Data has been gathered from Center for Disease Control using
the Wide-ranging ONline Data for Epidemiologic Research[(WONDER)](https://wonder.cdc.gov) system. 

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
pip install jupyterlab pandas matplotlib scikit-learn numpy seaborn
python3 -m pip install -U scikit-learn
```

Windows: 
```shell
py -m pip install jupyterlab pandas matplotlib scikit-learn numpy seaborn
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
## Exploratory Data Analysis
**Create a Jupyter Notebooks file to begin EDA:**
```zsh
touch your_project.ipynb
```
To run Jupyter within VS Code, use the Jupyter extension. Go to the Extensions pane on the left sidebar (the icon looks like four squares), search for "Jupyter," and install the "Jupyter" extension provided by Microsoft. If already installed, check for available updates for this extension. 

Open the newly create notebook and ceate/select the notebook kernel.

**Outline Notebook with Markdown and Code Cells:**
The following markdown cells should be included, with code cells in between.
- Import Dependencies 
- Data Acquisition
- Initial Data Inspection
- Initial Data Transformation and Feature Engineering, if needed
- Initial Descriptive Statistics 
- Initial Data Distributions
- Initial Visualizations

Verify your dataset is saved in your project folder if loading in from a static file. 

Complete the structured data exploration using the code structures noted within the eda.ipynb file. 

Make notes as needed within your REAMME.md for furture reference.

**Final EDA Commit** 
Insure all final changes are committed to GitHub.
```zsh
git add .
git commit -m "final eda"                         
git push origin main
```
---
## Predictive Modeling
**Create another Jupyter Notebooks file to begin predictive modeling:**
```zsh
touch your_project.ipynb
```
Open the newly create notebook and ceate/select the notebook kernel.

**Outline Notebook with Markdown and Code Cells:**
Outline your project with markdown cells with code cells in between. 
- Train/Test Data Split 
- Train and Evaluate Linear Regression Model 
- Train and Evaluate Random Forest Regressor
- Train and Evaluate Decision Tree Model
- Train and Evaluate Random Forest Model 
- Results

## Discussion

**Final Modeling Commit** 
Insure all final changes are committed to GitHub.
```zsh
git add .
git commit -m "final modeling"                         
git push origin main
---


## Save Space
To save disk space, you can delete the .venv folder when not actively working on this project.
You can always recreate it, activate it, and reinstall the necessary packages later. 
Managing Python virtual environments is a valuable skill. 
