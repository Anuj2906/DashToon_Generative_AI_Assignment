# DashToon_Generative_AI_Assignment
## Artistic Style Transfer

This repository contains a TensorFlow implementation of neural style transfer. The code is designed to take a content image and a style image and generate a stylized version of the content image, incorporating the artistic style of the style image.

## Getting Started

### Prerequisites

- TensorFlow
- Matplotlib
- NumPy
- ImageIO

Install the required dependencies using:
```bash
pip install tensorflow matplotlib numpy imageio
```
## Usage:
### Clone the repository:
```
git clone https://github.com/your-username/style-transfer.git
cd style-transfer
```
Open and run the style_transfer.ipynb Jupyter notebook.

Customize the paths to your content and style images in the notebook:

```
content_path = Path('/path/to/content/image.jpg')
style_path = Path('/path/to/style/image.jpg')
```
Run the notebook cells to perform style transfer and visualize the results.
## Parameters:
Adjust the following parameters in the notebook to control the style transfer process:

style_weight: Weight given to the style loss.

content_weight: Weight given to the content loss.

optimizer: Optimizer for updating the input image.

epochs: Number of training epochs.

steps_per_epoch: Steps per epoch.


Experiment with these parameters to achieve the desired stylized output.

## Results:
The notebook generates stylized images during the training process, allowing you to visualize how the stylized image evolves over epochs. The final stylized image is saved as stylized_image.jpg.
