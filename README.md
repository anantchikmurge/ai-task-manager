# AI-Powered Task Management System

## Overview
An intelligent task management system leveraging NLP and Machine Learning to automatically classify, prioritize, and assign tasks based on user behavior, deadlines, and workloads.

---

## Features
- Task description preprocessing using NLP (tokenization, stemming, stopword removal).
- Task classification with Naive Bayes and SVM.
- Priority prediction using Random Forest and XGBoost.
- Workload balancing logic for efficient task assignment.
- Hyperparameter tuning with GridSearchCV.
- Dashboard mockup for task summaries and performance metrics.

---

## Dataset
- Synthetic task dataset used for training and evaluation.
- APIs like Trello and Jira considered for future data collection.

---

## Installation & Setup

```bash
# Clone repo
git clone https://github.com/anantchikmurge/ai-task-manager.git

# Navigate to folder
cd ai-task-manager

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate    # Linux/macOS
venv\Scripts\activate       # Windows

# Install dependencies
pip install -r requirements.txt
# ai-task-manager