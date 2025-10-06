# Face-Recognition-System

This project is a face recognition system that identifies whether two uploaded images belong to the same person using deep learning embeddings.

Features
1. Installs and imports the DeepFace library for deep learning–based facial recognition and analysis
2. Uses OpenCV (cv2) for real-time image capture, frame processing, and face detection visualization
3. Detects facial regions in uploaded images using RetinaFace detector backend for accurate bounding box extraction
4. Crops detected face areas and computes 128-dimensional facial embeddings using the Facenet model
5. Compares facial embeddings via Euclidean distance to measure similarity between known and test faces
6. Labels faces as “Same Person” or “Different People” based on distance thresholds (<1.0 for matches)
7. Draws bounding boxes and name labels around detected faces for clear visual feedback
8. Supports multiple uploaded images
