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

![Uploaded Image]   and   ![Color Bar](

<img width="919" height="390" alt="image" src="https://github.com/user-attachments/assets/e2bc1fb8-ce22-434f-9ee6-fea0ebf955c3" />

)  




**Pie Chart of Color Proportions**

![Pie Chart]

(<img width="486" height="427" alt="image" src="https://github.com/user-attachments/assets/bd2847b7-2091-4691-a509-cbaea8bef8ac" />

)

**3D Scatter Plot of RGB Pixel Colors**

![3D RGB Plot]

(<img width="646" height="658" alt="image" src="https://github.com/user-attachments/assets/1353a421-e721-49ae-b8f9-1775f9766d1d" />



)

**3D Cluster Centers (Dominant Colors)**

![3D Clusters]

(<img width="646" height="658" alt="image" src="https://github.com/user-attachments/assets/d39b8c47-96de-48bc-9647-66a56b136a88" />

)

## 📦 Install Dependencies

pip install opencv-python-headless matplotlib scikit-learn pillow pandas

🧑‍💻 Author

Sreenivasulu Vedururi

📧 Feel free to connect via GitHub or LinkedIn.
---
