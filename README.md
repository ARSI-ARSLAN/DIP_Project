# Traffic Sign Classification Using Classical Image Processing 

This project demonstrates several fundamental **Digital Image Processing (DIP)** techniques using Python.  
The implementation focuses on **image preprocessing, filtering, enhancement, and edge detection** to analyze and improve image quality.

The project is implemented in **Python using Jupyter Notebook** and uses common image processing libraries.

---

# Project Objectives

The main objectives of this project are:

- Load and store images for processing
- Apply different **image filtering techniques**
- Perform **image enhancement**
- Detect edges in images
- Visualize the results of different processing methods

---

# Techniques Implemented

The project includes the following Digital Image Processing operations:

### 1. Image Loading
Images are read from disk and stored for further processing.

### 2. Image Preprocessing
Basic preprocessing is applied before performing filtering operations.

### 3. Mean Filter
A **Mean Filter** is used to smooth the image by reducing noise through averaging neighboring pixels.

### 4. Gaussian Filter
The **Gaussian Filter** applies a weighted smoothing technique that reduces noise while preserving image structure.

### 5. Median Filter
The **Median Filter** is used to remove **salt-and-pepper noise** by replacing each pixel with the median of its neighboring values.

### 6. Unsharp Masking
**Unsharp Masking** is used for **image sharpening**, enhancing edges and details by subtracting a blurred version of the image.

### 7. Edge Detection
Edge detection techniques are applied to identify **boundaries and important structures** within the image.

---

# Technologies Used

- Python
- Jupyter Notebook
- OpenCV
- NumPy
- Matplotlib

---

# Project Structure

```
project-folder
│
├── Dip_project.ipynb
├── images/
├── README.md
```

- `Dip_project.ipynb` → Main notebook containing all image processing implementations  
- `images/` → Folder containing input images used for processing  
- `README.md` → Project documentation  

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/digital-image-processing-project.git
cd digital-image-processing-project
```

Install required dependencies:

```bash
pip install numpy matplotlib opencv-python
```

---

# How to Run

Open the Jupyter notebook:

```bash
jupyter notebook
```

Then open:

```
Dip_project.ipynb
```

Run the cells sequentially to see the image processing results.

---

# Output

The notebook will display:

- Original image
- Filtered images (Mean, Gaussian, Median)
- Sharpened image using Unsharp Masking
- Edge detection results

These outputs allow visual comparison of different processing techniques.

---

# Applications

Digital Image Processing techniques like those used in this project are applied in:

- Medical imaging
- Computer vision
- Object detection
- Image enhancement
- Surveillance systems

---

# Future Improvements

Possible extensions for this project include:

- Implement additional edge detectors (Sobel, Canny, Laplacian)
- Add histogram equalization
- Apply morphological operations
- Process larger image datasets
- Build a simple GUI for interactive processing

---

# Author

Digital Image Processing project developed as part of coursework.
