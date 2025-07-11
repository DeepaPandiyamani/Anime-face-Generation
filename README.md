

# 🎭 FaceGen — Anime Face Generation using DCGAN

FaceGen is a deep learning mini-project that uses **Deep Convolutional Generative Adversarial Networks (DCGAN)** to generate high-quality, realistic **anime-style faces**. It involves training a generative model to learn the complex patterns of anime characters using adversarial learning.

---

## 🧠 Overview

This project explores the capabilities of **Generative Adversarial Networks (GANs)** in synthesizing anime images from random noise. It includes data preprocessing, model architecture design, training, and performance evaluation.

---

## 🚀 Key Features

* 🎨 Generates realistic anime-style faces.
* 🔁 Trained using adversarial learning on a large anime image dataset.
* ⚙️ Built with TensorFlow and Keras.
* 📈 Evaluated visually and numerically to assess image realism and diversity.

---



---

## 🛠️ Tech Stack

* **Python**
* **TensorFlow & Keras**
* **NumPy, Matplotlib**
* **DCGAN (Deep Convolutional GAN)**

---

## 📊 Model Architecture

* **Generator**: Transforms random noise vectors into 64x64 RGB images using transpose convolution layers.
* **Discriminator**: Classifies real vs. generated images using CNN layers.

---

## 📈 Training

* Images are normalized to \[-1, 1].
* Loss Function: Binary Cross-Entropy
* Optimizers:

  * Generator: Adam (lr=0.0003)
  * Discriminator: Adam (lr=0.0001)
* Epochs: 50

---

## 🖼️ Sample Output

<img width="248" height="185" alt="image" src="https://github.com/user-attachments/assets/d8615124-bd55-4388-89af-25d33cdfb27f" />


---

## 🔬 Evaluation

* Compared real vs. generated images visually.
* Tracked loss curves for generator and discriminator.
* Ensured image diversity and realism.

---

## 🌱 Future Enhancements

* Conditional GANs for attribute-based generation (e.g., hair color, emotion).
* Advanced architectures like **Self-Attention GAN**, **Wasserstein GAN**.
* Anime style transfer and semantic editing.
* Generate sketches, line-art, and colored variants.

---

## ✅ Conclusion

This project demonstrates how **DCGANs** can be effectively used to synthesize anime-style faces. It serves as a foundation for creative applications in **digital art, animation, and gaming**.

---

## 👩‍💻 Developed By

**Deepa P**

National Engineering College, Kovilpatti

---

