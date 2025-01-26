# Fashion Recommendation System

This project named as  **Fashion Recommendation System** built using **Streamlit** for the frontend and TensorFlow for image processing and feature extraction. It helps users find similar fashion items based on uploaded images which helps Bussiness to recommend products based on users preferences and analytics..

---

## Dataset

Download the dataset from [here](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small).

---

## Features
- Upload an image of a fashion item.
- The system finds visually similar items from a pre-trained dataset.
- Uses **ResNet50** for feature extraction and **K-Nearest Neighbors (KNN)** for similarity search.

---

## Installation and Setup

### Prerequisites
Ensure you have Python 3.8+ installed on your system. Then, follow the steps below to set up and run the project.

### Step 1: Clone the Repository
```bash
# Clone the repository
git clone https://github.com/yourusername/fashion-recommendation-system.git
cd fashion-recommendation-system
```

### Step 2: Install Dependencies
```bash
# Install required libraries
pip install -r requirements.txt
```

### Step 3: Download the Model and Dataset
- Pre-trained ResNet50 weights are used for feature extraction.
- Ensure your dataset of images is stored in the `dataset/` folder.

Place your pre-trained model and feature files in the appropriate directory.

### Step 4: Run the Application
Run the Streamlit app using the following command:
```bash
streamlit run final.py
```

---

## File Structure
```
.
|-- app.py                    # Main Streamlit app file
|-- requirements.txt          # List of dependencies
|-- dataset/                  # Folder containing images for recommendations
|-- models/                   # Folder for pre-trained models and features
|-- utils.py                  # Utility functions for preprocessing
```

---

## Usage
1. Start the application using `streamlit run app.py`.
2. Upload a fashion item image using the file uploader.
3. The system will display similar items based on the uploaded image.

---

## Dependencies
- Streamlit
- TensorFlow
- NumPy
- OpenCV
- Pillow
- Scikit-learn
- Tqdm

---

## Contributing
Contributions are welcome! Feel free to fork the repository and create a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.




