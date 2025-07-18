

---

# 🚢 Ship Detection in Satellite Imagery

This repository contains a comprehensive deep learning project aimed at detecting ships in satellite imagery. The project leverages advanced techniques such as data augmentation, class balancing, and transfer learning to achieve high precision and recall for detecting ships.

---

## 🌟 Key Features
- **Deep Learning Models**: Iteratively developed four models, culminating in the best-performing Model 4 using MobileNetV2 and transfer learning.
- **Advanced Data Augmentation**: Applied techniques like rotations, zooms, brightness adjustments, and cropping to enhance model generalization.
- **Class Imbalance Handling**: Addressed imbalance through class weighting to emphasize the minority `Ship` class.
- **Visualization**: Detailed training progress visualizations and confusion matrices to evaluate model performance.

---

## 📂 Repository Structure
```
├── datasets/                      # Dataset directory (not included due to size)
├── notebook.ipynb                 # Main Jupyter Notebook for the project
├── final_model_4.keras            # Saved best-performing model
├── images/                        # Visual assets for documentation
│   ├── training_progress.png      # Training progress visualization
│   ├── confusion_matrix.png       # Confusion matrix example
│   ├── banner.png                 # Project banner
├── README.md                      # Project overview and documentation
```

---

## 📊 Results
### **Model 4 Performance**
- **Validation Accuracy**: 96.75%
- **Validation Loss**: 0.0971
- **Precision (Ship)**: 89.19%
- **Recall (Ship)**: 99.00%

Model 4 demonstrated strong generalization and balanced performance between precision and recall, making it suitable for real-world applications.

---

## 🛠️ Techniques Used
- **Framework**: TensorFlow/Keras
- **Architecture**: MobileNetV2 for feature extraction
- **Optimization**: Adam optimizer with a learning rate of 0.00005
- **Metrics**: Accuracy, Precision, Recall, F1-Score

---

## 🚀 How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ENKI0311/ship-detection.git
   cd ship-detection
   ```

2. **Run the Notebook**:
   - Open `notebook.ipynb` in Jupyter Notebook or Google Colab.
   - Ensure the dataset is properly linked before running.

3. **Test the Model**:
   - Load the saved model (`final_model_4.keras`) and test it on your own satellite imagery.

---

## 📈 Visual Examples
### Training Progress
![Training Progress](/cyG2Z54.png)

### Confusion Matrix
![Confusion Matrix](/tLsSoTz.png)

---

## 🛠️ Future Work
- Extend to multi-class object detection in satellite imagery (e.g., ports, airplanes).
- Deploy the model as a web API using Flask or FastAPI.
- Explore larger and more diverse datasets for further refinement.

---

## 🙌 Acknowledgments
- The dataset used for this project is sourced from [Ships in Satellite Imagery on Kaggle](https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery).

---

## 📝 License
This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.

---

## 📧 Contact
For questions or suggestions, feel free to reach out:
- **Email**: your_email@example.com
- **GitHub**: [YourUsername](https://github.com/ENKI0311)

---





