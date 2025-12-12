This project develops an object detection system for Survue, a cyclist safety startup building AI-powered bike lights. The system detects vehicles, pedestrians, and traffic signs in real-time from bike-mounted cameras to provide early warnings and enhance cyclist safety.

To run the models, user has to place the survue dataset(coco formatted data) in the survue_project folder and run the survue.ipynb file step by step. This will create three different models (nano, small, small with augmentation).

The inference.ipynb file can run the model on any input dash cam video to generate the inference to show how the model works in predicting objects in real settings.

Key Results

Best Model: YOLOv8s achieving 57.75% mAP@0.5
Vehicle Detection: 70.2% mAP (production-ready)
Lightweight: 6-22 MB models suitable for edge deployment
