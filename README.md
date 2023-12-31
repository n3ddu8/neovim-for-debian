<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
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
[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/n3ddu8/neovim-for-debian">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Neovim for Debian</h3>

  <p align="center">
    A Neovim .deb package for Debian based distributions.
    <br />
    <a href="https://github.com/neovim/neovim/wiki"><strong>Explore the original project wiki »</strong></a>
    <br />
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a a href="#installation">Installation</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

A .deb of the latest stable version of Neovim, built from source. Useful for debian based distributions where only an older version of Neovim is available (such as Ubuntu LTS versions) and you can't/won't install an Appimage, Flatpak etc.

I created this project because I use Ubuntu 22.04 via WSL2 at work and the available version is not supported by the lazy plugin manager. After the third time building from source (bricked environment, new laptop etc) I decided I needed a way to more easily grab a pre-packged .deb which was automatically kept up-to-date with the latest release.


<p align="right">(<a href="#readme-top">back to top</a>)</p>






<!-- GETTING STARTED -->
### Installation

Clone the repo and run a local install of the .deb file:
```shell
git clone https://github.com/n3ddu8/neovim-for-debian.git
cd neovim-for-debian
sudo apt install ./nvim-linux64.deb
```


<!-- USAGE EXAMPLES -->
## Usage

Run `nvim` in your terminal to launch Neovim.

_For more information, please refer to the [Original Projects Wiki](https://github.com/neovim/neovim/wiki)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* The good folks over at [Neovim](https://github.com/neovim) for creating such an amazing editor.
* [othneildrew](https://github.com/othneildrew) for providing the [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/n3ddu8/neovim-for-debian.svg?style=for-the-badge
[contributors-url]: https://github.com/n3ddu8/neovim-for-debian/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/n3ddu8/neovim-for-debian.svg?style=for-the-badge
[forks-url]: https://github.com/n3ddu8/neovim-for-debian/network/members
[stars-shield]: https://img.shields.io/github/stars/n3ddu8/neovim-for-debian.svg?style=for-the-badge
[stars-url]: https://github.com/n3ddu8/neovim-for-debian/stargazers
[issues-shield]: https://img.shields.io/github/issues/n3ddu8/neovim-for-debian.svg?style=for-the-badge
[issues-url]: https://github.com/n3ddu8/neovim-for-debian/issues
[license-shield]: https://img.shields.io/github/license/n3ddu8/neovim-for-debian.svg?style=for-the-badge
[license-url]: https://github.com/n3ddu8/neovim-for-debian/blob/master/LICENSE.txt
[product-screenshot]: images/screenshot.png
