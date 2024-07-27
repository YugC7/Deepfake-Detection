# Deepfake Detection Module and UI

## Introduction

Welcome to the Deepfake Detection Module and UI, developed by Team Data Gurus. This repository contains a Python-based module for detecting deepfakes and a user-friendly web interface for uploading and analyzing videos. Deepfake videos pose significant challenges in various domains, and our solution aims to provide an effective and accessible way to identify such content.

## Features

- **Deepfake Detection**: Utilizes state-of-the-art machine learning models to detect deepfake videos.
- **Reliability**: Trained and tested on a Dataset of 1500 images, this model can easily detect most deepfake videos and photos.
- **User-Friendly UI**: A web-based interface to easily upload and analyze videos.

## Table of Contents

- [Installation](#installation)
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
pip install streamlit tensorflow cv2 numpy mtcnn
```
3. Run UI

```bash
streamlit run streamlit_deepkafe_detector.py
```

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
