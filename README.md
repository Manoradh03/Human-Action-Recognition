# Human Action Recognition

This project is a web application built using Flask that utilizes a pre-trained I3D model for human action recognition in videos. Users can upload a video and receive predictions for the top five actions detected in the video.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [License](#license)

## Features

- Upload a video file for action recognition.
- Predict the top 5 actions with their probabilities.
- Display a generated GIF from the uploaded video.
- User-friendly interface built with Bootstrap.

## Requirements

- Python 3.x
- Flask
- TensorFlow
- TensorFlow Hub
- NumPy
- OpenCV
- Imageio

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Manoradh03/Human-Action-Recognition.git
   cd flask_app
   ```

2. **Install the required packages:**

   You can install the required packages using pip. It is recommended to use a virtual environment for your project, but if you prefer to install them globally, you can run:

   ```bash
   pip install -r Requirements.txt
   ```

3. **Run the application:**

   Start the Flask application:

   ```bash
   python app.py
   ```

   The application will be running at `http://127.0.0.1:5000`.

## Usage

1. Open your web browser and navigate to `http://127.0.0.1:5000`.
2. Click on the "Select a Video" button to upload a video file.
3. After selecting a video, click on the "Upload and Predict" button.
4. Wait for the predictions to be displayed along with the generated GIF.

## File Structure

```plaintext
my_flask_app/
├── app.py                     # Main application file
├── Requirements.txt           # Required Python packages
├── data/
│   └── label_map.txt         # Kinetics-400 action labels
├── static/
│   ├── css/
│   │   └── styles.css         # Custom CSS styles
│   └── js/
│       └── script.js          # Custom JavaScript
├── templates/
│   └── index.html             # HTML template for the application
```

## License
### Instructions
This project is licensed under the MIT License. See the LICENSE file for more information.
```
1. Replace `Manoradh03` and `Human-Action-Recognition` with your actual GitHub username and repository name.
2. Save the README file as `README.md` in the root of your project directory.
3. Add, commit, and push your changes to your GitHub repository.
```
