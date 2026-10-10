# Flower Species Recognition
Developed as part of an AI & Deep Learning course at **ESIEE Paris (2026)** by **Théo Khuoy** and **Axel Durand**.

## Project Overview
Identifying **flower species** from photos is a challenge because the same species can look very different depending on lighting, orientation, and scale, while different species can also look very similar to each other.

- **Architecture:** MobileNet pre-trained on ImageNet used as a feature extractor, followed by fine-tuning of the final layers.
- **Dataset:** Flowers Recognition dataset from Kaggle containing **4,317 images** across **5 categories**: *daisy, dandelion, rose, sunflower, and tulip*.
- **Performance:** Achieves an accuracy of **87.9%** on the validation set.

## Project Structure
- `docs/` : IEEE paper assets
- `images/` : Sample images
- `.gitignore` : Git exclusion
- `flower_recognition.ipynb` : Main Jupyter Notebook

## Configuration & Usage

### Requirements
Dependencies :
* Python 3.8+
* TensorFlow / Keras
* NumPy, Matplotlib, Jupyter

Installation :
```bash
pip install tensorflow numpy matplotlib jupyter```