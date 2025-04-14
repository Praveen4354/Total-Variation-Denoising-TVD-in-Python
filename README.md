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
