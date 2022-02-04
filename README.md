# GAN Skin-Cancer


In this repository you will find the Colab Notebook for generating synthetic images for skin cancer lesions.
The network is only a PoC (Proof of Concept) to test the feasibility of the task.

1. Architectural framework

<img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/GAN_architecture.png">

The network used is a custom Generative Adversarial Network (GAN), consisting of a generator (G) and a binary classification network called discriminator (D).

The generator receives in input a  random normal noise vector <i>(latent space)</i> with shape [100] and performs an upsampling to produce an output synthetic image of size [64,64,3].

4 convolutional blocks, each with 128 filters, kernel size 3x3 e stride 1x1.
The output has a size of [64,64,3]


in input a vector (latent space) of random normal N(0,1) noise with shape [100] and give in output an image of dimension [64,64,3].



The dataset used is <a href="https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000"> here </a>

<h4> Example Generated Images </h4>

<table>
  <tr>
    <th><img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/gen_1.png"></th>
    <th><img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/gen_2.png"></th>
    <th><img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/gen_3.png"></th>
    <th><img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/gen_4.png"></th>
    <th><img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/gen_5.png"></th>
    <th><img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/gen_6.png"></th>
    <th><img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/gen_7.png"></th>
    <th><img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/gen_8.png"></th>
  </tr>
</table>
