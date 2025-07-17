# Underwater Fish Detection using Object Detection Models
This project aims to detect and classify various underwater creatures such as fish, jellyfish, sharks, and starfish using object detection techniques. The dataset used is the publicly available Aquarium Object Detection Dataset.

📂 Dataset
Source: Kaggle – Aquarium Object Detection

Path used: /kaggle/input/aquarium-data-cots

Classes:
['fish', 'jellyfish', 'penguin', 'puffin', 'shark', 'starfish', 'stingray']

Contains annotated images with bounding boxes for training object detection models.

🎯 Objectives
To preprocess and annotate underwater images.

To train and compare various object detection models.

To determine the most efficient model based on accuracy, speed, and confidence score.

To deploy the best model for real-time fish detection.

⚙️ Preprocessing
Converted all annotations to YOLO format.

Resized images to a fixed dimension (448×448) to maintain uniformity.

Applied image augmentation (optional step).

Split dataset into train, validation, and test sets.

🧠 Models Used
YOLOv5

SSD (Single Shot MultiBox Detector)

Faster R-CNN

RetinaNet

EfficientDet

Each model was evaluated on accuracy, loss, and detection performance using the same dataset.

# 📊 Model Performance Summary
Model	Accuracy	Inference Speed	Confidence Score (avg)	Remarks
YOLOv5	86%	Very Fast	0.81	Best for real-time detection
SSD	74%	 Fast	0.71	Lightweight but less accurate
Faster R-CNN	91%	 Slow	0.87	Best Accuracy & Precision
RetinaNet	84% Moderate	0.78	Balanced performance
EfficientDet	83%	 Moderate	0.76	Good but heavier model


# 🏆 Best Performing Model
Faster R-CNN achieved the best results:

High detection accuracy of 91%

Average confidence score: 0.87

Excellent bounding box precision

Suitable for applications needing high accuracy over speed

# 🚀 Deployment Steps
1. Clone the Repository
git clone https://github.com/yourusername/underwater-fish-detection.git
cd underwater-fish-detection

# 2. Install Dependencies
pip install -r requirements.txt

# 3. Streamlit Web App (Optional)
streamlit run app.py


# 🧾 Conclusion
The project compares multiple deep learning models on underwater object detection. Faster R-CNN emerged as the most effective model due to its superior detection precision, though YOLOv5 is recommended for real-time use due to its speed.




# 📸 Screenshots


<img width="646" height="759" alt="image" src="https://github.com/user-attachments/assets/91bde58a-a75e-4585-ac51-f2b45c17d112" />

<img width="254" height="336" alt="image" src="https://github.com/user-attachments/assets/80fec510-d7fe-4ad1-8923-4bb17a6ef1c2" />


# With Length 


<img width="1149" height="747" alt="image" src="https://github.com/user-attachments/assets/e6a2ce11-62ff-4359-9b76-b6326c9cb1c2" />





# Training And Loss 


<img width="640" height="642" alt="image" src="https://github.com/user-attachments/assets/f7ebc66c-bf11-4bfc-8f37-97b9f517ebdc" />
