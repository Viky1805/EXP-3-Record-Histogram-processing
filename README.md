# EXP-3-Record-Histogram-processing

# Histogram Equalization Using OpenCV (Grayscale & Color Images)

---

## Aim

To write a Python program using OpenCV to perform histogram equalization on both grayscale and color images to enhance image contrast and brightness.

The program performs the following operations:

- Read and display a grayscale image  
- Plot histogram of the grayscale image  
- Apply histogram equalization on grayscale image  
- Read and display a color image  
- Plot histogram of B, G, R channels  
- Convert image to HSV color space  
- Apply histogram equalization on the Value (V) channel  
- Convert the enhanced image back to BGR format  
- Display original and enhanced images with histograms  

---

## Software Used

- Anaconda – Python 3.7  
- Jupyter Notebook / VS Code  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  

---

## Algorithm

### Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2:
Read the image `parrot.jpg` in grayscale format.

### Step 3:
Display the grayscale image and plot its histogram.

### Step 4:
Apply histogram equalization using `cv2.equalizeHist()` to enhance contrast.

### Step 5:
Display original grayscale image, its histogram, enhanced image, and its histogram using a 2 × 2 grid.

### Step 6:
Read the same image in color format.

### Step 7:
Split the image into B, G, R channels and plot their histograms.

### Step 8:
Convert the image from BGR to HSV color space.

### Step 9:
Apply histogram equalization on the V (Value) channel.

### Step 10:
Merge the channels and convert the image back to BGR format.

### Step 11:
Display original color image, histogram, enhanced image, and enhanced histogram using a 2 × 2 grid.

---

## Program

### Developed By:
**Name: Vignesh S**  

### Register No: 212224110061

---

##  Output

### Grayscale Histogram Equalization

- Original grayscale image is displayed  
- Histogram of original grayscale image is plotted  
- Enhanced image after histogram equalization is displayed  
- Histogram of enhanced grayscale image shows improved contrast  

### Color Image Histogram Equalization

- Original color image is displayed  
- Histogram of B, G, R channels is plotted  
- Enhanced image after HSV-based equalization is displayed  
- Histogram of enhanced image shows better intensity distribution

<img width="692" height="493" alt="image" src="https://github.com/user-attachments/assets/f528f32f-4f8a-447a-a80a-e37d1b0373e7" />


<img width="733" height="535" alt="image" src="https://github.com/user-attachments/assets/392b773b-8299-4f44-9b98-688ad07fc8d1" />

  
<img width="720" height="542" alt="image" src="https://github.com/user-attachments/assets/d6d2328d-2337-4f9b-999a-b6edb92aafa6" />

<img width="713" height="488" alt="image" src="https://github.com/user-attachments/assets/22f04dfe-6397-4bc4-b498-5f2589b2d1e5" />

<img width="705" height="485" alt="image" src="https://github.com/user-attachments/assets/edb6a7e2-46ad-4633-a54b-8a5bda42dd84" />

<img width="731" height="538" alt="image" src="https://github.com/user-attachments/assets/3ab5b8bb-a1ee-4631-9b7e-c3e78394707e" />

<img width="1373" height="392" alt="image" src="https://github.com/user-attachments/assets/0c3bef12-a8a7-4c2b-8c00-4f536e6a70b1" />

<img width="1386" height="415" alt="image" src="https://github.com/user-attachments/assets/5f60c00b-b206-43ea-90b1-99f070fb3c52" />





---

## Result

Thus, histogram equalization is successfully performed on both grayscale and color images using OpenCV. The contrast and brightness of the images are significantly improved, enhancing visual quality and feature visibility.

Thus, histogram equalization is successfully performed on both grayscale and color images using OpenCV. The contrast and brightness of the images are significantly improved, enhancing visual quality and feature visibility.
