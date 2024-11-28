# Plant Disease Classification Web Application 🌱

This is a web application that allows farmers to identify and confirm plant diseases using deep learning models. Currently, the model is trained to classify **Potato** diseases and can identify three classes: 
- Potato___Early_blight
- Potato___Late_blight
- Potato___Healthy

The application uses a **Convolutional Neural Network (CNN)** model for classification.

### Dataset
The model is trained using the dataset from Kaggle: [Plant Village Dataset](https://www.kaggle.com/datasets/arjuntejaswi/plant-village). It contains images of healthy and diseased plants, specifically potatoes.

The dataset consists of 2152 images belonging to the following three classes:
- `Potato___Early_blight`
- `Potato___Late_blight`
- `Potato___healthy`

![Model Accuracy](https://github.com/MARESH001/Plant-disease-classification/blob/main/output.png)

### Features
- **Web Interface**: Allows users to upload images of plants to identify diseases.
- **CNN Model**: Trained on images of potato diseases to predict the plant health.
- **Future Updates**: The second version of the application will include additional plant diseases.

---

## How to Run

### Clone the Repository

First, clone the repository to your local machine:
```bash
git clone https://github.com/MARESH001/Plant-disease-classification.git
run npm start
```
