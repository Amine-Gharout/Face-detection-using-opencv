# Face Detection with OpenCV 🖼️👤

## Description  
This Python script detects faces in an image using OpenCV's Haar cascade classifier. It identifies faces in the input image, draws rectangles around detected faces, and displays the processed image.

---

## How It Works 🚀  

1. **Image Loading**:  
   - The script reads the input image using OpenCV's `imread()` function.  

2. **Grayscale Conversion**:  
   - The image is converted to grayscale for better performance during face detection.  

3. **Face Detection**:  
   - The Haar cascade classifier (`haarcascade_frontalface_default.xml`) is used to detect faces in the grayscale image.  
   - The `detectMultiScale()` method scans the image and identifies bounding boxes for detected faces.

4. **Drawing Rectangles**:  
   - Rectangles are drawn around the detected faces on the original image using `rectangle()`.

5. **Displaying the Result**:  
   - The processed image is displayed in a window using `imshow()` until a key is pressed.

---

## Usage Instructions 🛠️  

### Prerequisites:  
- Python installed on your system (preferably version 3.6+).  
- OpenCV library installed. Use the following command to install OpenCV:  
  ```bash
  pip install opencv-python
