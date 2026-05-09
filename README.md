# Customer Churn Prediction

## 一、專案簡介

本專案使用電信客戶資料建立 Customer Churn Prediction 模型，透過機器學習分析客戶流失行為，預測高風險流失客戶，並提出商業策略建議。

專案內容涵蓋資料清理、探索性資料分析（EDA）、特徵工程、模型建構、模型評估與商業洞察分析。

---

## 二、資料集欄位

資料包含：

- 客戶基本資訊
- 合約類型
- 月費與總消費
- 地理資訊
- 客戶流失資訊

---

## 三、使用技術

- Python
- Pandas / NumPy
- scikit-learn
- Matplotlib / Seaborn

---

## 四、探索性資料分析（EDA）

### 發現：

- Month-to-month 合約客戶流失率較高
- Monthly Charges 較高的客戶較容易流失
- Tenure Months 較短的客戶較不穩定

---

## 五、模型建構

### 使用模型：

1. Logistic Regression
2. Random Forest

---

## 六、模型評估

使用：

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

作為模型評估指標。

### 模型結果：

| Model | ROC-AUC |
|---|---|
| Logistic Regression | 0.85 |
| Random Forest | 0.85 |

---

## 七、Feature Importance

模型顯示以下特徵對 churn prediction 最重要：

- Total Charges
- Tenure Months
- Monthly Charges

---

## 八、商業洞察

### 高風險流失族群：

- 月費較高客戶
- 使用時間較短客戶
- Month-to-month 合約客戶

### 商業建議：

- 提供長期合約優惠
- 計畫增加高風險客戶黏著度

---
