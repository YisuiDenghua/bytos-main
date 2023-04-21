<div align="center">

BytOS
===
[![Built with Nix][builtwithnix badge]][builtwithnix]
[![License: MIT][MIT badge]][MIT]

BytOS is a purely functional Linux distribution. This repository contains the core source tree of BytOS and the configurations to build BytOS with Nix.
</div>


![byt](https://user-images.githubusercontent.com/102890144/233574465-a0135662-d70a-4d6c-9225-9626d25bfab0.png)


## Features

BytOS uses declarative .json files to config the entire operating system, the default config file is `/etc/bytos/configuration.json`. There are some basic modules provided in BytOS, you can also write BytOS modules yourself and import them in your config files. 


## Status

We are still working in progress to bring BytOS out, feel free to open issues and PRs.


[builtwithnix badge]: https://img.shields.io/badge/Built%20With-Nix-41439A?style=for-the-badge&logo=nixos&logoColor=white
[builtwithnix]: https://builtwithnix.org/
[MIT badge]: https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge
[MIT]: https://opensource.org/licenses/MIT
