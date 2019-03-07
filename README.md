# DCGAN

Generating facial images of imaginary celebrities and facial sketches of imaginary people using Deep Convolutional GAN (DCGAN). Used the CelebA and CUFS datasets to train the respective models. 

Utilized PyTorch framework for development. Used a NVIDIA GeForce GTX 1070 GPU machine to facilitate training of the model. 


Please note:
 * Before running the Notebook, download the CelebA dataset images (http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) and the CUFS dataset images (http://mmlab.ie.cuhk.edu.hk/archive/facesketch.html) and put them into the 'imgs' subdirectory of the 'celeba' and 'cufs' directories respectively. 

<p align="center">
  <br><br>
  <b>CelebA Results</b>
  <br><br>
  Epochs 1 --> 5
  <br>
  <img src="https://github.com/ApurbaSengupta/DCGAN/blob/master/results/fake_samples_epoch_001.png" height="200" width="200">
  <img src="https://github.com/ApurbaSengupta/DCGAN/blob/master/results/fake_samples_epoch_002.png" height="200" width="200">
  <img src="https://github.com/ApurbaSengupta/DCGAN/blob/master/results/fake_samples_epoch_003.png" height="200" width="200">
  <img src="https://github.com/ApurbaSengupta/DCGAN/blob/master/results/fake_samples_epoch_004.png" height="200" width="200">
  <br><br>
  <img src="https://github.com/ApurbaSengupta/DCGAN/blob/master/results/fake_celeba.png">
  <img src="https://github.com/ApurbaSengupta/DCGAN/blob/master/results/plot_celeba.png">
  <br><br><br>
  <b>CUFS Results</b>
  <img src="https://github.com/ApurbaSengupta/DCGAN/blob/master/results/fake_cufs.png">
  <img src="https://github.com/ApurbaSengupta/DCGAN/blob/master/results/plot_cufs.png">
</p>
