# DualAST: Dual Style-Learning Networks for Artistic Style Transfer
This is the official Tensorflow implementation of our paper: "DualAST: Dual Style-Learning Networks for Artistic Style Transfer"  
  
This project provides a novel style transfer framework, termed as DualAST, to address the artistic style transfer problem from a new perspective. Unlike existing style transfer methods, which learn styles from either a single style example or a collection of artworks, DualAST learns simultaneously both the holistic artist-style (from a collection of artworks) and the specific artwork-style (from a single style image): the first style sets the tone (*i.e.*, the overall feeling) for the stylized image, while the second style determines the details of the stylized image, such as color and texture. Moreover, we introduce a Style-Control Block (SCB) to adjust the styles of generated images with a set of learnable style-control factors.  
  
![image](https://github.com/HalbertCH/DualAST/blob/main/results/1.png)  
  
## Requirements  
We recommend the following configurations:  
- python 3.7
- tensorflow 1.14.0
- CUDA 10.1
- PIL, numpy, scipy
- tqdm
  
## Download  
- Content images used for training: [Places365(105GB)](http://data.csail.mit.edu/places/places365/train_large_places365standard.tar).
- Style images used for training: [Artworks of different artists](https://drive.google.com/drive/folders/1WxWxIhqqtkx4CwBVem7ZSr_ay9JJCiOh?usp=sharing). Thanks for the dataset provided by AST.
- Pre-trained [VGG-19](https://drive.google.com/drive/folders/1n7VazSzdVdAN8Bp392KYQGVshg9pTdQ4?usp=sharing) model.
