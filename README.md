📘 FOOD EXPIRY DETECTION SYSTEM (Smart Kitchen Assistant) Using YOLOv7

This project demonstrates the implementation of real-time object detection using the YOLOv7 architecture, tailored for an AI-powered Smart Kitchen Assistant designed to detect and identify food items, enabling proactive monitoring for expiry and spoilage using computer vision.

🧠 Project Overview
Robotics systems increasingly rely on accurate visual perception to interact with dynamic environments. YOLO (You Only Look Once) is a state-of-the-art, real-time object detection system that balances accuracy and inference speed, making it highly suitable for robotic applications. 
The objective is to automate the process of detecting various food items in real-time and lay the groundwork for an expiry tracking system. By integrating object recognition with expiration logic, this project aims to reduce food waste and improve kitchen efficiency.

🔍 Features
- Real-time food item detection using YOLOv7, optimized for speed and accuracy.
- Custom-trained model using annotated food images from Roboflow.
- Includes mAP (mean Average Precision) and visualization of predictions on test images.
- Designed as a modular system that can be extended with expiry date estimation and IoT integrations.

📁 Project Structure
- Robotics_YOLO.ipynb: Main notebook containing the training and inference pipeline using YOLOv7.
- data.yaml: Roboflow-exported configuration file describing classes and paths.
- runs/train/: Folder automatically generated during training (contains model weights and logs).
- images/: Sample input images and detection outputs.\

🚀 Usage
To reproduce the results:
- Clone the YOLOv7 repository
- Install dependencies from the YOLOv7 repo.
- Use the Roboflow-provided data.yaml and images.
- Run the cells in Robotics_YOLO.ipynb.

🚀 How It Works
- Data Preparation: A dataset of food items is labeled using Roboflow.
- Model Training: The YOLOv7 model is trained using the labeled dataset through PyTorch-based training scripts.
- Inference: Real-time detection is performed, where food items are recognized with bounding boxes and class labels.
- Future Scope: Detected food items can be cross-referenced with a database of shelf lives to estimate expiry dates and send alerts.

🔍 Results
The trained model demonstrates high detection accuracy and real-time inference capability, making it suitable for robotics tasks like object grasping, sorting, or navigation assistance.

