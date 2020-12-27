#### Image-Style-Transfer-App  

## Header Info 
Title: Neural Style Transfer: An End-to-End Computation  

Group:  

Shuyi Huo (sh3989)  
Siqi Chen (sc4647)   
Weihan Chu (wc2688)  

Special thanks to volunteer contributors: Linjun Huang 


## Introduction 
Our team is trying to implement a high-performance Image Style Transfer algorithm from scratch and apply it to establish a photo style transfer web frontend. For computing a high-performance algorithm, our team utilized a famous image processing pre-trained CNN named VGG-19 and compiled other models for comparison; For output validation, we use different content pictures (portrait, scene etc.) and different style pictures (famous paints from variate artistic genres) to compute our target images; For evaluating model performance, our team combined content loss with style loss and total variation loss for tuning the ideal target images. Since there is no absolutely quantified result on the performance of style transformation, our team made a brief inference and conclusion.  


## Introduction: Data 
Since our team is using a pre-trained VGG-19 model so we don’t have training validation samples regarding this project.
Our team selected 2 images each for content style as input and trying to make them heterogeneous to validate the performance of our model.
The output will be our style-transferred image. Input and output Size as tensor: [1,512,512,3]  

For example:  

![New York City](https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/image/NYC.jpg){:height="50%" width="50%"}  

![Star](https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/image/star.jpg){:height="50%" width="50%"}   

<p align="center">
  <img src="https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/image/NYC.jpg" width="256" height="455">
  <img src="https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/image/star.jpg" width="256" height="455">
</p>

The output is:  


![nyc_star_transfer](https://github.com/ShuyiHuo/Image-Style-Transfer-App/blob/main/image/nyc_star_transfer.jpg){:height="50%" width="50%"} 

