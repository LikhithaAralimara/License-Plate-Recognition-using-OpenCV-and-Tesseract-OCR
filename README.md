# License Plate Recognition using OpenCV and Tesseract OCR

This Python script uses OpenCV, Tesseract OCR, and a Haar Cascade Classifier for License Plate Recognition (LPR) on vehicle images. It detects license plates, extracts alphanumeric characters, and identifies the state based on the initial characters.

## Prerequisites

- Python 3.x
- OpenCV
- NumPy
- Tesseract OCR

Ensure Tesseract OCR is installed and set the path to the executable in the script:

```python
pytesseract.pytesseract.tesseract_cmd = "C:/Program Files (x86)/Tesseract-OCR/tesseract.exe"
```
## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/LikhithaAralimara/License-Plate-Recognition-using-OpenCV-and-Tesseract-OCR.git
   cd License-Plate-Recognition-using-OpenCV-and-Tesseract-OCR
   
## Running the Script

Execute the following command to run the script:

```bash
python license_plate_recognition.py
```

## Results and Mapping

After running the script, the following outcomes are observed:

### Result

The recognized license plate text and bounding boxes are overlaid on the input image, and the final result is saved as "Result.png."

### States Mapping

The script provides a mapping of recognized state codes to their corresponding full names.

```python
states = {
    "AN": "Andaman and Nicobar",
    "AP": "Andhra Pradesh",
    # ... (other state codes and names)
}
```
Feel free to customize and seamlessly integrate the script into your projects for license plate recognition!

Note: Adjust the input image path in the script according to your requirements.
