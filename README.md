SimpleGAN-for-MNIST
===
###### 'GAN'
This's a project to construct a simple GAN structure to generate hand written number.

Introduction
---

This is my first implementation of Generative Adversarial Network. Using the simple network structures (DNN) and some activations (LeakyReLU, Dropout) to construct models training on MNIST. Althought the model structure is simple, the loss seems convergent fast and the performance is pretty good. 


Training
---

Step 1. Fix Generator generate random handwritting numbers , Training Discriminator.  
Step 2. Fix Discriminator , training Generator to generate better handwritting numbers .  
  

This is one epoch, and continue this process again and again......( default training 50000 epochs )


Performance
---

Random handwritting numbers training from 0 to 50000 epochs.
![](https://github.com/allen108108/SimpleGAN-for-MNIST/blob/master/data/sample_0.jpg)

Handwritting number eight training from 0 to 100000 epochs.
![](https://github.com/allen108108/SimpleGAN-for-MNIST/blob/master/data/sample_1.jpg)



Reference
---
  
1. [李宏毅 Machine Learning and having it Deep and Structured 課程筆記](https://allen108108.github.io/blog/categories/%E8%AA%B2%E7%A8%8B%E7%AD%86%E8%A8%98-Course/%E6%9D%8E%E5%AE%8F%E6%AF%85-Machine-Learning-and-having-it-Deep-and-Structured/page/2/)  
2. [實戰GAN：TensorFlow與Keras生成對抗網絡構建](https://www.tenlong.com.tw/products/9787121374098)  