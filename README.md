This project uses deep learning-based object detection (e.g., YOLOv5 or Faster R-CNN) to identify objects in video frames, and object tracking algorithms (e.g., SORT or Deep SORT) to assign persistent IDs and track objects over time.

Detection: YOLOv5 for real-time bounding box generation

Tracking: Deep SORT for ID assignment using Kalman filters + appearance embeddings

Libraries: OpenCV, PyTorch, YOLO, NumPy
