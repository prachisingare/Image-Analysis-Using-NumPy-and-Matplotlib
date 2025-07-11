# Image-Analysis-Using-NumPy-and-Matplotlib
 “A beginner-friendly project on image analysis using NumPy and Matplotlib to understand image structure and RGB manipulation. This project demonstrates how a digital image can be **interpreted, analyzed, and transformed** using basic image processing techniques in Python with the help of **NumPy**, **PIL**, and **Matplotlib**."

### 🧾 Key Concepts Covered

- ✅ Understanding images as multidimensional NumPy arrays (matrices)
- ✅ Creating artificial grayscale images using `np.ones()` and `np.zeros()`
- ✅ Loading and converting a JPEG image to a 3D matrix using `PIL.Image` and `np.asarray()`
- ✅ Extracting individual color channels (Red, Green, Blue)
- ✅ Modifying specific channels to observe the effect on image appearance
- ✅ Visualizing the color intensities using various color maps like `gray`, `Reds`, `Blues`, etc.

### 📌 Image Matrix Representation

After loading the image `Shivaji Maharaj Fort.jpeg`, it was converted into a NumPy array:

```python
from PIL import Image
import numpy as np

img = Image.open("Shivaji Maharaj Fort.jpeg")
img_array = np.asarray(img)
print(img_array.shape)  # Output: (602, 602, 3)


---

## 🧪 Technologies Used

| Tool/Library | Purpose                          |
|--------------|----------------------------------|
| Python 3.10+ | Core programming language        |
| NumPy        | Matrix operations & manipulations|
| Matplotlib   | Image and data visualization     |
| PIL (Pillow) | Loading and handling image files |
| JupyterLab   | Interactive notebook environment |

---

## 🧬 Key Concepts Demonstrated

- **Image as Array**: Each image is a 3D NumPy array — shape `(height, width, 3)` for RGB.
- **Matrix Manipulation**: Using NumPy to manipulate brightness, mask channels, copy data.
- **Channel Visualization**: Visualize Red, Green, and Blue components separately.
- **Color Mapping**: Use color maps (`cmap`) to visualize grayscale representations.
- **Pixel Value Understanding**: Visual inspection of RGB values and image composition.

---

## 💡 Sample Code Highlights

### Load Image and Convert to Array
```python
from PIL import Image
import numpy as np

img = Image.open("Shivaji Maharaj Fort.jpeg")
img_array = np.asarray(img)
print(img_array.shape)  # Output: (602, 602, 3)


🎯 Learning Outcomes
Understand the structure and representation of digital images

Apply matrix operations to manipulate images

Separate and analyze individual RGB channels

Explore how simple NumPy logic can reshape visual data

Gain exposure to image processing fundamentals using pure Python

📸 Sample Outputs
✔️ Original colored image

✔️ Red-only, Green-only, and Blue-only images

✔️ Grayscale color-mapped images using individual channels

✔️ White/Black images using synthetic NumPy arrays


