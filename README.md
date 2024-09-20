

# Cat vs Dog Classification

## Overview

This project demonstrates the use of a Support Vector Machine (SVM) for classifying images of cats and dogs. The model is trained using Scikit-Learn and OpenCV for image preprocessing.

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/cat-vs-dog-svm.git
    cd cat-vs-dog-svm
    ```

2. **Setup Virtual Environment and Install Dependencies:**

    ```bash
    python -m venv env
    env\Scripts\activate  # On Windows
    source env/bin/activate  # On macOS/Linux
    pip install -r requirements.txt
    ```

3. **Training the Model:**

    Place your dataset in the `data` folder and run the `train_model.py` script to train the SVM model.

    ```bash
    python train_model.py
    ```

4. **Testing the Model:**

    Use the `test_model.py` script to evaluate the model on your test images.

    ```bash
    python test_model.py
    ```

## Project Structure

- `train_model.py`: Script to train the SVM model.
- `test_model.py`: Script to test the trained model.
- `requirements.txt`: Python dependencies.
- `data/`: Directory to store the dataset.

## Technologies

- **Machine Learning:** Scikit-Learn
- **Image Processing:** OpenCV, NumPy

## License

Licensed under the MIT License.
