# 🎯 Player Re-identification using YOLOv11 and ResNet50

This project was submitted as part of an **AI Internship Assignment at Liat.ai**.  
The goal was to build a system that detects and re-identifies players in a video, ensuring players retain consistent IDs even when they leave and re-enter the frame.

---

## 📌 Objective

Given a 15-second sports video, the task is to:
- Detect all players throughout the video using a pre-trained YOLOv11 model.
- Assign unique player IDs.
- Maintain the same ID for each player even if they leave and re-enter the frame.
- Output a video with bounding boxes, consistent IDs, and original match audio.

---

## 🚀 How to Set Up and Run the Code

1. **Clone the repository and navigate to the folder:**
   ```bash
   git clone https://github.com/Teja5164/PlayerReIdentification_using_YOLOv11.git
   cd PlayerReIdentification_using_YOLOv11
2. **Install required libraries:
    You can install all dependencies using pip:
   ```bash
    pip install -r requirements.txt

---

3. **Download the input video and YOLOv11 model:

  Input Video: 15sec_input_720p.mp4

  YOLOv11 Model: best.pt

---

##Run the notebook:
Open the Jupyter notebook Player Re-Identification using YOLOv11.ipynb in Kaggle, Colab, or Jupyter and execute the cells step-by-step.

---

## Final Output:

The final annotated video will be saved as:
output_video_with_audio.mp4

## Dependencies and Environment Requirements

Make sure your environment supports the following libraries:
Python ≥ 3.8
ultralytics
opencv-python
torch, torchvision
numpy
Pillow
scikit-learn
ffmpeg-python
matplotlib
collections
pickle
You can install them all using:
    ```bash
    pip install ultralytics opencv-python torch torchvision scikit-learn ffmpeg-python matplotlib

---

## Best tested on Kaggle or Google Colab with GPU runtime enabled.

---

## Output Includes:

Bounding boxes around players
Consistent player IDs
Original audio retained using ffmpeg
Final output video: output_video_with_audio.mp4

---

## 🔗 Resources  
- **Input Video**: [15sec_input_720p.mp4](https://drive.google.com/file/d/.../view?usp=drive_link)  
- **YOLOv11 Model**: [Download (.pt)](https://drive.google.com/file/d/1-5fOSHOSB9UXyP_enOoZNAMScrePVcMD/view)  
- **Output Video**: [output.mp4](https://drive.google.com/file/d/.../view?usp=drive_link)  
- **Complete Folder**: [Google Drive](https://drive.google.com/drive/folders/11rABaiWY4f3L6cHcuCh7t03RWE1IhpC7)  

For full methodology, tools used, problems encountered, and future scope — refer to the Project Report (PDF).

---

## 👤 Author

**N R Teja Prakash**    
- 🔗 [LinkedIn](https://www.linkedin.com/in/teja-prakash-0b49a830b)  
- 💻 [GitHub](https://github.com/Teja5164)  
- ✉️ [Email](mailto:tejaprakash5164@gmail.com)
