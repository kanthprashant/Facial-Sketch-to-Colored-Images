<div id="top"></div>

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

<img src="/Images/1.jpg" width="800" height="600">

In this project, we tackle the problem of generating color photorealistic images of human faces from corresponding hand-drawn sketches. We aggregate and align datasets CUHK and FS2K of facial sketches and corresponding real facial photos for training and evaluation. For our baseline we tried to follow 4 papers, sketch2face [Julia Gong et al.], pix2pix [Philip Isola et al.], and Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks [Jun-Yan Zhu, Alexei A. Efros et al.] <br/>
For more details, please see [Report](/Report/)

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

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
   git clone https://github.com/kanthprashant/Facial-Sketch-to-Colored-Images.git
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

* Philip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros: Image-to-Image Translation with Conditional Adversarial Networks
* Julia Gong, Matthew Mistele: sketch2face: Conditional Generative Adversarial Networks for Transforming Face Sketches into Photorealistic Images.
* Shu-Yu Chen, Wanchao Su, Lin Gao, Shihong Xia, Hongbo Fu: DeepFaceDrawing: Deep Generation of Face Images from Sketches.
* Jun-Yan Zhu, Taesung Park, Philip Isola, Alexei A. Efros: Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks.
* Udemy: Computer Vision A-Z, Practical Deep Learning with Pytorch

<p align="right">(<a href="#top">back to top</a>)</p>

