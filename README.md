Solana  Wallet Generator

Create Solana Wallets with Customized Addresses

Developed in Go, this Ethereum Wallet Generator enables the rapid creation of multiple Ethereum and crypto vanity wallets. It's optimized for speed, capable of generating ten thousand wallets (vanity addresses and mnemonic seeds) in just a second.

Features:

Supports the generation of beautiful and unique vanity wallet addresses.
Offers blazing-fast wallet generation, reaching speeds of over 100k wallets per second with concurrency and private key mode.
Allows customization of vanity addresses using prefixes, suffixes, regex, or specific characters.
Supports infinite wallet generation with an option to set a limit on the number of desired vanity addresses.
Utilizes a hierarchical deterministic path by default.
Provides options for both normal mode (generating wallets with mnemonic phrases) and private key mode (faster generation without mnemonic phrases).
Supports benchmarking of generation speed with the isDryrun flag.
Offers Docker images and executable files for easy usage across platforms.
Installation:

![example](https://github.com/bukaka22/solana-wall-generator/assets/167086581/4d3afbff-c47e-4c8d-8c45-5e9cc93a1a7a)


Modes:

Normal Mode: Generates wallets with mnemonic phrases (default).
Only Private Key Mode: Generates wallets with private keys only, significantly increasing speed but without mnemonic phrases.
Usage:

Specify parameters such as the number of wallets to generate, concurrency level, and mode using command-line flags.
Options include setting a limit on the number of result wallets, defining a specific database output file, and specifying entropy bits for the mnemonic phrase.
Customize vanity addresses using flags like -contains, -prefix, -suffix, or -regex.
Examples:



https://github.com/bukaka22/solana-wall-generator/assets/167086581/4c6df1e3-4c76-4bb7-bd8e-86b007970afe



License: This repository is released under the WTFPL (Do What the Fuck You Want to Public License).

