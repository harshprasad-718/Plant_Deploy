# Plant Disease Detection Application

This project is a Plant Disease Detection application built using Streamlit and TensorFlow. It allows users to upload images of plant leaves and receive predictions about potential diseases, along with severity estimates and additional information about the diseases.

## Project Structure

```
plant-disease-detection-app
├── src
│   ├── main.py               # Main application script
│   ├── disease_info.json     # JSON file containing disease information
│   └── utils.py              # Utility functions for the application
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
└── .streamlit
    └── config.toml          # Streamlit configuration settings
```

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   cd plant-disease-detection-app
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```
   streamlit run src/main.py
   ```

2. Open your web browser and navigate to `http://localhost:8501` to access the application.

3. Upload an image of a plant leaf suspected of having a disease. The application will analyze the image and provide predictions along with severity estimates and additional information about the detected disease.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.