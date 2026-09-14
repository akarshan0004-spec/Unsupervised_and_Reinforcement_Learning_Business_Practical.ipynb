# Unsupervised & Reinforcement Learning — Business AI Practical

> A business-focused machine learning practical demonstrating customer segmentation with K-Means clustering and the fundamentals of Reinforcement Learning through a delivery-route optimization scenario.

---

## 📌 Project Overview

This project demonstrates how machine learning techniques can be applied to practical business decision-making.

The practical focuses on two important areas of Machine Learning:

1. **Unsupervised Learning** — discovering hidden customer segments using K-Means Clustering.
2. **Reinforcement Learning** — understanding how an intelligent system can learn from actions and rewards through a delivery-route example.

The project is designed with a business-first perspective, emphasizing not only model implementation but also the interpretation of machine learning outputs for decision-making.

---

## 🎯 Objectives

- Understand customer segmentation using K-Means Clustering.
- Identify groups of customers with similar spending and engagement behavior.
- Interpret clustering results from a business perspective.
- Understand the fundamental workflow of Reinforcement Learning.
- Identify the Agent, Environment, Action, and Reward.
- Understand Exploration vs. Exploitation.
- Connect Machine Learning concepts with real-world business applications.

---

## 🧠 Machine Learning Concepts

### Unsupervised Learning

The project uses **K-Means Clustering** to segment customers based on:

- Monthly Spending
- App Visits

The model is configured with:

```python
KMeans(
    n_clusters=3,
    random_state=42,
    n_init=10
)
