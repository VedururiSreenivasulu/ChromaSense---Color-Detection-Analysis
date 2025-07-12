This project analyzes an uploaded image and extracts its **top dominant colors** using **KMeans clustering**, then generates various visualizations and downloads.

> Built for Google Colab with `scikit-learn`, `Pillow`, `OpenCV`, and `matplotlib`.

---

## 📌 Features

- Upload an image via Colab
- Extract dominant colors using KMeans (`k=5` by default)
- Visualize:
  - Original image
  - Color bar with hex codes
  - Pie chart of color proportions
  - 3D scatter plot of all pixel colors
  - 3D plot of cluster centers
- Export:
  - `dominant_colors_bar.jpg`: Bar image with hex labels
  - `dominant_colors.csv`: RGB and hex values with pixel counts

---

## 🖼️ Example Outputs

> Replace these links after uploading your images to the repo.

**Original Image + Color Bar**

![Uploaded Image](examples/input_image.jpg)  
![Color Bar](examples/dominant_colors_bar.jpg)

**Pie Chart of Color Proportions**

![Pie Chart](examples/pie_chart.jpg)

**3D Scatter Plot of RGB Pixel Colors**

![3D RGB Plot](examples/3d_pixel_distribution.jpg)

**3D Cluster Centers (Dominant Colors)**

![3D Clusters](examples/3d_cluster_centers.jpg)

---

## 📦 Install Dependencies

```bash
pip install opencv-python-headless matplotlib scikit-learn pillow pandas
