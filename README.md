# Car-number-plate-detection
##Project Overview
This project demonstrates a real-time vehicle number plate detection system developed using Python and OpenCV. The system leverages Haar Cascade classifiers to identify and locate license plates from a live webcam video stream.

##Requirements :-
To run this project, ensure you have the following:
Python 3.x
OpenCV (cv2)
A working webcam for real-time detection

##Setup & Installation

1.Clone the GitHub repository:

git clone https://github.com/Bhoomika-gp/Car-Number-Plate-Detection.git


2.Install the necessary dependencies:

pip install opencv-python


3.Download the pre-trained Haar Cascade file
haarcascade_russian_plate_number.xml
and place it inside the model folder.

##How to Run

1.Execute the detection script:

python number_plate.py


2.A webcam window will open showing the live video feed.

3.The system automatically detects number plates and draws bounding boxes around them with the label “Number Plate”.

4.Press the s key to save the detected plate image. Saved images will be stored in the plates directory.
##project Structure
```
car-number-plate-detection/
│
├── model/
│   └── haarcascade_russian_plate_number.xml  # Haar Cascade model for plate detection
│
├── plates/
│   └── scanned_img_0.jpg  # Sample detected plate images
│   └── scanned_img_1.jpg
│   └── ... (more saved plate images)
│
├── LICENSE                  # Project license file (MIT)
├── README.md                # Project documentation
├── easy_OCR.ipynb           # OCR notebook for text extraction
├── number_plate.py          # Main detection script
└── requirements.txt         # List of required dependencies
```
