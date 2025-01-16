# Plant Disease Classification Project

This project focuses on identifying crop diseases using the PlantVillage dataset. The task is a multiclass classification problem involving 39 distinct plant disease categories.

## 🌱 Dataset

- **Source**: [PlantVillage Dataset](https://data.mendeley.com/datasets/tywbtsjrjv/1)
- **Details**:
  - **Classes**: 39
  - **Total Images**: 61,486
  - **Format**: RGB images

## 🧠 Model Overview

- **Architecture**: Convolutional Neural Network (CNN)
- **Framework**: TensorFlow/Keras
- **Objective**: Accurately classify plant images into one of 39 disease categories.

## ⚙️ Training Details

- **Epochs**: 20
- **Batch Size**: 32
- **Optimizer**: Adam
- **Learning Rate**: 0.0001

### Final Epoch Metrics
| Metric              | Value   |
|---------------------|---------|
| **Training Accuracy**  | 90.02%  |
| **Training Loss**      | 0.3058  |
| **Validation Accuracy**| 94.41%  |
| **Validation Loss**    | 0.1927  |

## 📂 File Structure

- `CNNPlantDiseaseClassificationV2`: Main file containing the CNN implementation and training pipeline.
- **Other Files/Folders**:
  - **Notebooks**: Jupyter notebooks for exploratory data analysis and visualization (if applicable).
  - **Logs**: Training and validation logs.(not added)
  - **Models**: Saved trained models for deployment or further analysis.(not added)

## 📊 Results

The model performs well across all classes, achieving a high validation accuracy of **94.41%**.
Example: ![image](https://github.com/user-attachments/assets/5c4b3a9e-b461-40b9-b24e-0e87e68fd913)


## 🔭 Future Work

- Experiment with advanced data augmentation techniques to improve model generalization.
- Incorporate transfer learning with pre-trained models like ResNet or EfficientNet.
- Optimize hyperparameters to boost classification accuracy further.
- Develop a web-based application for real-time plant disease detection.

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 💡 Acknowledgments

- [PlantVillage Dataset](https://www.kaggle.com/emmarex/plantdisease) for providing the data.
- TensorFlow/Keras community for tools and resources.

---

If you have suggestions or improvements, I want you to know that you're welcome. 🌟
