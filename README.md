Important ::: View Demo_screenshots for result.

Real-Time Fire Detection System  
An AI-powered **real-time fire detection system** built using **YOLO** and **EfficientDet**, designed to identify flames from images and live video feeds with high accuracy.  


Project Goal  
Enable **early fire detection** through computer vision, making surveillance and safety systems more intelligent and responsive.  

⚙️ Process  
1. **Dataset Preparation:** Custom fire dataset with augmentations (flips, rotations, blur, noise).  
2. **Model Training:** Trained YOLO on Google Colab, optimized using train/val/test splits.  
3. **Deployment:** Final weights (`fire.pt`) integrated with `fire.py` for real-time inference.  

Features  
- Real-time fire detection from camera feeds or video streams.  
- Robust against lighting changes, angle variations, and noise.  

Run fire.py file.
The model is trained on colab with custom dataset, the updated weights are then stored in the form of fire.pt file and used to detect fire.

Datasets are in Data_compressed folder, in zipped form.



<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/414d45c4-f782-4011-a105-d4cff2b0b860" />

Dependencies: Ultralytics, openCV
Run the Project  
```bash
# Clone repository
git clone https://github.com/your-username/fire-detection.git  
cd fire-detection  

# Install dependencies
pip install ultralytics opencv-python  

# Run detection
python fire.py
```
