# Image Style Transfer Project 
  
## Introduction 
Our team is trying to implement a high-performance Image Style Transfer algorithm from scratch and apply it to establish a photo style transfer web frontend. For computing a high-performance algorithm, our team utilized a famous image processing pre-trained CNN named VGG-19 and compiled other models for comparison; For output validation, we use different content pictures (portrait, scene etc.) and different style pictures (famous paints from variate artistic genres) to compute our target images; For evaluating model performance, our team combined content loss with style loss and total variation loss for tuning the ideal target images. Since there is no absolutely quantified result on the performance of style transformation, our team made a brief inference and conclusion.  


## Procedure 
Since our team is using a pre-trained VGG-19 model so we don’t have training validation samples regarding this project.
Our team selected 2 images each for content style as input and trying to make them heterogeneous to validate the performance of our model.
The output will be our style-transferred image. Input and output Size as tensor: [1,512,512,3]  

For example:  

<p align="center">
  <img src="https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/image/NYC.jpg" width="500px" height="500px">
  <img src="https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/image/star.jpg" width="500px" height="500px">
</p>
  
## Result
The output is:  

<p align="center">
  <img src="https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/image/nyc_star_transfer.jpg" width="500px" height="500px">
</p>

The more information and details will be shown on our [report](https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/5242_Final_Report.pdf) and 
the code will be shown on [code](https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/project_demo.ipynb).

## Reference   

[1]Gatys, Leon A., Alexander S. Ecker, and Matthias Bethge. “Image Style Transfer Using Convolutional Neural Networks.” 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016.  

[2]Keras-Team, ed. “Keras-Team/Keras.” GitHub, n.d. https://github.com/keras-team/keras/tree/fcf2ed7831185a282895dda193217c2a97e1e41d.

[3]“Neural Style Transfer: TensorFlow Core.” TensorFlow, n.d. https://www.tensorflow.org/tutorials/generative/style_transfer.

---

**Group Members:**  

Shuyi Huo (sh3989)  
Siqi Chen (sc4647)   
[Weihan Chu](https://github.com/WeihanChu-wc2688) (wc2688)  

Special thanks to volunteer contributor: Linjun Huang 
