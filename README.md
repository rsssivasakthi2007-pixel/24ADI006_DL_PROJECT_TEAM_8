# 🔥 Deep Learning-Based Real-Time Fire and Smoke Detection Using Surveillance Video

## 📌 Project Overview

Fire accidents can cause serious damage to people, buildings, forests, and other properties. Traditional fire alarm systems may not detect every fire or smoke incident immediately in large surveillance areas.

This project uses **Deep Learning and Computer Vision** to detect fire and smoke from images and surveillance video. A pretrained YOLO object detection model identifies fire and smoke and displays bounding boxes around detected objects.

The project uses Python, OpenCV, YOLO, and Gradio to create a simple web interface for testing uploaded images and videos.

## 🎯 Objectives

- Detect fire and smoke from images and video.
- Identify the location of detected objects using bounding boxes.
- Display prediction labels and confidence scores.
- Provide a simple web interface for users.
- Explore the use of AI for early fire detection and surveillance monitoring.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| YOLO | Fire and smoke object detection |
| Hugging Face | Pretrained model hosting |
| OpenCV | Video and image processing |
| Gradio | Web interface |
| Google Colab | Model testing and development |
| GitHub | Version control and project documentation |

## ⚙️ System Workflow

1. **Input:** Upload an image or surveillance video.
2. **Preprocessing:** Read the image or extract frames from the video.
3. **Detection:** Pass the image or frames to the pretrained YOLO model.
4. **Prediction:** Detect fire, smoke, or no detected objects.
5. **Visualization:** Draw bounding boxes and show confidence scores.
6. **Output:** Display the annotated image or processed video.

```text
Image / Surveillance Video
            |
            v
   Image and Frame Processing
            |
            v
    Pretrained YOLO Model
            |
            v
    Fire and Smoke Detection
            |
            v
 Bounding Boxes + Confidence
            |
            v
       Gradio Interface
```

## ✨ Key Features

- Fire detection
- Smoke detection
- Image-based prediction
- Video frame analysis
- Bounding-box visualization
- Confidence score display
- Browser-based interface
- Pretrained model inference without training from scratch

## 📂 Project Structure

```text
fire-smoke-detection/
│
├── app.py                 # Gradio application
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
├── sample_images/         # Sample test images
├── sample_videos/         # Sample test videos
└── outputs/               # Processed results
```

*This is the suggested structure. Keep only the files and folders that exist in your repository.*

## 🚀 Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd fire-smoke-detection
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Install the dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python app.py
```

Open the local Gradio URL shown in the terminal to use the interface.

**Google Colab option:** Install the required packages in a Colab cell, load the pretrained model, and launch Gradio with sharing enabled to test the application through a temporary public URL.

## 📦 Requirements

Example `requirements.txt`:

```text
ultralytics
huggingface_hub
gradio
opencv-python-headless
pillow
numpy
```

## 🧪 Testing

Test the system with different types of input:

- Images containing visible fire.
- Images containing smoke.
- Normal scenes without fire or smoke.
- Videos containing fire or smoke.
- Surveillance-style footage with different lighting conditions.

Record the model's predictions and check for false detections and missed detections. Evaluate performance on a representative test dataset before making claims about accuracy.

## 📊 Expected Output

The application is designed to display:

- **Fire detected** when the model identifies fire.
- **Smoke detected** when the model identifies smoke.
- **No objects detected** when no target objects are detected above the configured confidence threshold.
- Bounding boxes and confidence scores for detected objects.

Actual results depend on the input media, model quality, and confidence threshold. “No objects detected” does not guarantee that a scene is safe.

## 📚 Dataset and Model Resources

- [D-Fire Dataset](https://github.com/gaia-solutions-on-demand/DFireDataset)
- [CCTV Smoke and Fire Dataset](https://huggingface.co/datasets/Simuletic/CCTV-Smoke-Fire-Emergency-Detection-Dataset)
- [Ultralytics YOLO Documentation](https://docs.ultralytics.com/)
- [Hugging Face Documentation](https://huggingface.co/docs)

Check each dataset's license and usage restrictions before redistributing images or using them commercially.

## 🔮 Future Enhancements

- Real-time camera stream processing.
- Email or notification alerts for detected fire and smoke.
- Improved detection under low-light and challenging conditions.
- Performance evaluation using precision, recall, and mean Average Precision (mAP).
- Deployment as a hosted web application.
- Integration with authorized surveillance systems.

## ⚠️ Limitations

This project is an educational prototype. Its predictions may contain false positives or false negatives. It must not be used as a replacement for certified fire alarms, emergency response procedures, or professional fire safety systems.

## 📜 Disclaimer

This project is developed for educational and demonstration purposes. Detection results may contain false positives or missed detections. Always follow
# 24ADI006_DL_PROJECT_TEAM_8
