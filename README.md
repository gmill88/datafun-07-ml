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
8. Create a new file in the root project folder names miller_ml.ipynb
9. Add markdown with project title, author, and provide a clickable link to the project repository
10. Import Dependencies
```python
import numpy as np
import pandas as pd
import pyarrow
import matplotlib.pyplot as plt
import seaborn as sns
import scipy
from scipy import stats
from  sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn import metrics
```
## Start Excercises

### Part 1 - Chart a Straight Line
- Follow Chapter 10.16 directions to plot Celsius vs Farenheit

### Part 2 - Predict Avg High Temp in NYC in January using SLR
- Acquire data
- Inspect and Clean Data
- Generate Descriptive Statistics
- Build the Model
- Predict
- Visualize

### Part 3 - Predict Avg High temp in NYC in January using Supervised machine learning
- Acquire, inspect, clean, and describe the data
- Build the Model
- Test the Model
- Predict
- Create Visualizations

### Part 4 - Add Insights
- Publish insights comparing the two methods

### Part 5 - Optional Bonus
- Load the data
- Train and Test the data
- Create visualizations of the data
- Choose the model of best fit

## References 
- https://openai.com
- Guided projects 10.16, 15.4 and 15.5 from textbook