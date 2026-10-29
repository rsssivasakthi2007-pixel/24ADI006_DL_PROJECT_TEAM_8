# 🔥 Deep Learning-Based Real-Time Fire and Smoke Detection Using Surveillance Video

## 📌 Project Overview

Fire accidents can cause serious damage to human life, property, and the environment. Traditional fire detection systems may not detect fire or smoke effectively in every surveillance area.

This project uses a **pretrained YOLO object detection model** to detect fire and smoke from uploaded images and surveillance videos. The system displays detected objects with bounding boxes and provides a simple web interface for users to upload files and view the results.

## 🎯 Objectives

- Detect fire and smoke from images and videos.
- Use a pretrained YOLO model for object detection.
- Display bounding boxes around detected objects.
- Show detection results through a web interface.
- Allow users to view and download processed videos.
- Support early identification of potential fire hazards.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Deep Learning:** YOLO Object Detection
- **Computer Vision:** OpenCV
- **Model Platform:** Hugging Face
- **Web Framework:** Streamlit
- **Development Environment:** Google Colab
- **Libraries:** Ultralytics, Hugging Face Hub

## ⚙️ System Workflow

1. User uploads an image or video.
2. The pretrained YOLO model is loaded.
3. The uploaded file is processed by the model.
4. Fire and smoke objects are detected.
5. Bounding boxes are drawn around detected objects.
6. The detection results are displayed on the website.
7. Processed videos can be viewed and downloaded.

## 🧠 Model Used

This project uses a pretrained YOLO model downloaded from Hugging Face:

**Model Repository:** [nobita111222/fire-smoke-yolov8n](https://huggingface.co/nobita111222/fire-smoke-yolov8n)

The model is loaded using the Ultralytics YOLO library. A confidence threshold of 0.25 is used by default to filter detections.

## 🌐 Web Application Features

- Simple and user-friendly interface.
- Image upload and fire/smoke detection.
- Video upload and frame-by-frame detection.
- Bounding box visualization.
- Detection status and detected class names.
- Processed video preview and download option.
- Adjustable detection confidence threshold.

## 💻 Installation and Execution

### Prerequisites

- Python 3.10 or 3.11 recommended.
- Internet connection for downloading the pretrained model and required packages.
- A computer capable of running the model.

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### Step 2: Open the Project Folder

```bash
cd YOUR_PROJECT_FOLDER
```

### Step 3: Install Dependencies

```bash
python -m pip install streamlit ultralytics huggingface_hub opencv-python-headless
```

### Step 4: Run the Web Application

```bash
python -m streamlit run app.py
```

### Step 5: Open the Website

Open the local URL shown in the terminal, usually:

```text
http://localhost:8501
```

Upload an image or video and click **Start Detection** to view the results.

## 📂 Project Structure

```text
Fire-Smoke-Detection/
│
├── app.py
├── requirements.txt
└── README.md
```

The pretrained model weights are downloaded from Hugging Face when the application starts, so the model file does not need to be stored in the repository.

## 🔮 Future Enhancements

- Real-time detection from CCTV camera streams.
- Instant alerts when fire or smoke is detected.
- Email or mobile notifications.
- Improved detection accuracy in different lighting conditions.
- Detection location tracking and event logging.
- Deployment as a publicly accessible web application.

## ⚠️ Limitations

- Detection accuracy depends on the pretrained model and input video quality.
- Processing speed depends on the available hardware.
- A local Streamlit application is accessible only on the computer running it unless additional networking or hosting is configured.
- The system is intended as a project demonstration and should not replace certified fire safety systems.

## 👩‍💻 Project Outcome

This project demonstrates how deep learning and computer vision can be combined with a web application to identify potential fire and smoke hazards in images and videos.

## 📜 Disclaimer

This project is developed for educational and demonstration purposes. Detection results may contain false positives or missed detections. Always follow
# 24ADI006_DL_PROJECT_TEAM_8
