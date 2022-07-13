# mlp_lenet_bathnorm

<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/marcusntnu/mlp_lenet_bathnorm">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Training BatchNorm and Only BatchNorm: Affine parameter learning for MLP's</h3>

  <p align="center">
    A CNN with weights frozen at their random original value and trained only on the beta and gamma parameters of the batch-normalization can achieve surprisingly good results on image classification problems, much better than training an equivalent number of weights chosen at random. This project investigates this idea further.
    <br />
    <a href="https://github.com/marcusntnu/mlp_lenet_bathnorm"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/marcusntnu/mlp_lenet_bathnorm">View Demo</a>
    ·
    <a href="https://github.com/marcusntnu/mlp_lenet_bathnorm/issues">Report Bug</a>
    ·
    <a href="https://github.com/marcusntnu/mlp_lenet_bathnorm/issues">Request Feature</a>
  </p>
</div>



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

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Heres some text for the project.


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/marcusntnu/mlp_lenet_bathnorm.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

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

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>
