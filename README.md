Here’s a clean and concise `README.md` for your **Driver Drowsiness Detection System** project:

````markdown
# Driver Drowsiness Detection System

A real-time Python project that detects driver drowsiness using webcam feed. The system monitors eye state (open/closed) using a CNN model and triggers alerts to prevent accidents caused by fatigue.

## Features

- Real-time eye state detection using OpenCV
- CNN-based classification with Keras
- Visual/audio alert on drowsiness
- Pre-trained model included

## Technologies Used

- Python
- OpenCV
- Keras & TensorFlow
- NumPy
- Matplotlib

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/driver-drowsiness-detection.git
   cd driver-drowsiness-detection
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the detection script:

```bash
python detect_drowsiness.py
```

The system will start the webcam and monitor the driver's eye state. Alerts will trigger if drowsiness is detected.

## Dataset

Includes labeled images of eyes (open/closed) used to train the CNN model. You can retrain or fine-tune the model as needed.

## Pre-trained Model

The pre-trained weights (`cnnCat2.h5`) are included for immediate use.

## Contributing

Contributions are welcome! Open issues or submit pull requests for improvements.


