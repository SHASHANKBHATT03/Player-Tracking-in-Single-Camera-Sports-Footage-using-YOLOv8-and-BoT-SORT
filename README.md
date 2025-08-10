# 🏃‍♂️ Player Tracking in Single-Camera Sports Footage using YOLOv8 and BoT-SORT

This project implements a real-time **player tracking system** for single-camera sports footage using **YOLOv8** for detection and **BoT-SORT** for tracking. It processes a 15-second video clip and outputs a new video with consistent player IDs and original audio.

---

## 🔍 Features

- ⚽ Detects and tracks players in sports footage
- 🧠 YOLOv8 used for accurate object detection
- 🔄 BoT-SORT applied for consistent ID tracking
- 🎥 Output video includes bounding boxes and player IDs
- 🔊 Original audio is retained in final video
- ☁️ Works seamlessly in Google Colab using Google Drive links

---

## 📥 Downloads Used

- 🎞️ **Input video** (15 seconds):  
  [Google Drive Link](https://drive.google.com/file/d/1TDcND31fvEDvcnZCaianTxJrmT8q7iIi/view)

- 🧠 **YOLOv8 model weights** (best.pt):  
  [Google Drive Link](https://drive.google.com/file/d/1-5fOSHOSB9UXyP_enOoZNAMScrePVcMD/view)

---

## ▶️ Run in Google Colab

1. **Open the notebook**:  
   [player_reid_clean_colab_final.ipynb](./player_reid_clean_colab_final.ipynb)

2. **Download files from Google Drive**:

python
!pip install gdown
!gdown --id 1TDcND31fvEDvcnZCaianTxJrmT8q7iIi -O videos/input_video.mp4
!gdown --id 1-5fOSHOSB9UXyP_enOoZNAMScrePVcMD -O models/best.pt


3.	Run all cells to:
o	Detect players using YOLOv8
o	Track them using BoT-SORT
o	Reattach original audio using FFmpeg
o	View and download final output from runs/detect/track/
________________________________________
📁 Project Structure
📂 models/                               # YOLOv8 weights
📂 videos/                               # Input video from Google Drive
📂 runs/detect/track/                    # Final tracked output video
📂/content/final_tracked_output.mp4      # Final video with player tracking 
📜 player_reid_clean_colab_final.ipynb   # Jupyter notebook 
________________________________________
💻 Dependencies
pip install ultralytics opencv-python ffmpeg-python gdown
________________________________________
📄 License
MIT License © 2025 Shashank Bhatt
________________________________________
🙋‍♂️ Author
Shashank Bhatt
B.Tech CSE (2021-2025) | Graphic Era Hill University
## 🔗 Connect with Me

- GitHub: [SHASHANKBHATT03](https://github.com/SHASHANKBHATT03)
- LinkedIn: [Shashank Bhatt](https://www.linkedin.com/in/shas
