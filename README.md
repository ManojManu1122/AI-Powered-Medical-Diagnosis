# AI-Powered-Medical-Diagnosis

## **Overview**
This project leverages **Convolutional Neural Networks (CNNs)** to detect and classify multiple medical conditions based on image inputs. The model is trained to identify **brain tumors, pneumonia, bone fractures, skin infections, kidney stones, and eye infections** using deep learning techniques. The system is integrated with **Streamlit** to provide a user-friendly web interface for easy accessibility.

## **Features**
- **Multi-Disease Detection**: Supports classification for six medical conditions.
- **Deep Learning Model**: Built with a custom CNN architecture optimized for image classification.
- **Streamlit UI**: Simple web-based interface for users to upload images and receive predictions.
- **Optimized Training**: Uses Adam optimizer and categorical cross-entropy loss for accurate classification.
- **Scalable and Extendable**: Can be expanded to detect additional medical conditions.

## **Technologies Used**
- **Python**
- **TensorFlow/Keras**
- **OpenCV** (for image preprocessing)
- **Streamlit** (for UI development)
- **NumPy, Pandas, Matplotlib** (for data processing and visualization)

## **Project Workflow**
1. **Data Collection & Preprocessing**:
   - Images are collected from medical datasets.
   - Preprocessing includes resizing, normalization, and augmentation.
2. **Model Development**:
   - Built a CNN model with multiple **Conv2D, MaxPooling, and Dense layers**.
   - Used **Softmax activation** for multi-class classification.
3. **Model Training & Evaluation**:
   - Trained the model using **Adam optimizer** and **categorical cross-entropy loss**.
   - Evaluated performance using accuracy and loss metrics.
4. **Web Interface Development**:
   - Integrated with **Streamlit** for user-friendly image uploads and predictions.
5. **Deployment & Testing**:
   - The model is tested with real-world medical images to ensure accuracy.

## **Installation & Setup**
### **Prerequisites**
Ensure you have Python installed and the following dependencies:
```bash
pip install tensorflow streamlit opencv-python numpy pandas matplotlib
```

### **Running the Application**
1. Clone the repository:
   ```bash
   git clone https://github.com/ManojManu1122/AI-Powered-Medical-Diagnosis.git
   cd disease-prediction-cnn
   ```
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## **Usage**
1. Open the web app in your browser.
2. Upload a medical image (X-ray, MRI, etc.).
3. Click the **Predict** button.
4. View the predicted disease category and confidence score.

## **Future Enhancements**
- Add more medical conditions to the model.
- Improve accuracy with **ResNet/VGG architectures**.
- Implement a mobile application for better accessibility.
- Integrate with cloud services for real-time predictions.

