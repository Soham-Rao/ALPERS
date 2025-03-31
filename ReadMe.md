# ALPERS
_Automatic License PlatE Recognition System_

---
### To Run
1. Install Dependencies
	1. Open Command Prompt at the required working directory
	2. Run the following command ``` pip install -r Requirements.txt```
2. Run ```./GUI/main.py``` 
3. Choose Live video feed or Static image
	1. If the Image option is chosen, upload an Image containing a license plate
	2. If the Live video option is chosen, show the license plate to the camera (press 'q' to exit)
4. The License plate will be recorded in the ```plates.txt``` file
---
### Tech Stack
1. Machine Learning
	- Ultralytics Yolo V8
	- CUDA 
	- PyTorch
2. GUI
	- Tkinter
	- CustomTkinter
3. Input Handling
	- OpenCV
4. Text Extraction
	- EasyOCR
---




