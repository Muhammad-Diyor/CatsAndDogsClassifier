# Cats and Dogs Classifier UI

This repository contains a simple UI for classifying images into cats and dogs using a pre-trained model.

Model has been trained using Tensoflow, Keras and Pandas on Google Colab.

Training code here: [Link](https://colab.research.google.com/drive/1F4157biWuerZ5oC8BRr2LCtB_D5m4MM0?usp=sharing)

## Instructions for Running the UI

### Prerequisites
- Make sure you have [Python](https://www.python.org/) installed on your system.

### Clone the Repository
Clone this repository to your local machine:

```bash
git clone https://github.com/Muhammad-Diyor/CatsAndDogsClassifier
cd CatsAndDogsClassifier
```

### Install Dependencies
Install the required Python packages. Run the following commands one by one
```bash
pip install numpy
pip install matplotlib
pip install Pillow
pip install tensorflow
pip install keras
```

### Download the pre-trained model

Download the model from Google Drive: [Link](https://drive.google.com/file/d/1IDZqbIisRJ9EuM2oI7m-Zfv7sUgygYQV/view?usp=sharing)
And put it in the same directory with `gui.py` file.
### Run the UI
Execute the following command to run the UI:

```bash
python gui.py
```