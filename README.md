# Iris Recognition System

This project implements an iris recognition system comprising modules for:
- Image enhancement
- Iris localization
- Normalization
- Feature extraction
- Matching
- Performance evaluation

---

## Project Structure

- `Images/` — Contains the input iris images.
- `ImageEnhancement.py` — Performs image enhancement operations.
- `IrisLocalization.py` — Detects and localizes the iris and pupil boundaries.
- `IrisNormalization.py` — Normalizes the localized iris region for uniformity.
- `FeatureExtraction.py` — Extracts key features from the normalized iris.
- `IrisMatching.py` — Matches extracted iris features between samples.
- `PerformanceEvaluation.py` — Evaluates the system's recognition performance.
- `IrisRecognition.py` — Main script that runs the complete recognition pipeline.

---

## Prerequisites

- Ensure you have **Python 3.7** or higher installed.
- Install the required libraries by running:

```bash
pip install opencv-python numpy matplotlib scikit-learn scipy
```

## How to Run

1. Unzip the project files to your desired directory.
2. Place your input images inside the `Images/` folder.
3. Open a terminal or command prompt in the project directory.
4. Run the following command:

```bash
python IrisRecognition.py
```

## Additional Information

- Each module (`ImageEnhancement.py`, `IrisLocalization.py`, etc.) can also be run individually for testing and analysis.
- Ensure that the input images are compatible with the expected format (e.g., `.bmp`, `.jpg`).

## Images

This file contains 8 images depicting the step-by-step output we obtained for localization, normalization, and enhancement.

- **Fig1**: Depicts the grayscale image of the eye.
- **Fig2**: Depicts the colored image, which is what gets stored in the target array in the Localization function.
- **Fig3**: Depicts the output of Localization, i.e., the original image with inner and outer boundaries.
- **Fig4**: Depicts the enhanced normalized 64x512 rectangular image, which is used for further feature extraction steps.


