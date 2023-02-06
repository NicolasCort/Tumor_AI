# Tumor AI

This is a project that aims to develop an AI-based tool for detecting brain tumors from MRI scans. The model is trained using a dataset of MRI scans with annotated tumors to identify the presence of a brain tumor in new scans.

Here is an example of a brain tumor:
<p align="center">
  <img src="mri brain mask.png" width="800" height="250" align="center"> 
</p>

The first image is the MRI scan, the second the tumor detected with a mask and the third the mask+ MRI scan.


## Libraries

- Python 3.7 or later
- Numpy
- Seaborn
- Matplotlib
- Pandas
- Tensorflow
- Cv2
- Glob
- Random
- Zipfile
- Skimage

## Model
For the model I used a Covolutional Neural Network (CNN). 
Convolutional neural networks are distinguished from other neural networks by their superior performance with image, speech, or audio signal inputs. They have three main types of layers, which are:

- Convolutional layer
- Pooling layer
- Fully-connected (FC) layer

The convolutional layer is the first layer of a convolutional network. While convolutional layers can be followed by additional convolutional layers or pooling layers, the fully-connected layer is the final layer. With each layer, the CNN increases in its complexity, identifying greater portions of the image. Earlier layers focus on simple features, such as colors and edges. As the image data progresses through the layers of the CNN, it starts to recognize larger elements or shapes of the object until it finally identifies the intended object.

You can learn more about it here: https://en.wikipedia.org/wiki/Convolutional_neural_network

## Results

After training the model we got these results:

<p align="center">
  <img src="brain results.png" width="1000" height="250" align="center"> 
</p>


## Installation

Clone the repository to your local machine:

```bash
 git clone https://github.com/NicolasCort/Tumor_AI.git

```
Install the required packages using pip:

```bash
 pip install -r requirements.txt


```

## Contributions
Contributions to this project are welcome! If you want to contribute, please follow these steps:

Fork this repository
Clone the forked repository to your local machine
Make the desired changes and commit them
Push the changes to your forked repository
Submit a pull request to this repository
