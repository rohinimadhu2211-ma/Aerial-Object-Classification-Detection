🛩️ Aerial Object Classification using Deep Learning
📌 Project Overview

This project focuses on classifying aerial images into Bird 🐦 and Drone 🚁 using deep learning techniques. The goal is to build an accurate model for applications like surveillance, wildlife monitoring, and airspace safety.

🚀 Features
Image Classification (Bird vs Drone)
Custom CNN Model
Transfer Learning using MobileNetV2
Achieved ~98% Accuracy
Model Evaluation (Precision, Recall, F1-score)
Streamlit Web App for real-time prediction
🧠 Technologies Used
Python
TensorFlow / Keras
OpenCV
NumPy, Matplotlib, Scikit-learn
Streamlit
📂 Project Structure
Aerial_Project/
 ├── data/
 ├── models/
 │    └── best_model.keras
 ├── app.py
 ├── train.py
 ├── requirements.txt
 └── README.md
⚙️ How It Works
Data preprocessing (resize, normalize images)
Data augmentation (rotation, zoom, flip)
Model training:
Custom CNN
Transfer Learning (MobileNetV2)
Model evaluation using classification metrics
Deployment using Streamlit
📊 Results
Accuracy: ~98%
Precision: ~98%
Recall: ~98%
F1-score: ~98%
▶️ Run the Project
🔹 Install dependencies
pip install -r requirements.txt
🔹 Run Streamlit App
streamlit run app.py
🌐 Output
Upload an image
Get prediction: Bird or Drone
View confidence score
🔮 Future Work
Implement object detection using YOLOv8
Extend to real-time video detection
Improve dataset for more classes
💬 Conclusion

The project successfully demonstrates the use of deep learning and transfer learning for aerial image classification with high accuracy and real-world applicability.

👩‍💻 Author
Rohini S
