# Image Processing with Deep Learning

This project focuses on basic image processing techniques using Python and deep learning libraries. The image of a cow is taken, and various image processing tasks are performed on it, such as converting it to a numpy array, resizing, and converting from RGB to Grayscale.

## Table of Contents
1. [Objective](#objective)
2. [Libraries Used](#libraries-used)
3. [Approach](#approach)
4. [Technologies Used](#technologies-used)
5. [How to Run](#how-to-run)

---

## Objective
The main objectives of this project are:
- **Reading an image file** and converting it to a numpy array.
- **Resizing** the image to fit specific dimensions.
- **Converting the image** from RGB color format to Grayscale.

These operations are performed using Python libraries: `matplotlib.image`, `Pillow`, and `OpenCV (cv2)` in the **Google Colab** environment.

---

## Libraries Used
- **matplotlib.image**: Used to read the image file and convert it into a numpy array.
- **Pillow (PIL)**: Used for image resizing and format conversions.
- **OpenCV (cv2)**: Used for image processing tasks like color space conversion.
  
---

## Approach
1. **Reading the Image**:
   - Loaded an image of a cow using the `matplotlib.image` library.
   - Converted the image into a numpy array for further processing.

2. **Resizing the Image**:
   - Resized the image to a standard dimension using the `Pillow` library.

3. **RGB to Grayscale Conversion**:
   - Converted the image from the RGB format to Grayscale using `OpenCV (cv2)`.

4. **Visualization**:
   - Displayed the original and processed images using `matplotlib`.

---

## Technologies Used
- **Google Colab**: Platform for executing Python code.
- **Python Libraries**:
  - `matplotlib.image`: To load and display images.
  - `Pillow (PIL)`: For image resizing.
  - `OpenCV (cv2)`: For performing the color conversion (RGB to Grayscale).
  

---

This project demonstrates the application of simple image processing techniques using Python, which serve as fundamental steps for more advanced deep learning-based image analysis tasks.
