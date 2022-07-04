[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://diora.network/">
    <img src="./logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Diora Network</h3>

  <p align="center">
    Diora Network is a incentivised smart contract parachain, utilizing advanced PoSM with Double Validation & Randomization for security guarantees
    <br />
    <a href="https://diora.network/docs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://diora.network/">View Demo</a>
    ·
    <a href="https://github.com/diora-network/diora/issues">Report Bug</a>
    ·
    <a href="https://github.com/diora-network/diora/issues">Request Feature</a>
    ·
    <a href="https://github.com/diora-network/diora/pulls">Send a Pull Request</a>
  </p>
</p>


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Devnet](#built-with)
* [Running Diora](#getting-started)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

https://user-images.githubusercontent.com/49777543/168764160-121147ce-78c3-4e77-a020-5e03df8e6e06.mp4





### Devnet Chain Specs

The Devnet is a public early access testnet to validate the technical architecture and security of our blockchain in a setting that is as realistic as possible.

Chain ID
```
201
```
RPC
```
https://testnet.diora.network/
```
Websocket
```
https://dev.diora.network/
```


<!-- GETTING STARTED -->
## Getting Started

Launch a local setup including a Relay Chain and a Parachain

* polkadot & diora
```
# Compile Polkadot
git clone https://github.com/paritytech/polkadot
git checkout release-v0.9.20
cargo build --release

# Compile Diora
https://github.com/Diora-Network/Diora
cargo build --release
```
By shell 

```
cd script
bash ./build.sh
bash ./start-all.sh
# log
tail -f data/log.2022

# stop-all and remove data
bash ./stop-all.sh
```
After the relay chain produces 10 blocks, the parachain starts producing blocks

# Launch the multi-chain
```
polkdot-launch ./diora/polkadot-launch/config.json

```

<!-- USAGE EXAMPLES -->
## Usage


Facuet

Wallets

Dex





<!-- CONTRIBUTING -->
## 🤝 Contributing

Contributions are what make the DioraDAO such an amazing place to be learn, inspire, and create. Any contributions you make are **extremely appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## 📝 License 

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## 📫 Contact

Diora Network - [@DioraNetwork](https://twitter.com/dioranetwork) - support@diora.network

Project Link: [https://github.com/diora-network/diora](https://github.com/diora-network/diora)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Purestake](https://purestake.io)
* [Astar](https://astar.newtwork)
* [ORML]()






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[forks-shield]: https://img.shields.io/github/forks/
[forks-url]: https://github.com/diora-network/diora/members
[stars-shield]: https://img.shields.io/github/stars/
[stars-url]: https://github.com/diora-network/diora/stargazers
[issues-shield]: https://img.shields.io/badge/github/issues/
[issues-url]: https://github.com/diora-network/diora/issues
[linkedin-shield]: https://img.shields.io/badge/contact-us-blue?logo=discord&logoColor=white
[linkedin-url]: https://discord.me
