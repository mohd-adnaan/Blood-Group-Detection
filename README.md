**Blood Group Detection using Image Preprocessing Techniques and YOLOv5**

**Introduction:**
This project aims to detect blood groups from images utilizing image preprocessing techniques followed by comparison of results with YOLOv5, a state-of-the-art object detection model.

**Objective:**
The primary objective is to accurately detect and classify blood groups from images, enabling efficient automation in medical processes.

**Methodology:**
1. **Image Preprocessing Techniques:**
   - Utilize OpenCV for image preprocessing, including color space transformation, contrast enhancement, and noise reduction.
   - Implement techniques such as CLAHE (Contrast Limited Adaptive Histogram Equalization) to enhance image quality.
   - Segment blood cells from the preprocessed images using morphological operations and thresholding.
   - Extract relevant features from the segmented cells for classification.

2. **YOLOv5 Object Detection:**
   - Employ YOLOv5, a deep learning-based object detection model, for blood group detection.
   - Train the YOLOv5 model on a labeled dataset of blood group images.
   - Fine-tune the model to improve detection accuracy and robustness.

3. **Result Comparison:**
   - Compare the results obtained from image preprocessing techniques with those from YOLOv5.
   - Evaluate the accuracy, precision, and recall of each method.
   - Analyze the strengths and limitations of both approaches.

**Dependencies:**
- OpenCV
- YOLOv5
- Python 3.x

**Usage:**
1. Clone the repository.
2. Install the required dependencies.
3. Preprocess the images using the provided techniques.
4. Train and evaluate the YOLOv5 model on the dataset.
5. Compare the results obtained from image preprocessing with those from YOLOv5.
