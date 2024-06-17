# StyleFusionGAN

**Development of an Adaptable Deep Learning Model for Artistic Style Transfer:**

<U>Implement VGG19 based CNN to design Artistic-Style-Transfer Neural Net using the concept of Generative Adversial Neural Network.</U>


## Description
- Artistic Style Transfer involves using two distinct images: a "content image" and a "style image".
- A neural network learns to merge the stylistic elements of the style image with the content of the content image.
- This process results in the creation of visually appealing and unique compositions.
- Applications include generating captivating artwork, transforming photographs, and exploring the intersection of artificial intelligence and artistic expression.


## Installation

Provide instructions on how to install and set up your project. Include any dependencies or requirements that users need to install.

```bash
# Clone the repository
git clone https://github.com/tanush-k/StyleFusionGAN

# Navigate to the project directory
cd StyleFusionGAN

# Additional installation steps...
pip install -r requirements.txt
```

## Key Features

- **Style Transfer:** Use pre-trained models to transfer the artistic style of one image onto another.
- **Customization:** Explore different combinations of content and style images to create diverse artistic outputs.
- **Deep Learning:** Leverage state-of-the-art GAN architectures for realistic and expressive image transformations.

## Base Model:

![VGG19](https://www.mdpi.com/agriengineering/agriengineering-04-00056/article_deploy/html/images/agriengineering-04-00056-g002.png)

**Summary:**

VGG19 is a convolutional neural network architecture that has proven to be effective in various computer vision tasks, including image classification and feature extraction. In the context of the Artistic Style Transfer GAN project, we use a pre-trained VGG19 model as the base architecture for extracting features from content and style images.

**Key Features of VGG19:**

- Deep architecture with 19 layers, including convolutional and fully connected layers.
- Known for its simplicity and effectiveness in capturing hierarchical features.
- Pre-trained on large image datasets, making it suitable for transfer learning tasks.
- Utilized in the project to extract high-level features for content and style representations.

