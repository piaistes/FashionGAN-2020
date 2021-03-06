# FashionGAN-This fashion item does not exist (yet)!
This is an invitation to anyone who would like to play with state-of-the-art-AI tools 
to take advantage of this repository, creating never-seen-before fashion items!

No need for extra  GPU's! All training process is done in Google-Colab Free Version!

![alt text](https://github.com/piaistes/FashionGAN-2020/blob/main/GithubTitle.JPG)

## Requirements
- Google-Drive Account with at least 50GB of memory (for training with 128x128 images)
- Dataset with square-images (ideally 128x128 for Google-Colab ressources, I recommend to have at least 10k to ensure a certain variation within the dataset)

## Manipulation
Here you go with some examples of how you can play with FashionGAN (apart from generating new designs):

### Truncation-Trick
![alt text](https://github.com/piaistes/FashionGAN-2020/blob/main/TruncationV1.JPG)

### Interpolation/Morphing
![alt text](https://github.com/piaistes/FashionGAN-2020/blob/main/Interpolation.JPG)

### Style-Mixing
![alt text](https://github.com/piaistes/FashionGAN-2020/blob/main/StyleMixing.JPG)

### Projection 
Some examples of projecting images that WERE NOT part of the original training dataset:
![alt text](https://github.com/piaistes/FashionGAN-2020/blob/main/Projection1.0.JPG)
Some examples of projecting images that WERE part of the original training dataset:
![alt text](https://github.com/piaistes/FashionGAN-2020/blob/main/Projection2.0.JPG)

## References
Dear Reader, please have in mind, that for this experiment only free ressources (1 GPU) was used. For higher resolutions and better quality results in all applied techniques, up to 8 GPU's are necessary. Also, variation of the original dataset plays a crucial role. Nonetheless, new ways of designing and manipulating clothing have worked well, and might change common sales rules and processes in future. If you want to learn more about StyleGAN and it's manipulation techniques that were used here, I recommend heading to the following papers:
- https://arxiv.org/abs/1812.04948
- https://arxiv.org/abs/1912.04958
