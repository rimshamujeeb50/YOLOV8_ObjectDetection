# YOLOV8_ObjectDetection
This Repository contains files pertaining to the Yolov8 Object detection system developed.

Dataset Link: https://universe.roboflow.com/eepdatasets-fe5sq/eep_detect
(Note:Retrieve the dataset in either YOLOv8 or YOLOv5 PyTorch format.)

STEPS FOR EXECUTING FILES FROM THIS REPOSITORY:

•	Step 1: Upload the zipped dataset folder to your Google Drive.

•	Step 2: Duplicate the EEP_detection.ipynb file in Colab and commence training step by step.

•	Step 3: Upon completing the training, retrieve the best.pt model file from the runs->Detect->weights folder.

•	Step 4: Access the "Yolo_model" folder using any Python-compatible IDE.
(Note: It is recommended to create a virtual environment for your project before proceeding.)

•	Step 5: Install all the necessary dependencies and replace the Fire.py script with your best.pt model.

•	Step 6: Execute the Flask script to generate a local server-compatible link and observe the model's functionality.

•	Step 7: Follow the link generated in the IDE console to access your Web Interface.

Explore the interface.
