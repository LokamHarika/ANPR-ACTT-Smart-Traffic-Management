# ANPR & ATCC System

## Overview
This project is an Automatic Number Plate Recognition (ANPR) and Automated Traffic Control & Compliance (ATCC) system that utilizes YOLOv8 and YOLOv9 for real-time vehicle monitoring. It is designed to enhance traffic management by detecting and analyzing various violations.

### Key Features
✔ ANPR (Automatic Number Plate Recognition): Detects and extracts vehicle license plates using advanced YOLO models.  
✔ ATCC (Automated Traffic Control & Compliance): Monitors traffic flow and detects rule violations.  
✔ Helmet Detection: Identifies two-wheeler riders without helmets.  
✔ Triple Riding Detection: Flags instances where more than two people are riding a two-wheeler.  
✔ Accident Detection: Recognizes accident scenarios using deep learning.  
✔ Emergency Vehicle Detection: Identifies ambulances, fire trucks, and police vehicles to prioritize their movement.  

## Technologies Used
- Backend: Flask, Python  
- Frontend: React.js  
- Machine Learning Models: YOLOv8, YOLOv9, PyTesseract-OCR, Computer Vision  
- Database: MySQL  

## Installation & Setup

### Prerequisites
Ensure you have the following installed before running the project:  
- Python (>=3.11)  
- Node.js & npm (for frontend)  
- Flask  
- React.js  
- OpenCV, NumPy, TensorFlow/PyTorch  
- YOLOv8 & YOLOv9 (Ultralytics)  
- PyTesseract-OCR  

### Deployment Steps

#### Step 1: Clone the Repository
Open a terminal and run:  
```
git clone https://github.com/LokamHarika/ANPR-ACTT-Smart-Traffic-Management.git
```  

#### Step 2: Backend Setup
Navigate to the project directory and start the backend:  
```
python app.py
``` 

#### Step 3: Frontend Setup
Open a new terminal and navigate to the frontend directory:  
```
cd FrontEnd
npm install  # Install dependencies
npm run dev  # Start the frontend server
```  

#### Step 4: Login to the System
When the login page appears, enter the credentials:  
- Username: user  
- Password: pass  

Once logged in, the dashboard will be accessible for real-time monitoring.  

## You're All Set! 🎯
The ANPR & ATCC System is now fully operational! You can now monitor vehicle activities, detect violations, and improve road safety with AI-driven automation.
