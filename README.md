# Training BatchNorm and Only BatchNorm: Affine parameter effecst in MLP's
<div id="top"></div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Part of a project in Deep Learning Applied AI at the University of Sapienza spring of 2022. The starting point was the paper by "Training BatchNorm and only BatchNorm" where they investigated the effects of training only batch normalization
layers on residual neural nets.

<!-- GETTING STARTED -->
## Getting Started
The notebook are standard tensorflow/keras notebooks. For understanding more about what they are about I recommend reading the paper on training BatchNorm and only BatchNorm (link in acknowledgments).

<p align="right">(<a href="#top">back to top</a>)</p>


### Prerequisites

The notebooks run with jupyter and tensorflow/keras. They also work fine in google colab.

* Jupyter notebook
* Tensorflow
  ```sh
  pip install tensorflow
  ```
* Keras-tuner if you want to do tuning. If this becomes an issue feel free to comment it out.
  ```sh
  pip install keras-tuner --upgrade
  ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

There are two notebooks, one for each architecture (LeNet CNN and MLP's). Each notebook has a tuning section at the bottom where the tuning is commented out. For this project the MLP notebook is the interesting one.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap
Self-evalution on further work that can be done on this project.
- [ ] Optimize the random parameter freezing/unfreezing. Only in Keras for R is it possible to freeze certain weights, this could come soon and easily speed up runtime for the larger nets.
- [ ] More rigorous MLP architecture design. As it is the dimensions and contents are somewhat simple and arbitrarily picked based on getting initial results.
- [ ] Testing and tuning more hyperparameters. Also activation function positioning (before or after) and batch sizing.
- [ ] Further experimenting with other datasets. Also extending it to non-computer vision sets.
- [ ] Experiment with other architectures.

See the [open issues](https://github.com/marcusntnu/mlp_lenet_bathnorm/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Your Name - henriksboe@gmail.com

Project Link: [https://github.com/marcusntnu/mlp_lenet_bathnorm](https://github.com/marcusntnu/mlp_lenet_bathnorm)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Research paper on Training BatchNorm and Only BatchNorm](https://arxiv.org/abs/2003.00152)
* [Simple MNIST Keras example](https://keras.io/examples/vision/mnist_convnet/)
* [Sayak Paul's experiments on training only batch norm](https://wandb.ai/sayakpaul/training-bn-only/reports/How-powerful-the-randrom-features-of-a-CNN-can-be%3F--VmlldzoxMTIxODA)

<p align="right">(<a href="#top">back to top</a>)</p>
