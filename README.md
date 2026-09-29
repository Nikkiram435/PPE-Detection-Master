🦺 PPE Detection & Construction Safety Monitoring

Real-time construction safety monitoring using YOLOv8 and OpenCV.

📌 Overview

This project is an AI-powered Personal Protective Equipment (PPE) Detection System designed to improve safety monitoring at construction sites.

The system uses YOLOv8 and OpenCV to detect workers and identify essential safety equipment such as helmets, safety vests, and masks in real time.

It also provides real-time detection counts and can send email alerts when a person is detected without a helmet.

✨ Features

🪖 Helmet Detection – Detects whether a worker is wearing a helmet.

🦺 Safety Vest Detection – Identifies workers wearing safety vests.

😷 Mask Detection – Detects whether a worker is wearing a mask.

👤 Person Detection – Detects people within the monitored area.

📊 Real-Time Count Display – Displays the number of detected helmets, vests, masks, and persons.

📧 Email Alerts – Sends an alert when a person is detected without a helmet.

⚡ Non-Blocking Email Process – Helps maintain a smooth video feed while alerts are sent.

🔔 Mail Sent Notification – Displays a notification when an email alert is successfully sent.

🎥 Real-Time Video Detection – Supports webcam/video-based monitoring.

🛠️ Tech Stack

Technology

Purpose

Python

Core programming

YOLOv8

Object detection

OpenCV

Computer vision & video processing

NumPy

Numerical processing

SMTP / Email

Safety alert notifications

Conda / pip

Environment & dependency management

🧠 How It Works

Camera / Video Input
        ↓
   YOLOv8 Model
        ↓
Object Detection
        ↓
┌─────────────────────────────┐
│ Person                      │
│ Helmet                      │
│ Safety Vest                 │
│ Mask                        │
└─────────────────────────────┘
        ↓
Real-Time Detection Results
        ↓
Safety Monitoring
        ↓
Email Alert if Helmet Missing

📂 Project Structure

PPE-Detection-Master/
│
├── Model/
│   └── PPE detection model files
│
├── Visuals/
│   └── Project visuals
│
├── app.py
├── webcam.py
├── webcam1.py
├── webcam2.py
├── requirements.txt
├── yolo_env.yml
├── ppe-detection.ipynb
├── .gitignore
└── README.md

⚙️ Requirements

Python 3.9

YOLOv8

OpenCV

Dependencies listed in requirements.txt

🚀 Installation

1. Clone the repository

git clone https://github.com/Nikkiram435/PPE-Detection-Master.git
cd PPE-Detection-Master

2. Install dependencies

Using pip:

pip install -r requirements.txt

Or using Conda:

conda env create -f yolo_env.yml
conda activate yolo

3. Run the application

python webcam.py

The system will start real-time PPE detection using the webcam/video input.

📧 Email Alert Configuration

The project supports email notifications for helmet violations.

If email alerts are enabled, configure the required email settings through environment variables.

Do not upload real passwords, API keys, or other credentials to GitHub.

Example:

SENDER_EMAIL=your_email@example.com
RECEIVER_EMAIL=receiver@example.com
EMAIL_PASSWORD=your_app_password

⚠️ Never commit real credentials or sensitive information to a public repository.

🎯 Use Cases

This system can be used for:

Construction site safety monitoring

Workplace PPE compliance

Helmet compliance detection

Real-time safety surveillance

Computer vision-based safety systems

Automated safety notifications

🔮 Future Improvements

Possible future enhancements include:

📱 Web-based monitoring dashboard

☁️ Cloud-based monitoring

📈 Safety compliance analytics

🎥 Multi-camera support

🚨 More PPE violation alerts

📊 Historical safety reports

🌐 Remote monitoring

📸 Project Preview

Add project screenshots or demo images here:

![PPE Detection](Visuals/ppe-public-view.png)

👩‍💻 Project

PPE Detection & Construction Safety Monitoring

Built as a final-year academic project using computer vision and deep learning techniques.

📄 License

This project is licensed under the MIT License.

🙌 Acknowledgements

YOLOv8

OpenCV

Python

Open-source computer vision community
