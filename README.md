# AreCare-Arecanut-Identification-System
Arecanut Quality Classifier using Keras and OpenCV

This project focuses on classifying Arecanut (betel nut) based on its quality using machine learning techniques with Keras and image processing with OpenCV.

## Project Overview

The classifier uses a pre-trained Keras model (`keras_Model.h5`) to distinguish between good and bad quality Arecanut. It utilizes a webcam to capture images, preprocesses them, and predicts the quality using the trained model.

## Setup Instructions

### Prerequisites

- Ensure Python is installed (`python --version`).
- Install required packages:
  ```bash
  pip install opencv-python tensorflow numpy
  ```

### Running the Classifier

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/DEV-SRB/AreCare---Arecanut-Identification-System.git
   cd your-repo
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirement.txt
   ```

3. **Run the Classifier:**
   ```bash
   python model_test.py
   ```

   Make sure to adjust the camera index (`camera = cv2.VideoCapture(0)`) if using a different webcam.

4. **Interpret Results:**
   - The classifier will display the webcam feed with a window showing the real-time prediction of Arecanut quality.
   - Press `Esc` to exit the program.

## File Descriptions

- `keras_Model.h5`: Pre-trained Keras model for Arecanut quality classification.
- `model_test.py`: Main Python script that loads the model, captures webcam images, and performs predictions.
- `labels.txt`: Text file containing class labels used by the model.

## Contributing

Feel free to contribute to improve this classifier. Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
