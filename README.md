# Training BatchNorm and Only BatchNorm: Affine parameter learning for MLP's
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

Heres some text for the project.


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


<p align="right">(<a href="#top">back to top</a>)</p>


### Prerequisites

The notebooks run with jupyter and tensorflow/keras. They also work in colab.

* Jupyter notebook
* Tensorflow
  ```sh
  pip install tensorflow
  ```
* Keras-tuner
  ```sh
  pip install keras-tuner --upgrade
  ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

There are three notebooks, one for each architecture (LeNet CNN and MLP's) and one merged. Each notebook has a tuning section at the bottom where the tuning is commented out.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap
Self-evalution on further work that can be done on this project.
- [ ] More rigorous MLP architecture design
- [ ] Testing and tuning more hyperparameters. Also activation function positioning and batch size.
- [ ] Further experimenting with other datasets.

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
