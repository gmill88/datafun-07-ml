# datafun-07-ml

## Overview
This module is designed to use machine learning to employ supervised learning and simple linear regression to train a model and use the resulting madel to make predictions.  

## Project start
1. Start a new repository and select default README.md
2. Clone the repository to local environment. I Used VS Code to clone the repository. 
3. Open the project and activate the virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```
4. Install dependencies into the .venv
```bash
python3 -m pip install pandas pyarrow jupyterlab matplotlib seaborn
```
5. Freeze dependencies into requirements.txt
 ```bash
 python3 -m pip freeze > requirements.txt
  ```
6.  Create a .gitignore using the touch command and add 
```bash
.vscode/
.venv/
.DS_Store
``` 
7. Git add, commit and push to GitHub
```bash
git add .
git commit -m "initial comment"
git push origin main   
``` 