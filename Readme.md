
# Fashion Recommendation System

Welcome to the **Fashion Recommendation System**, a user-friendly platform built using **Streamlit** and **TensorFlow**. This system allows users to discover visually similar fashion items by simply uploading an image. It’s perfect for businesses looking to enhance their product recommendations based on customer preferences and analytics.

---

## 📂 Dataset

The dataset can be downloaded from [this Kaggle link](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small).  
Ensure the dataset is stored in the `images/` folder as outlined in the **File Structure** section.

---

## ✨ Features
- 🔄 **Image Upload**: Upload an image of a fashion item to get recommendations.
- 🤖 **AI-Powered Recommendations**: Finds visually similar items using **ResNet50** for feature extraction.
- 🚀 **Fast Search**: Employs **K-Nearest Neighbors (KNN)** for efficient similarity searches.

---

## 🛠️ Installation and Setup

### Prerequisites
- Python version: **3.8+**
- Ensure `pip` is installed on your system.

### Step-by-Step Guide

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/sahil-D-scientist/project_Fashion_recommendation_app.git
   cd fashion-recommendation-system
   ```

2. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare Dataset and Model**  
   - Download and store the dataset in the `dataset/` folder.
   - Place pre-trained ResNet50 weights and any feature files in the `models/` directory.

4. **Run the Application**  
   Launch the Streamlit app with:  
   ```bash
   streamlit run final.py
   ```

---

## 🗂️ File Structure

```plaintext
fashion-recommendation-system/
├── app.py                # Main Streamlit app file
├── requirements.txt      # List of required dependencies
├── dataset/              # Folder for images used for recommendations
├── models/               # Folder containing pre-trained models and features
├── utils.py              # Utility functions for preprocessing
```

---

## 🚀 How to Use
1. Run the application with:
   ```bash
   streamlit run app.py
   ```
2. On the app interface:
   - Upload a fashion item image via the file uploader.
   - View visually similar recommendations from the pre-trained dataset.

---

## 📦 Dependencies

This project uses the following Python libraries:
- **[Streamlit](https://streamlit.io/)** - For building the interactive web app.
- **[TensorFlow](https://www.tensorflow.org/)** - For deep learning and feature extraction.
- **[NumPy](https://numpy.org/)** - For numerical operations.
- **[OpenCV](https://opencv.org/)** - For image processing.
- **[Pillow](https://python-pillow.org/)** - For handling images.
- **[Scikit-learn](https://scikit-learn.org/)** - For KNN similarity search.
- **[Tqdm](https://tqdm.github.io/)** - For progress bars.

Install all dependencies using:
```bash
pip install -r requirements.txt
```

---



## 📜 License

This project is licensed under the MIT License. See the full license [here](https://opensource.org/licenses/MIT).

