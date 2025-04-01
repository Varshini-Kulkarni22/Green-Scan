
# Green Scan (AI crop disease prediction and management)

Green Scan (AI crop disease prediction and management) is a plant disease detection application that leverages deep learning techniques. The application uses TensorFlow's MobileNetV2 model to identify plant diseases from leaf images. It also integrates with MongoDB for data storage.

## Features
- Upload leaf images to detect plant diseases.
- Uses MobileNetV2 for efficient image classification.
- Web interface built with Flask.
- Stores results in MongoDB.

## Prerequisites
- Python 3.x
- MongoDB

## Usage

1. Start the Flask server:
    ```bash
    python app.py
    ```

2. Open your browser and go to `http://localhost:5000` to use the application.

## Project Structure
```
Green-Scan/
│   app.py                    # Main application file
│   model_development.ipynb   # Jupyter notebook for model development
│   requirements.txt          # List of dependencies
│
├── static/                   # Static image assets
│   └── ...                   # Leaf images for disease detection
├── plant disease/            # Diseased plant images
│   └── ... 
└── templates/                # HTML templates for the web interface
    └── ...                   # HTML files for Flask routing
```

## Dependencies
- Flask
- TensorFlow
- Pillow
- OpenCV
- NumPy
- PyMongo


## License
This project is licensed under the MIT License - see the LICENSE file for details.
