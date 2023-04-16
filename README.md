
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">mandelbrot.py</h3>

  <p align="center">
    A script to display the Mandelbrot set with python
  </p>
</p>






<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://ara-systems.net)

The mandelbrot function takes in a real and imaginary part of a complex number c, as well as a maximum number of iterations to perform. It then iteratively computes the sequence $z_n = z_{n-1}^2 + c$, where $z_0 = 0$, until either the sequence diverges (i.e., $|z_n|$ exceeds $2$) or the maximum number of iterations is reached. It returns the number of iterations before the sequence diverges, or the maximum number of iterations if the sequence does not diverge.

### Run

1. Clone the repo
   ```sh
   git clone https://github.com/iion91/mandelbrot.git
   ```
   or download the file
2. Install dependencies
   ```sh
   pip install numba
   pip install numpy
   pip install matplotlib
   ```
3. Start the script 
   ```cmd
   python mandelbrot.py
   ```






[product-screenshot]: images/screenshot.png
[contributors-shield]: https://img.shields.io/github/contributors/iion91/mandelbrot.svg?style=for-the-badge
[contributors-url]: https://github.com/iion91/mandelbrot/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/iion91/mandelbrot.svg?style=for-the-badge
[forks-url]: https://github.com/iion91/mandelbrot/network/members
[stars-shield]: https://img.shields.io/github/stars/iion91/mandelbrot.svg?style=for-the-badge
[stars-url]: https://github.com/iion91/mandelbrot/stargazers
[issues-shield]: https://img.shields.io/github/issues/iion91/mandelbrot.svg?style=for-the-badge
[issues-url]:  https://github.com/iion91/mandelbrot/issues
[license-shield]: https://img.shields.io/github/license/iion91/mandelbrot.svg?style=for-the-badge
[license-url]:  https://github.com/iion91/mandelbrot/blob/master/LICENSE.txt
