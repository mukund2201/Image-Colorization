The codes and data from my GAN based image colorization experiment will be available in this repository.The notebook's goal is to familiarise me with the process of developing and testing a GAN model.



The Dataset used for in the notebook is COCO Dataset. GAN. 
![image](https://user-images.githubusercontent.com/81349041/176591733-5d31e583-f0a5-415e-9e2c-88fbe87bbce0.png)

A GAN is composed of two smaller networks called the generator and discriminator. As the name suggests, the generator’s task is to produce results that are indistinguishable from real data. The discriminator’s task is to classify whether a sample originated from the generator’s model distribution or the original data distribution. Both of these subnetworks are trained simultaneously until the generator is able to consistently produce results that the discriminator cannot classify.
The structure of the model consists of a U-net Generator and a Patch Discriminator as the main networks for this. 
The architectures of the generator and discriminator both follow a multilayer perceptron model. Since colorization is a class of image translation problems, the generator and discriminator are both convolutional neural networks (CNN).

GAN Network Architechture
![image](https://user-images.githubusercontent.com/81349041/176592086-b68c6c0e-05bb-4693-9f48-3158437bd0ed.png)


To end, this is just a practice for Deep Learning model deployment for me to better understand the whole flow and will be a stepping stone for more complicated projects in the future.

Some references and parts of code taken from here: 
https://web.eecs.umich.edu/~justincj/teaching/eecs442/projects/WI2021/pdfs/068.pdf
https://towardsdatascience.com/colorizing-black-white-images-with-u-net-and-conditional-gan-a-tutorial-81b2df111cd8

