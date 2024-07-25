# Leaf Disease Detection

Leaf Disease Detection is a project that uses machine learning and computer vision techniques to identify and classify diseases in plant leaves. The application is built with Python and uses Streamlit for the front-end interface, allowing users to upload images of leaves and get predictions about potential diseases.

## Features

- Detects and classifies different types of leaf diseases.
- User-friendly web interface built with Streamlit.
- Provides a confidence score for each prediction.
- Supports multiple types of plants and diseases.

## Technologies Used

- **Python**: The main programming language used for developing the project.
- **Streamlit**: Used for building the interactive web interface.
- **OpenCV**: For image processing and manipulation.
- **TensorFlow/Keras**: Used for building and training the machine learning model.
- **NumPy & Pandas**: For data manipulation and analysis.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/leaf-disease-detection.git
    cd leaf-disease-detection
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

## Usage

- Open your web browser and go to `http://localhost:8501`.
- Upload an image of a leaf using the file uploader.
- Click on the "Predict" button to get the disease prediction and confidence score.

## Dataset

The model was trained on a publicly available dataset containing images of healthy and diseased leaves. The dataset includes the following categories:

- Healthy
- Powdery Mildew
- Rust
- Bacterial Spot
- Early Blight

## Model

The project uses a convolutional neural network (CNN) architecture trained on the aforementioned dataset. You can find the model architecture and training details in the `model` directory.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- The dataset used in this project was sourced from [Kaggle/Other Source](https://www.kaggle.com).
- Inspiration for the project structure was taken from various open-source repositories.

## Contact

For any questions or issues, please open an issue in the repository or contact me at [your-email@example.com](mailto:your-email@example.com).

---

Thank you for using Leaf Disease Detection!
