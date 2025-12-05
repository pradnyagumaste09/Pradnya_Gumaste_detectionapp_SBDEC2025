🏛️ HeritageLens AI – Cultural Heritage Detection App

A Streamlit-based AI application for detecting and analyzing heritage sites, archaeological structures, and cultural landmarks using advanced YOLOv11 deep learning technology.

🌟 Features
📸 Image Detection

Upload single or multiple images

Real-time object detection with bounding boxes

Confidence scoring

Cropped detection previews

Downloadable results and reports

🎥 Video Analysis

Upload local video files

Analyze YouTube video links

Frame-by-frame real-time detection

Start/stop controls

Detailed video summaries

📊 Interactive Dashboard

Detection statistics and charts

Class-wise summaries

Confidence score distribution

Combined insights from image + video analysis

📚 Educational Module

Information on heritage categories

Cultural significance

Preservation tips

AI’s role in archaeology

📄 PDF Report Generation

Automatic PDF creation

Clean, professional formatting

Includes statistics + sample detections

🏺 Heritage Classes Detected

Stones / Stone Pillars / Stone Structures 🗿

Crops / Farmland 🌾

Non-Archaeological (Natural Features) 🏔️

Heritage Sites (Temples, Forts, Monuments) 🏛️

🚀 Installation
Prerequisites

Python 3.8+

(Optional) CUDA-enabled GPU

Setup
git clone https://github.com/<your-username>/Pradnya_detectionapp_SBDEC2025.git
cd Pradnya_detectionapp_SBDEC2025
pip install -r requirements.txt


Ensure your model weights file is named:

best.pt


and placed in the project directory (or update your code path accordingly).

🎯 Usage
Start the Application
streamlit run app.py


Open your browser at:
👉 http://localhost:8501

📸 Image Detection

Go to Image Detection

Upload one/multiple images

Click Analyze

View bounding boxes + statistics

Download PDF report if needed

🎥 Video Detection

Open Video Detection

Choose:

Upload Video

YouTube Link

Start detection

Stop to generate summary

Export PDF report

📊 Summary Dashboard

View combined analytics

Explore interactive charts

Download overall report

📚 Learn About Heritage

Read heritage category details

Understand cultural context

Learn preservation techniques

🔧 Technical Details
Architecture

Frontend: Streamlit

Model: YOLOv11

Backend: PyTorch

Processing: OpenCV, PIL

Charts: Plotly, Matplotlib

Reports: ReportLab

Model Info

Object Detection (YOLOv11)

4-class custom trained model

Outputs bounding boxes, class labels, confidence scores

🎨 UI/UX Highlights

Modern layout with custom CSS

Warm heritage-inspired colors

Responsive design

Interactive elements

User-friendly navigation

📋 Requirements
System

8GB RAM (16GB recommended)

2GB free storage

GPU recommended for speed

Python Dependencies

(Already included in requirements.txt)

🛠️ Troubleshooting
Model Load Error

Ensure best.pt is present

Ensure correct model path

Slow Performance

Lower image/video resolution

Use GPU if available

YouTube Errors

Check URL

Ensure internet connection

🤝 Contributing

Fork repository

Create feature branch

Add changes

Submit pull request

Follow:

PEP8

Meaningful variable names

Clear comments

📄 License

This project is licensed under MIT License.

🙏 Acknowledgments

Ultralytics (YOLOv11)

Streamlit

OpenCV

PyTorch

Plotly

❤️ HeritageLens AI — Preserving the Past with Technology
