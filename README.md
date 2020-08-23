# WildfireDetectionYOLO
This is the team submission for [Let's Stop Wildfires Hackathon 2.0](https://aiformankind.org/lets-stop-wildfires-hackathon-2.0). Hosted by AI For Mankind. All credit goes to [AI For Mankind](https://github.com/aiformankind/wildfire-smoke-detection-camera) for providing participants with the [annotated dataset and quickstart repo](https://github.com/aiformankind/wildfire-smoke-dataset).
### Our Team
1. Santiago Perez Alvarado
2. Surbhi Gupta
3. Alan ShangGuan
4. Davies Odu
5. Aarnav Sawant
### Steps to Run Inference with our Model
1. Clone this repository with ```git clone https://github.com/AarnavSawant/WildfireDetectionYOLO.git```
2. Navigate to the directory with ```cd WildfireDetectionYOLO```
3. Install all system requirements with ```pip install -r requirements.txt```
4. Run detect.py with ```python3 detect.py --weights best.pt --source PATH/TO/IMAGES/OR/IMAGEDIRECTORY/OR/VIDEO --output OUTPUT_DIRECTORY --save-txt```
5. To see the images and annotations, go to the OUTPUT_DIRECTORY. The coordinates for the bounding boxes are in the format [Class, y_min, y_max, x_min, x_max]
