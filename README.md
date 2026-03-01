 **Plant Disease Detection using CNN**

**Overview**
A deep learning model that automatically detects tomato 
leaf diseases from images using Convolutional Neural Networks (CNN).
Built on the PlantVillage dataset with 38 disease classes.

**Author**
- **Name:** Dr. Tapas Ranjan Das
- **Background:** PhD in Plant Pathology
- **Focus:** Applying Machine Learning to Plant Disease Diagnostics

**Problem Statement**
Manual disease diagnosis is time-consuming and requires expert 
knowledge. This model enables fast, automated detection of 
tomato diseases from leaf photographs.

**Dataset**
- **Source:** PlantVillage Dataset
- **Images:** 54,000+ leaf images
- **Classes:** 38 disease categories
- **Crops:** 14 crop species

**Model Architecture**
- 3 Convolutional layers (32, 64, 128 filters)
- MaxPooling layers for dimensionality reduction
- Dense layer with 256 neurons
- Dropout (0.5) to prevent overfitting
- Softmax output for multi-class classification

**Results**
| Metric | Score |
|--------|-------|
| Validation Accuracy | 85.43 % |
| Model | Custom CNN |
| Image Size | 128 x 128 |
| Framework | TensorFlow/Keras |

**Technologies Used**
- Python 3
- TensorFlow / Keras
- TensorFlow Datasets
- NumPy
- Matplotlib
- Google Colab (T4 GPU)

**How to Run**
1. Open the notebook in Google Colab
2. Enable T4 GPU runtime
3. Run all cells sequentially

**Files**
- `tomato_disease_cnn.ipynb` - Main training notebook
- `README.md` - Project documentation

**Future Work**
- Deploy as web application using Streamlit
- Extend to all 14 crops in PlantVillage
- Implement transfer learning with EfficientNet
- Test on field-collected images
