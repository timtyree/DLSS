# Deep Learned Super Sampling
Super Sampling Images to ```16``` Times Their Orignal Size using Convolutional Neural Networks <br/>

# Inspiration
This [Computerphile Video](https://www.youtube.com/watch?v=_DPRt3AcUEY) inpsired me to try to code a DLSS program <br/>
The video talks about super sampling from 1080p to 4K <br/>
Due to memory constraints, I can only work with smaller images

# Results
I compared [Nearest Neighbor](https://pillow.readthedocs.io/en/3.1.x/reference/Image.html#PIL.Image.Image.resize) Interpolation to my Deep Learned Super Sampling program <br/>
Here I am upsampling from ```64x64``` to ```256x256``` which is equivalent to increasing the size by ```16``` times

![zoe](https://raw.githubusercontent.com/vee-upatising/DLSS/master/Results/zoe.gif)
![zoe](https://raw.githubusercontent.com/vee-upatising/DLSS/master/Results/zoe2.gif)

# Model Architecture
![model](https://raw.githubusercontent.com/vee-upatising/DLSS/master/Results/model.png)

# [Kaggle Notebook](https://www.kaggle.com/function9/deep-learned-super-sampling)
