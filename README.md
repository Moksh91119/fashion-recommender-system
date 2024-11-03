# Fashion Recommender System

This is a Fashion Recommender System built with TensorFlow, Streamlit, and k-Nearest Neighbors (k-NN) algorithm. The system uses a deep learning model to extract features from images of clothing items and provides similar item recommendations based on visual similarity.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Contact](#contact)

## Overview

This project is designed to help users find fashion items similar to an uploaded image. Using a pre-trained ResNet50 model, the system extracts features from images and then recommends visually similar items from a dataset of clothing images. The application is deployed using Streamlit, allowing users to upload an image and view recommended items instantly.

## Features

- Image upload functionality.
- Deep feature extraction using ResNet50 (without top layers).
- k-NN search for similar images based on extracted features.
- Displays top 5 similar fashion items.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Moksh91119/fashion-recommender-system.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd fashion-recommender-system
    ```

3. Download or add the dataset of fashion images in the images/ folder.

4. Run app.py to start the Streamlit app:
     ```bash
    streamlit run app.py
    ```

## Usage

1. Start the application by running app.py.
2. Upload an image of a fashion item.
3. The app will display the uploaded image and show the top 5 recommended items visually similar to the uploaded image.

## Dataset

- [Dataset Link](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)
- The dataset consists of images of various fashion items. You can either use your own dataset or download a publicly available dataset of fashion items.
- Ensure the images are placed in the images/ folder before running the feature extraction code in app.py.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: [jainmoksh03@gmail.com](mailto:jainmoksh03@gmail.com)
- **Portfolio**: [itsmemoksh.in](https://itsmemoksh.in/) - Check out my other projects!

---

Contributions and feedback are welcome! Please open an issue or submit a pull request.
