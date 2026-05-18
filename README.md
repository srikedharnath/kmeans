# kmeans


# Student Performance Clustering using K-Means

This project uses the K-Means Clustering algorithm to group students based on their academic performance and attendance behavior.

---

# Project Type

Unsupervised Machine Learning

Algorithm Used:
- K-Means Clustering

---

# Dataset Used

Student Performance Dataset

The dataset contains student academic, social, and behavioral information.

---

# Features Used

The following important features were selected for clustering:

- studytime
- failures
- absences
- G1
- G2
- G3

These features help identify:
- high-performing students
- average students
- low-performing students

---

# Data Preprocessing

The following preprocessing steps were performed:

- Selected important numerical columns
- Removed outliers using IQR method
- Applied feature scaling using StandardScaler

---

# Clustering Process

## Step 1 — Feature Scaling

Data was standardized using StandardScaler.

## Step 2 — Elbow Method

The Elbow Method was used to determine the optimal K value.

## Step 3 — Model Training

K-Means clustering was trained using:

```python
KMeans(
    n_clusters=3,
    random_state=42
)
