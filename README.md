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

![Uploaded Image]([<img width="919" height="390" alt="image" src="https://github.com/user-attachments/assets/0cef4890-da7d-4067-be6c-66a02af2f3ed" />
)  
![Color Bar](<img width="919" height="390" alt="image" src="https://github.com/user-attachments/assets/22324e90-9f49-4971-9883-562c8096b353" />
)

**Pie Chart of Color Proportions**

![Pie Chart](<img width="471" height="427" alt="image" src="https://github.com/user-attachments/assets/42649ccb-19b3-4fbc-8c5c-be177fe6ff9c" />

)

**3D Scatter Plot of RGB Pixel Colors**

![3D RGB Plot](<img width="646" height="658" alt="image" src="https://github.com/user-attachments/assets/b191c23b-cedb-4501-b7a5-8858c30605d5" />
)

**3D Cluster Centers (Dominant Colors)**

![3D Clusters](<img width="647" height="658" alt="image" src="https://github.com/user-attachments/assets/d2a3a833-8897-4d15-b92a-4686d8452b83" />
)

---

## 📦 Install Dependencies

```bash
pip install opencv-python-headless matplotlib scikit-learn pillow pandas
