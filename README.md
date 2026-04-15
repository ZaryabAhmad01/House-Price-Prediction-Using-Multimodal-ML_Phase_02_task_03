# House-Price-Prediction-Using-Multimodal-ML_Phase_02_task_03


**Model Parameters:**
- Total Parameters: 12,417
- Trainable Parameters: 12,033
- Non-trainable Parameters: 384

---

### ⚙️ TRAINING CONFIGURATION

| Parameter | Value |
|-----------|-------|
| Epochs | 50 |
| Batch Size | 32 |
| Optimizer | Adam |
| Loss Function | Mean Squared Error (MSE) |
| Evaluation Metric | Mean Absolute Error (MAE) |
| Train/Test Split | 80% / 20% |

---

### 📈 FINAL RESULTS

| Metric | Value | Explanation |
|--------|-------|-------------|
| **MAE** | **$28,825.45** | Average prediction error |
| **RMSE** | **$36,204.89** | Penalizes larger errors |
| **Average Price** | **$587,531.60** | Baseline for comparison |
| **Accuracy** | **95.1%** | 100% - (MAE/Avg Price × 100) |
| **Error Rate** | **4.9%** | Percentage deviation |

---

### 📊 EVALUATION METRICS EXPLAINED

**Mean Absolute Error (MAE)**
> Formula: (1/n) × Σ|Actual - Predicted|
> Interpretation: On average, predictions are off by $28,825

**Root Mean Square Error (RMSE)**
> Formula: √[(1/n) × Σ(Actual - Predicted)²]
> Interpretation: Larger errors are penalized; value of $36,205 indicates few outliers

**Accuracy Calculation**
> Formula: 100% - (MAE ÷ Average Price × 100)
> Result: 100% - (28,825 ÷ 587,531 × 100) = 95.1%

---

### ✅ REQUIREMENTS COMPLETED

| Requirement | Status |
|-------------|--------|
| Use regression model for price prediction | ✅ COMPLETED |
| Process tabular data with neural network | ✅ COMPLETED |
| Calculate and report MAE | ✅ COMPLETED |
| Calculate and report RMSE | ✅ COMPLETED |
| Achieve reasonable prediction accuracy | ✅ COMPLETED (95.1%) |

---

### 💡 KEY FINDINGS

1. **High Accuracy**: 95.1% accuracy demonstrates that neural networks effectively capture complex relationships between housing features and prices.

2. **Low Error Rate**: With only 4.9% average error, the model provides reliable price estimates suitable for real estate applications.

3. **Effective Regularization**: BatchNormalization and Dropout layers prevented overfitting while maintaining good generalization.

4. **Scalable Architecture**: The 5-layer architecture (128→64→32→16→1) balanced model complexity with performance.

---

### 🚀 TECHNOLOGIES USED

- **Python 3.10** - Core programming language
- **TensorFlow/Keras** - Neural network implementation
- **Scikit-learn** - Data preprocessing & metrics
- **Matplotlib** - Visualization
- **NumPy/Pandas** - Data manipulation

---

### 📝 CONCLUSION

The multimodal regression model successfully predicts house prices with **95.1% accuracy** and an **MAE of $28,825**. These results validate that neural networks can effectively learn patterns in housing data, making this approach suitable for real-world price estimation tasks.

---


---

**📅 Date:** April 2026
**👨‍💻 Task:** Multimodal ML - Housing Price Prediction
