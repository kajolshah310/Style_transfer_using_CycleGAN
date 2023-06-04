# Style_transfer_using_CycleGAN - Computer Vision
Multi-collection Style Transfer Using CycleGAN

## Description
In this project, I have implemented multi-collection style transfer using CycleGAN in computer vision. Style transfer involves generating a new image that combines the content from one image and the artistic style from another image or a collection of images. CycleGAN is a deep learning approach that utilizes generative and discriminative networks to achieve style transfer without paired training samples.

![alt text](https://github.com/kajolshah310/Style_transfer_using_CycleGAN/blob/main/epoch8%20outputs.PNG)

Style transfer is the process of redrawing or generating a new image that combines the content or scene from one image and the artistic style from a different image or a collection of images. Initially, the problem first stemmed from wanting to make an input image look as if it was drawn with the same style as in a painting from a famous artist. Manually transferring the image to a different style by interpreting another artist’s style/technique is something that would take a professional artist considerable time and effort, if they are even able to achieve adequate results.
To automate the process, AI and computer vision techniques have been used to obtain promising results. As there are many practical applications for style transfer, such as quickly creating animations from real life scenes, there has been a lot of research and development into creatingmore accurate models that produce clear images and are pleasing to the eye. Unfortunately, many implementations of GANs that are able to obtain collective style transfer are only capable of generating images of one style. Therefore, multiple networks and models must be trained in order to achieve multiple models.


The notebook showcases the process of training and using a CycleGAN model for style transfer. It explains the concepts behind CycleGAN, its training procedure, and how it addresses the unpaired image-to-image translation problem. The notebook also provides code examples and visualizations to help you understand and experiment with style transfer using CycleGAN.


## Features
- Overview of the style transfer process and CycleGAN architecture
- Step-by-step guide for training a CycleGAN model
- Code examples for applying style transfer to images
- Visualizations of style transfer results
- Insights into the challenges and considerations in style transfer using CycleGAN

## Requirements
To run the notebook and perform style transfer using CycleGAN, you need the following dependencies:
- Python 3.x
- Jupyter Notebook
- Keras
- TensorFlow
- NumPy
- Matplotlib

You can install the required packages using the following command:
```shell
pip install torch torchvision numpy matplotlib
```
## Usage
1) Clone the repository to your local machine using the following command:
```
git clone https://github.com/kajolshah310/Style_transfer_using_CycleGAN.git
```
2) Navigate to the repository's directory:
```
cd Style_transfer_using_CycleGAN/style_transfer
```
3) Launch Jupyter Notebook:
```
jupyter notebook
```

4) Open the Multi_style_transfer_with_Cycle_GAN.ipynb notebook and execute the cells to follow along with the training process and apply style transfer to your own images.
Feel free to modify the code and experiment with different images and styles to create unique and visually appealing outputs.

## References

[1] X. Chen, C. Xu, et al. "Gated-GAN: Adversarial Gated Networks for Multi-Collection Style Transfer" Published in IEEE Transactions on Image Processing, 2019.
[1] Zhu, Jun-Yan, et al. "Unpaired image-to-image translation using cycle-consistent adversarial networks." Proceedings of the IEEE International Conference on Computer Vision, 2017.

## License
This repository is licensed under the MIT License. Feel free to use the code and notebook for your own projects or research.

