# GAN Skin-Cancer


In this repository you will find the Colab Notebook for generating synthetic images for skin cancer lesions.
The implemented network is only a PoC (Proof of Concept) to test the feasibility of the task.

<div>
  <h3>1. Architectural framework</h3>

  <div align="center">
    <img src="https://github.com/GiuseppeCannata/GAN-skin-cancer/blob/master/imgs/GAN_architecture.jpg" height="397" weight="735">
    <br>
    <figcaption ><em>Fig.1: GAN framework implemented</em></figcaption>
  </div>
  <br>
  The Generative Adversarial Network (GAN) implemented is shown in detail in Fig.1. In particular, with G has been indicated the generator network, while with D the 
  discriminator network. The generator receives in input a random normal noise vector <i>(latent space)</i> with shape [100] and performs an upsampling to produce an output 
  synthetic RGB image of size [64,64,3]. 

  The dataset used is <a href="https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000"> here </a>

  <h3>2. Results </h3>
  Some qualitative results are shown below:
  <br><br>
  
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
</div>
