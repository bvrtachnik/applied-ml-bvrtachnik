# Mushroom Classification - Brett Vrtachnik

## Overview
This project applies classification modeling techniques to predict whether a mushroom is edible or poisonous based on physical characteristics. The dataset, sourced from the UCI Machine Learning Repository, contains entirely categorical features, which were encoded and used to train two classifiers: a Decision Tree and a Random Forest.

## Notebook
[Click here to open the notebook](https://github.com/bvrtachnik/applied-ml-bvrtachnik/blob/main/midterm/classification_bvrtachnik.ipynb)

## Peer Review
[Click here to view the peer review](https://github.com/bvrtachnik/applied-ml-bvrtachnik/blob/main/midterm/peer_review.md)

## Dataset
- **Source:** UCI Mushroom Dataset
- **Target Variable:** `class` (0 = edible, 1 = poisonous)
- **Selected Features:** `odor`, `gill-color`

## Models Used
- **Decision Tree Classifier**
- **Random Forest Classifier**

# Project Setup

## Project Initialization

### Create a GitHub Repository
- Create a new repo on GitHub and add a default README.

### Clone the Repository
```shell
git clone [your-repo-url]
cd [cloned-repo]
```

### Add `.gitignore` and `requirements.txt` Files
- Add `.gitignore` and `requirements.txt` to the project.

### Create and Activate a Virtual Environment
```shell
python -m venv .venv
.\.venv\Scripts\Activate
```

### Upgrade Pip, Setuptools, and Wheel
```shell
py -m pip install --upgrade pip setuptools wheel
```

### Install Dependencies
```shell
pip install -r requirements.txt
```

### Track and Push Changes with Git
```shell
git add .
git commit -m "Initial commit"
git push origin main
```

### 4. Launch the Notebook
```bash
jupyter notebook classification_bvrtachnik.ipynb
```




