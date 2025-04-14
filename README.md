# 🧼 Total Variation Denoising (TVD) in Python

This repository demonstrates the application of **Total Variation Denoising (TVD)** using the `skimage.restoration.denoise_tv_chambolle` method on both:

- 🟢 1D noisy signals (e.g., sine wave)
- ⚫ 2D grayscale images (e.g., sample camera image)

TVD is a powerful regularization technique used to reduce noise while preserving edges and important features in the signal or image.

---

## 📂 Contents

- `signal_denoising.py` - Denoising a noisy sine wave using TVD.
- `image_denoising.py` - Denoising a grayscale image using TVD and visualizing the effects.
- `histogram_analysis.py` - Comparing pixel intensity distributions of original, noisy, and denoised images using Seaborn histograms.

---

## 🧪 Dependencies

Make sure you have the following Python libraries installed:

```bash
pip install numpy matplotlib seaborn scikit-image pandas
```

---

## 🧭 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/tvd-denoising.git
cd tvd-denoising
```

2. Run the scripts:

```bash
python signal_denoising.py
python image_denoising.py
python histogram_analysis.py
```

Each script will generate visualizations showing the effectiveness of TVD in removing noise.

---

## 📈 Example Outputs

### 📉 Signal Denoising (1D)
Displays:
- Original signal (sine wave)
- Noisy signal
- Denoised signal (using TVD)

### 🖼️ Image Denoising (2D)
Displays:
- Original image (`camera` from `skimage.data`)
- Noisy image (Gaussian noise)
- Denoised image
- Histogram comparison of pixel intensities (Original vs Noisy vs Denoised)

---

## 📌 Notes

- TVD is great for denoising while **preserving important edges** in images and signals.
- The regularization parameter `weight` (lambda) controls the trade-off between **smoothness** and **fidelity to original data**.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## ✨ Acknowledgements

- [`scikit-image`](https://scikit-image.org/)
- [`matplotlib`](https://matplotlib.org/)
- [`seaborn`](https://seaborn.pydata.org/)
