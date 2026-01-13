# Handwritten Mathematical Equation Recognition Using CNN

This project is a web-based application that recognizes and solves handwritten mathematical equations using a Convolutional Neural Network (CNN). It provides a user-friendly interface to either upload an image of an equation or draw it directly on a canvas.

## Features

- **Equation Recognition**: Uses a trained CNN model to recognize handwritten digits and mathematical symbols.
- **Equation Solver**: Solves the recognized equations and provides the result.
- **Input Methods**:
    - **Upload Image**: Upload an image file containing a handwritten equation.
    - **Canvas Drawing**: Draw an equation directly on the screen using the built-in canvas.
- **Web Interface**: Built with Flask for a simple and interactive user experience.

## Tech Stack

- **Backend Framework**: Flask
- **Deep Learning**: TensorFlow / Keras
- **Image Processing**: OpenCV, Pillow (PIL)
- **Computer Algebra**: SymPy
- **Data Handling**: Pandas

## Installation

1.  Clone the repository:
    ```bash
    git clone  https://github.com/cepdnaclk/e20-co542-Handwritten-Mathematical-Equation-Recognition-Using-CNN.git
    cd e20-co542-Handwritten-Mathematical-Equation-Recognition-Using-CNN
    ```

2.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  Run the Flask application:
    ```bash
    python app.py
    ```

2.  Open your web browser and navigate to:
    ```
    http://127.0.0.1:5000/
    ```

3.  **To Use**:
    - **Upload**: Click on "Upload Image" to select a file from your computer.
    - **Canvas**: Click on "Canvas" to draw an equation.
    - Click the "Predict" or "Solve" buttons to get the result.

## Project Structure

- `app.py`: Main Flask application file defining routes and logic.
- `requirements.txt`: List of Python dependencies.
- `train_classifier.ipynb`: Jupyter Notebook used for training the CNN model.
- `eqn-detect-new-model.keras`: Trained model file.
- `equation_calculator.py` & `solve_equation_file.py`: Helper scripts for equation parsing and solving.
- `templates/`: HTML templates for the web interface.
- `static/`: Static files (CSS, JS, images).

