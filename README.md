# Signal-vs-Background-Classification-in-Higgs-Boson-Detection-using-Machine-Learning

This project implements machine learning and deep learning algorithms to classify particle collision events as signal (Higgs boson events) or background (Standard Model processes). The goal is to enhance the signal-to-background ratio in high-energy physics experiments using data-driven methods.

**Project Description:**

In particle physics, detecting rare events like the Higgs boson involves separating meaningful signal from overwhelming background noise. Traditional rule-based approaches often rely on handcrafted features and threshold filters. This project leverages supervised learning models trained on high-dimensional Monte Carlo simulation data to automate and improve this classification.

**Datasets used:**

We utilize three large-scale, Monte Carlo-simulated datasets from the UCI repository:

  a. HIGGS: 11M events, 28 features (kinematic and derived)
  
  b. SUSY: 5M events, 18 features
  
  c. HEPMASS: ~10.5M events, 27 features, mass-dependent subsets

**Models used:**

  a. Logistic Regression (LR)
  
  b. Support Vector Machine (SVM)
  
  c. Random Forest (RF)
  
  d. XGBoost
  
  e. Neural Networks (Deep Learning)

