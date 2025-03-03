# Real-time Violence Detection System  

## 📌 Problem Statement  

- CCTV surveillance is widely used, but it lacks automatic violence detection features.  
- Manual monitoring is inefficient and time-consuming, delaying response times.  
- This project proposes a **real-time violence alert system** to automate detection and improve safety.  

---

## 🚀 Methodology  

1. **Dataset**:  
   - Collected **1000 videos** each of **violence** and **non-violence** categories.  
2. **Model Training**:  
   - Used **MobileNetV2** for training.  
3. **Input**:  
   - Real-time video footage.  
4. **Output**:  
   - Processed image frames with classification.  

---

## 🧠 MobileNetV2  

- A **53-layer deep** convolutional neural network (CNN).  
- Optimized for real-time classification with low computational cost.  
- Uses **inverted residual structure** for efficient processing.  
- Implements **lightweight convolutions** to improve feature extraction.  

---

## 🖥️ Operating Environment  

- **Programming Language**: Python  
- **Development Environment**: Google Colaboratory  
  - Utilizes **Google’s GPU and TPU** for model training.  

---

## 📊 Results  

- **Best Epochs**: 31  
- **Training Accuracy**: **96.17%**  
- **Training Loss**: 0.1121  
- **Test Accuracy**: **95.77%**  
- **Test Loss**: 0.1163  

### 🔍 Performance Metrics  

| Class       | Precision | Recall | F1-Score |  
|------------|------------|------------|  
| **Non-Violence** | 0.95 | 0.96 | 0.96 |  
| **Violence** | 0.96 | 0.95 | 0.96 |  
| **Accuracy** | **96%** |  
| **Macro Avg** | 0.96 | 0.96 | 0.96 |  
| **Weighted Avg** | 0.96 | 0.96 | 0.96 |  

### ✅ Predictions Summary  

- **Correct Predictions**: 4606  
- **Wrong Predictions**: 203  

---


## 📌 Future Enhancements  

- Improve accuracy with larger datasets.  
- Optimize for **edge devices** like **Raspberry Pi**.  
- Implement real-time **alerts** and **notifications**.  

---

## 📜 License  

This project is open-source and available under the **MIT License**.  

---

## 👥 Contributors  

Feel free to **contribute** by opening issues and pull requests! 🚀
