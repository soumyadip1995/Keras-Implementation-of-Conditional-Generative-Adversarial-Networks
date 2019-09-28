## Keras-Implementation-of-Conditional-Generative-Adversarial-Networks

Conditional GANs (CGANs): The Generator and Discriminator both receive some additional conditioning input information. This could be the class of the current image or some other property.

### Credits
The credits for this repository goes to [this](https://github.com/eriklindernoren/Keras-GAN) repo. They have done a wonderful job in implementing cgans as well as image to image translation. Credits go to Jason Brownlee from Machine Learning Mastery.

### Running the code
Code is [here](https://github.com/soumyadip1995/Keras-Implementation-of-Conditional-Generative-Adversarial-Networks/blob/master/pix2pix/pix2pix.py)
To run the pix2pix image translation

```
!git clone https://github.com/soumyadip1995/Keras-Implementation-of-Conditional-Generative-Adversarial-Networks.git
% cd pix2pix/
! bash download_dataset.sh facades
! python3 pix2pix.py
```   
To run the Conditional GAN on the Fashion-MNIST dataset. 

```
!git clone https://github.com/soumyadip1995/Keras-Implementation-of-Conditional-Generative-Adversarial-Networks.git
%cd Keras-Implementation-of-Conditional-Generative-Adversarial-Networks/cgan_fashion_mnist/
!python conditional_gan_implementation.py
``` 
Running the example may take some time,I have run only for 25 epochs. You may choose to do more and GPU hardware is recommended, but not required.
At the end of the run, the model is saved to the file with name ‘cgan_generator.h5‘. Then execute.

```
!python generating_images.py
``` 
My result from the generating_images.py code:-

![alt_text](https://github.com/soumyadip1995/Keras-Implementation-of-Conditional-Generative-Adversarial-Networks/blob/master/results/download%20(1).png)

To run the Conditional GAN on the MNIST digit dataset.

```
!git clone https://github.com/soumyadip1995/Keras-Implementation-of-Conditional-Generative-Adversarial-Networks.git
%cd Keras-Implementation-of-Conditional-Generative-Adversarial-Networks/keras_cgan/
!python cgan_keras.py
``` 
To create the video from the images execute
```
!python video_cgan.py
``` 
My result after creating a video from the resultant output of the cgan_keras.py code:-

![alt_text](https://github.com/soumyadip1995/Keras-Implementation-of-Conditional-Generative-Adversarial-Networks/blob/master/results/video.gif)


