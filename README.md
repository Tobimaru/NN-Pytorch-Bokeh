# Evolution of Wasserstein GAN (WGAN) illustrated by a simple 1D problem
This is a python notebook that implements a one-dimensional GAN example to illustrate the evolution of WGAN training methods. It's a relatively simple problem in which the generator tries to mimic a Gaussian distribution. The notebook allows to compare between different models that have been proposed on the internet for this example based on the following sources:

* http://blog.aylien.com/introduction-generative-adversarial-networks-code-tensorflow/

* https://medium.com/@devnag/generative-adversarial-networks-gans-in-50-lines-of-code-pytorch-e81b79659e3f
 
* https://github.com/kremerj/gan

Relevant publications:

* GAN: https://arxiv.org/abs/1406.2661
* Wasserstein GAN: https://arxiv.org/abs/1701.07875
* Wasserstein GAN with improved training: https://arxiv.org/abs/1704.00028

### Requirements
In order to run the notebooks you need to have Jupyter Notebook installed, as well as the following packages (versions as tested on):

* numpy: 1.13.3
* PyTorch: 0.3.0
* Bokeh: 0.12.10 
