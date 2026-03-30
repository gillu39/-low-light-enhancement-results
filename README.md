# Low-Light Image Enhancement using Zero-Shot Learning and Depthwise Separable Convolution

This repository presents the results of our published research on low-light image enhancement using a lightweight deep learning framework.

---

## 📄 Publication

**Title:** Zero-shot learning with depthwise separable convolution for low-light image enhancement using hybrid perceptual loss

**Journal:** Journal of Real-Time Image Processing

🔗 Read full paper:
https://link.springer.com/article/10.1007/s11554-025-01744-5

---

## ✨ Highlights

* ✔ Zero-shot low-light image enhancement (no paired data required)
* ✔ Operates on HSV color space using only the V (Value) channel
* ✔ Lightweight model (~4058 parameters) for real-time applications
* ✔ Uses Depthwise Separable Convolution (DSC) for efficiency
* ✔ Hybrid perceptual loss:

  * Exposure loss
  * Illumination loss
  * Gram matrix texture loss
* ✔ Preserves structural details and natural appearance
* ✔ Suitable for resource-constrained devices

---

## 🧠 Method Overview

The proposed method enhances low-light images through a three-stage pipeline:

1. **HSV Conversion**

   * Input RGB image is converted to HSV
   * Only the V (brightness) channel is processed

2. **Feature Extraction (DSC-based Network)**

   * Lightweight architecture using depthwise separable convolutions
   * Generates parameter maps for enhancement

3. **Pixel-wise Curve Estimation**

   * Iterative enhancement using learned parameter maps
   * Guided by hybrid perceptual loss

4. **Reconstruction**

   * Enhanced V channel is recombined with original H and S
   * Converted back to RGB image

---

## 🖼️ Results

### Side-by-Side Comparison (Dark → Enhanced)

![Result](side_by_side_01.JPG)
![Result](side_by_side_24.JPG)
![Result](side_by_side_3.bmp)
![Result](side_by_side_Kluki.png)
![Result](side_by_side_night fall.JPG)

---

## ⚠️ Note

This repository provides **result visualization only**.
The full implementation is not publicly released to protect ongoing research work.

---

## 👩‍🎓 Author

**Supriya Singh**
PhD Research Scholar
Department of Computer Science
Babasaheb Bhimrao Ambedkar University, Lucknow

---

