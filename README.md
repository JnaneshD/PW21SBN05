# Image Annotation Based Information Retrieval

This project implements an image annotation and information retrieval system using deep learning techniques and web technologies. It allows users to upload images, detects objects within them, and provides relevant information links for each detected object.

## Features

- Object detection using Single Shot MultiBox Detector (SSD) model
- Image annotation with bounding boxes
- Information retrieval using Google API
- User-friendly web interface for image upload and result visualization
- RESTful API servers for object detection and information retrieval

## Technologies Used

- Python
- PyTorch
- OpenCV
- Flask
- HTML/CSS/JavaScript
- Google Vision API
- COCO Dataset

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/JnaneshD/PW21SBN05.git
   cd PW21SBN05
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up Google Vision API credentials
   ```
   Set the environment variable GOOGLE_APPLICATION_CREDENTIALS with the key
   ```
   

## Usage

1. Start the Flask servers:
   ```
   python SSD_yolo.py
   ```

2. Open the web interface in your browser (typically at `http://localhost:5000`)

3. Upload an image and wait for the results

## Project Structure

- `object_detection_server.py`: Flask server for object detection
- `info_retrieval_server.py`: Flask server for information retrieval
- `ssd_model.py`: Implementation of the SSD model
- `static/`: Contains CSS and JavaScript files
- `templates/`: Contains HTML templates
- `utils/`: Helper functions and utilities

## Model Performance

The SSD model was trained on the COCO 2014 dataset and achieved an AP50 of 0.65 on the test split.

## Future Work

- Extend the model to detect more object classes
- Implement real-time object detection for video streams
- Improve the accuracy of information retrieval

## Contributors

- [Jnanesh D]
- [Sachin U]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- PES University
- COCO Dataset
- PyTorch community

