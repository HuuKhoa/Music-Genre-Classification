Music Genre Classifier Project
Authors: Logan Wolff, Anthony Barbaro, Bryle Ong, Khoa Hoang, Huu-Khoa Nguyen

### Overview
This project develops a neural network-based system to classify music genres from audio spectrograms. Using deep learning, the system learns to recognize distinct features in spectrogram images corresponding to various music genres such as pop, metal, classical, and more. Not only that to genre, but also as a sound source to convert into classification section if possible due to noise and various effects.

### Background
The motivation behind this project is to explore the applications of convolutional neural networks (CNNs) in audio analysis, specifically for the task of music genre classification. The project uses spectrograms of music tracks as the input data, transforming the audio problem into a visual one, which is a typical approach for applying CNNs effectively.

### Installation
Prerequisites
Ensure you have Python 3.7 or later installed on your system. Python can be downloaded from the official website.

### Dependencies
The project depends on several Python libraries, which can be installed using pip. Here is a step-by-step guide:

### Clone the repository:
git clone <https://github.com/HuuKhoa/Music-Genre-Classification/>
cd <https://github.com/HuuKhoa/Music-Genre-Classification/>

### Create a virtual environment (recommended):
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

### Install required libraries:
pip install numpy matplotlib keras tensorflow jupyter deeplake librosa av

### Running Jupyter Notebook
After installing the dependencies, run Jupyter Notebook:
jupyter notebook
This command will start the Jupyter Notebook server and open a browser window where you can navigate and open the project notebooks.

### Usage
Data Preparation
Prepare your dataset: Ensure your spectrogram images are formatted and labeled correctly as per the guidelines provided in data_prep.ipynb.
Run the data_prep.ipynb: This notebook will guide you through loading, processing, and splitting the data for training and testing.
Model Training and Evaluation
Open musicgenreclassifierV2.ipynb: Follow the steps outlined to train the model using the preprocessed data.
Evaluate the model: The notebook includes steps to evaluate the model's performance on a test set and visualize the results.
Data
The project assumes a dataset of audio spectrograms categorized by music genres. For best results, ensure the spectrograms are uniformly sized and properly labeled. The format and preparation of the dataset are critical for successful training and classification.

### Contributing
Contributors are welcome to propose improvements to the codebase, add new features, or enhance the documentation. To contribute:
- Fork the repository.
- Create a new branch for your feature (git checkout -b feature/AmazingFeature).
- Commit your changes (git commit -m 'Add some AmazingFeature').
- Push to the branch (git push origin feature/AmazingFeature).
- Open a pull request.

### License
This project is licensed under the MIT License - see the  LICENSE.md file for details.
