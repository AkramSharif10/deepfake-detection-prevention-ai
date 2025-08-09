# AI-Powered Deepfake Detection

[![Python Version](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red.svg)](https://streamlit.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An intuitive web application built with Python and Streamlit to detect deepfakes in images using a trained AI model. This project provides a user-friendly interface to analyze images and distinguish between authentic and manipulated content.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Demo](#demo)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview

In an era of rising digital misinformation, the ability to discern real images from AI-generated fakes is crucial. This project addresses this challenge by providing a simple yet powerful tool for deepfake detection. By uploading an image to the web interface, users can leverage a pre-trained machine learning model to get an instant prediction on whether the image is real or fake.

## Key Features

-   **User-Friendly Interface:** A simple web app powered by Streamlit for easy image uploads.
-   **AI-Powered Detection:** Utilizes a trained neural network to analyze images for signs of manipulation.
-   **Instant Feedback:** Provides immediate results, classifying an image as "Real" or "Fake".
-   **Easy to Set Up:** The project is self-contained and can be run locally with minimal setup.

## Demo

Here is a quick look at the application's interface and functionality.

**1. Main Application Interface:**
<br/>

**2. Analyzing a 'Fake' Image:**
<br/>

**3. Analyzing a 'Real' Image:**
## Technology Stack

-   **Backend:** Python
-   **AI / Machine Learning:** TensorFlow, Keras, OpenCV
-   **Web Framework:** Streamlit
-   **Core Libraries:** NumPy, Pillow

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

-   Python 3.9 or higher
-   `pip` (Python package installer)

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/AkramSharif10/deepfake-detection-prevention-ai.git](https://github.com/AkramSharif10/deepfake-detection-prevention-ai.git)
    cd deepfake-detection-prevention-ai
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```sh
    # For Windows
    python -m venv venv
    venv\Scripts\activate

    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```
    *(Note: If you don't have a `requirements.txt` file, you can create one by running `pip freeze > requirements.txt` after installing the necessary packages like `streamlit`, `tensorflow`, etc.)*

## Usage

Once the installation is complete, run the following command in your terminal to start the Streamlit application:

```sh
streamlit run app.py
A new tab will automatically open in your default web browser at http://localhost:8501. From there, you can upload an image to analyze it.


