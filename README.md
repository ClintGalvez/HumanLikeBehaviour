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
<p align="center">
  <a href="https://github.com/ClintGalvez/HumanLikeBehaviour">
    <img src="cover.png" alt="Cover" width="auto" height="auto">
  </a>

  <h3 align="center">Human-Like Behaviour</h3>

  <p align="center">
    Recreating human-like behaviour for game AI
    <br />
    <a href="https://github.com/ClintGalvez/HumanLikeBehaviour"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ClintGalvez/HumanLikeBehaviour">View Demo</a>
    ·
    <a href="https://github.com/ClintGalvez/HumanLikeBehaviour/issues">Report Bug</a>
    ·
    <a href="https://github.com/ClintGalvez/HumanLikeBehaviour/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Tensorboard](#tensorboard)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Here's a blank template to get started:
**To avoid retyping too much info. Do a search and replace with your text editor for the following:**
`ClintGalvez`, `HumanLikeBehaviour`, `ClintGalvezz`, `clintgalvezz@gmail.com`


### Built With

* []()
* []()
* []()



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
```sh
npm install npm@latest -g
```

### Installation

1. Clone the repo
```sh
git clone https://github.com/ClintGalvez/HumanLikeBehaviour.git
```
2. Install NPM packages
```sh
npm install
```

### Tensorboard
**Note: as of UE 5.5, you may come across and issue where the plugin fails to find tensorboard within the Engine files, so to fix this we'll have tensorboard installed within the project files instead of the Engine files**
#### Installation
1. (Optional) open the project in Unreal to generate the required `Intermediate` folder
2. within the project directory `{Path to PROJECT}` navigate to the following directory `\Intermediate\PipInstall\Scripts`
```sh
{Path to PROJECT}\Intermediate\PipInstall\Scripts
```

3. run the following pip command to install tensorboard
```sh
./python -m pip install tensorboard
```

#### Run
1. go to the following directory
```sh
{Path to PROJECT}\Intermediate\PipInstall\Scripts
```

2. run the following command
```sh
tensorboard --logdir={Path to PROJECT}\Intermediate\LearningAgents\TensorBoard\runs
```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/ClintGalvez/HumanLikeBehaviour/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Clint Galvez - [@ClintGalvezz](https://twitter.com/ClintGalvezz) - clintgalvezz@gmail.com

Project Link: [https://github.com/ClintGalvez/HumanLikeBehaviour](https://github.com/ClintGalvez/HumanLikeBehaviour)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Professor Yuhong Guo](https://carleton.ca/scs/people/yuhong-guo/)
* [Hanping Zhang - PhD student supervised by Professor Yuhong Guo](https://www.linkedin.com/in/jaghanpingzhang/)
* [Lastly my friends Jacob Boruszkowski, Vy Nguyen, Kiara Lee, David Kenneth Burnett, Christopher Romero, and Shaun Adrian Bernardo Pangilinan]()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ClintGalvez/repo.svg?style=flat-square
[contributors-url]: https://github.com/ClintGalvez/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ClintGalvez/repo.svg?style=flat-square
[forks-url]: https://github.com/ClintGalvez/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/ClintGalvez/repo.svg?style=flat-square
[stars-url]: https://github.com/ClintGalvez/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/ClintGalvez/repo.svg?style=flat-square
[issues-url]: https://github.com/ClintGalvez/repo/issues
[license-shield]: https://img.shields.io/github/license/ClintGalvez/repo.svg?style=flat-square
[license-url]: https://github.com/ClintGalvez/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/ClintGalvez
[product-screenshot]: images/screenshot.png
