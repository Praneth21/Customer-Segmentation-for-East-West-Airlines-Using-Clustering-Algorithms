# ✈️ Airline Customer Segmentation – Clustering Analysis

## 📌 Objective
Segment frequent flyers of EastWest Airlines using clustering algorithms to inform marketing decisions like loyalty programs, targeted bonuses, and premium upgrades.

---

## 📁 Dataset
- Name: EastWestAirlines.csv
- Records: 3,999 flyers
- Features: Balance, flight miles, bonus miles, number of transactions, etc.

---

## 🧪 Methods Used

### 🔹 1. Data Preprocessing
- Normalized all numerical columns
- Removed `ID` for clustering

### 🔹 2. Hierarchical Clustering
- Distance: Euclidean
- Linkage: Ward’s method
- Dendrogram used to cut into **4 clusters**

### 🔹 3. K-Means Clustering
- k = 4
- Compared output with hierarchical results
- Stability test with 95% resample

---

## 🧠 Business Interpretation

| Cluster | Characteristics | Strategy |
|---------|------------------|----------|
| Cluster 1 | Low miles, low bonus, few transactions | Low-engagement flyers – low priority |
| Cluster 2 | High balance, high bonus, many flights | High-value loyalists – target with upgrades |
| Cluster 3 | Mid-high miles and transactions | Stable customers – retention focus |
| Cluster 4 | Moderate activity, potential to grow | Promote engagement with seasonal offers |

---

## 📊 Visuals (Optional)

| Visual | Description |
|--------|-------------|
| Dendrogram | Hierarchical cluster split |
| Cluster Means Barplot | Cluster-wise comparison |
| PCA Cluster Map | Optional 2D visualization |

---



