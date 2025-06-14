# MS_Final

---

# 專案簡介：學生期末成績預測模型

本專案旨在透過學生的學習習慣、生活行為與家庭背景等資料，預測其期末考試成績。透過建構回歸模型，不僅能提升教育單位對學生成績的掌握能力，也能協助識別學業表現風險並提供介入建議。

---

## 專案目標

- 了解各種學習與背景因素對成績的影響程度  
- 建立可解釋的期末成績預測模型  
- 探討特徵變數的重要性，協助教育決策  

---

# Dataset Variables and Assumptions

| Variable Name        | Value Range / Categories      | Assumptions / Notes                                                                 |
|----------------------|-------------------------------|--------------------------------------------------------------------------------------|
| `hours_studied`      | 1–44                          |                                                                                      |
| `sleep_hours`        | 4–10                          |                                                                                      |
| `previous_scores`    | 50–100                        |                                                                                      |
| `family_income`      | Low, Medium, High             | Encoded with two dummy variables:<br>Low = (0, 0), High = (1, 0), Medium = (0, 1)     |
| `attendance`         | 60–100                        | Percentage                                                                           |
| `Distance_from_Home` | Near, Moderate, Far           | Encoded with two dummy variables:<br>Near = (0, 0), Moderate = (1, 0), Far = (0, 1)   |
| `Exam_Score`         | Final Exam Score (numeric)    | Dependent variable                                                                   |


## 使用工具

- **Python 3**
- **Pandas / NumPy**：資料處理  
- **Scikit-learn**：回歸模型建構  
- **Gurobi**（可選）：進階最佳化預測模型實作  

---

## 數據資料集：https://www.kaggle.com/datasets/lainguyn123/student-performance-factors/data  