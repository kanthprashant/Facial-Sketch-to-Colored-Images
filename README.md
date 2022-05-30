<div id="top"></div>

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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Facial-Sketch-to-Colored-Images-Using-GANs</h3>
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
    <li><a href="#contributions">Contributions</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Project Name Screen Shot][project-screenshot]](/Images/1.jpg)

In this project, we tackle the problem of generating color photorealistic images of human faces from corresponding hand-drawn sketches. We aggregate and align datasets CUHK and FS2K of facial sketches and corresponding real facial photos for training and evaluation. For our baseline we tried to follow 4 papers, sketch2face [Julia Gong et al.], pix2pix [Philip Isola et al.], and Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks [Jun-Yan Zhu, Alexei A. Efros et al.] 

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [PyTorch 1.11](https://pytorch.org/)
* [NumPy](https://numpy.org/)
* [OpenCV](https://opencv.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* PyTorch
  ```sh
  conda install -c pytorch pytorch
  ```
* NumPy
  ```sh
  conda install numpy
  ```
* OpenCV
  ```sh
  conda install -c conda-forge opencv
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTIONS -->
## Contributors

1. [Parth Goel](https://github.com/parthgoe1)
2. [Prashant Kanth](https://github.com/kanthprashant)
3. [Rishika Bhanushali](https://github.com/rb-rishika)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* Philip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros: Image-to-Image Translation with Conditional Adversarial Networks
* Julia Gong, Matthew Mistele: sketch2face: Conditional Generative Adversarial Networks for Transforming Face Sketches into Photorealistic Images.
* Shu-Yu Chen, Wanchao Su, Lin Gao, Shihong Xia, Hongbo Fu: DeepFaceDrawing: Deep Generation of Face Images from Sketches.
* Jun-Yan Zhu, Taesung Park, Philip Isola, Alexei A. Efros: Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks.
* Udemy: Computer Vision A-Z, Practical Deep Learning with Pytorch

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
