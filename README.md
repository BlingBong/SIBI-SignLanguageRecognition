# SIBI Sign Language Recognition

---
## Introduction

- This is a real-time SIBI (Sistem Isyarat Bahasa Indonesia) Sign Language Recognition that was made for my personal bachelor thesis.
- Made with Jupyter Notebook and OpenCV.
- Uses six different dynamic SIBI gestures as action classes/labels, namely "apa/what", "bagaimana/how", "berapa/how many", "di mana/where", "mengapa/why", and "siapa/who".
- MediaPipe is utilized to collect datasets by extracting the values of hand keypoints and then storing them in NumPy array format.
- A total of 180 original data (30 data for each class) were augmented with four variants into 3060 data (510 data for each class).
- The model was built using three LSTM layers and three Dense layers with a data split of 2616 for training, 153 for testing, and 291 for validation. This combination produces a categorical accuracy value of 99.85%, a loss of 0.0059, and an overall performance matrix value of 100% after training with 150 epochs.

---
## Instructions

1. Clone the repository by running the following command in your terminal or Git Bash:
  ```bash
  git clone https://github.com/BlingBong/SIBI-SignLanguageRecognition.git
  ```
2. Make sure you have Jupyter Notebook installed on your computer, if not, follow these instructions [Jupyter Install](https://jupyter.org/install).
3. Open your terminal in the downloaded folder.
4. Run this command "python -m notebook" (may differ on each Operating System and Jupyter version).
5. Wait for the command to run successfully, you will be redirected to the Jupyter Notebook tab in your browser.
6. Open SIBI SLR.ipnyb in the Jupyter Notebook tab. You can now run the code!

If you encounter any errors or issues, you can refer to the "Issues" section of the repository or contact the repository's maintainer for help.

---
## Technologies

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

---
## Screenshots

| Description | Screenshot |
| ----------- | ----------- |
| Data Collection | ![Data Collection](https://github.com/BlingBong/SIBI-SignLanguageRecognition/assets/62862052/f4ada757-03c5-41c3-94ba-b1921d6f7406) |
| Real-Time Testing | ![image](https://github.com/BlingBong/SIBI-SignLanguageRecognition/assets/62862052/7ada79e7-bae2-4d31-8699-560ccee50c21) |
| Model Loss Graph | ![image](https://github.com/BlingBong/SIBI-SignLanguageRecognition/assets/62862052/fac09f4e-adf9-482d-b9a1-c66d5e821bb6) |
| Model Accuracy Graph | ![image](https://github.com/BlingBong/SIBI-SignLanguageRecognition/assets/62862052/58a7349c-2be3-47e1-87c4-0f72c487c1f3) |


