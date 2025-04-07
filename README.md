🧠 Polyp Segmentation in Medical Images using Grad-CAM
This project focuses on semantic segmentation of polyps in colonoscopy images and leverages Grad-CAM (Gradient-weighted Class Activation Mapping) to enhance explainability of model predictions. It aims to aid medical professionals by providing accurate segmentation masks and visual explanations.

📌 Objectives
Perform segmentation of polyps from endoscopic/colonoscopy images.
Use Grad-CAM to provide visual interpretability of CNN-based segmentation models.
Highlight regions of interest (ROIs) that contribute to the model's decision.

🛠️ Technologies Used
Python 🐍
TensorFlow / Keras
OpenCV
NumPy
Matplotlib
Grad-CAM

🗃️ Dataset
Source: Kvasir-SEG Dataset
Contains 1000 colonoscopy images with corresponding ground truth segmentation masks.
Images are annotated for polyps by medical professionals.

🧪 Workflow
Preprocessing: Resize images, normalize, augment data.
Model Training: A CNN-based segmentation model (e.g., U-Net) trained on the dataset.
Prediction: Model generates binary mask for polyp areas.
Grad-CAM Application: Generate heatmaps to visualize important regions influencing the model.
Overlay Visualization: Combine heatmaps with the original image for explainability.

📊 Results
Achieved a high Dice Coefficient / IoU score (insert metrics here).
Grad-CAM heatmaps highlight polyp regions effectively.
Useful for model transparency and clinical validation.
