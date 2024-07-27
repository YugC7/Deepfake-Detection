# Deepfake Detection Module and UI

## Introduction

Welcome to the Deepfake Detection Module and UI, developed by Team Data Gurus. This repository contains a Python-based module for detecting deepfakes and a user-friendly web interface for uploading and analyzing videos. Deepfake videos pose significant challenges in various domains, and our solution aims to provide an effective and accessible way to identify such content.

## Features

- **Deepfake Detection**: Utilizes state-of-the-art machine learning models to detect deepfake videos.
- **Reliability**: Trained and tested on a Dataset of 1500 images, this model can easily detect most deepfake videos and photos.
- **User-Friendly UI**: A web-based interface to easily upload and analyze videos.
- **Detailed Reports**: Generates comprehensive reports on the analyzed videos.
- **Scalable**: Designed to handle multiple video uploads and analysis simultaneously.

## Table of Contents

- [Installation](#installation)
- [Modules](#modules)
- [Contributing](#contributing)
- [Copyright](#Copyright)

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)
- Streamlit library for UI

### Clone the Repository

```bash
git clone https://github.com/teamdatagurus/deepfake-detection.git
cd deepfake-detection
```

### Backend Setup

1. Create a virtual environment and activate it:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

2. Install the required Python packages:

```bash
pip install -r requirements.txt
```
3. Run UI
''' bash
streamlit run streamlit_deepkfake_detector.py
```

The UI should now be running at `http://localhost:3000`.

### Using the UI

1. Open your browser and go to `http://localhost:3000`.
2. Upload the video file you want to analyze.
3. Wait for the analysis to complete and view the results.

## Modules

### Deepfake Detection

The core module for detecting deepfakes is located in the `deepfake_detection` directory. It contains the following components:

- **model.py**: Defines the machine learning model used for detection.
- **preprocessing.py**: Contains functions for preprocessing video files.
- **inference.py**: Handles the inference logic to detect deepfakes.
- **utils.py**: Utility functions for various tasks.

### User Interface

The UI is built with React and is located in the `ui` directory. It contains the following components:

- **App.js**: Main component of the UI.
- **Upload.js**: Handles the video upload functionality.
- **Results.js**: Displays the results of the analysis.
- **api.js**: Contains functions for communicating with the backend.

## Contributing

We welcome contributions from the community. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push the branch to your fork.
4. Open a pull request with a detailed description of your changes.

Please ensure that your code adheres to our coding standards and includes appropriate tests.

## Copyright

This project is a property of Team Data Gurus by DigiNexus TechHub Pvt. Ltd. Copying is prohibited.
---

Feel free to customize this README further to better fit your project's specifics!
