<div align="center">

# Personal-Finances

A collection of notebooks to help me with my finances

![GitHub repo size](https://img.shields.io/github/repo-size/AucaCoyan/Personal-Finances)
![Lines of code](https://img.shields.io/tokei/lines/github/AucaCoyan/Personal-Finances)
![GitHub Pipenv locked Python version](https://img.shields.io/github/pipenv/locked/python-version/AucaCoyan/Personal-Finances)

![GitHub last commit](https://img.shields.io/github/last-commit/AucaCoyan/Personal-Finances)
![GitHub issues](https://img.shields.io/github/issues/AucaCoyan/Personal-Finances)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AucaCoyan/Personal-Finances)
![GitHub](https://img.shields.io/github/license/AucaCoyan/Personal-Finances)

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

[Features](#features) •
[Installation](#installation) •
[Use](#use) •
[Contributing](#contributing)

![Alt text](https://raw.githubusercontent.com/AucaCoyan/Personal-Finances/main/img/Screenshot%20from%202022-03-28%2008-50-35.png)

</div>

---

# Features

- [x] New File
- [x] Open a file
- [ ] Save file
- [x] Save a file as
- [x] Quit

---

# Installation

1. Clone the repo

```
git clone https://github.com/AucaCoyan/Personal-Finances
```

2. Install dependencies

```
pipenv install
```

3. Open the notebooks with Jupyter and start editing!

---

# Use

A little heads-up, most of the notebooks are in spanish and oriented to the argentinan markets.

You can start logging your accounts, monthly expenses in `resumen.ipynb`

## I have an error on resumen.ipynb!

> FileNotFoundError: [Errno 2] No such file or directory: 'data/CCL.csv'

Yes, that's because you didn't generate `CCL.csv`. You have to open `/Data/DescargarCCL.ipynb` and run it, so it generates the `CCL.csv` file

## What is `coingecko.ipynb`?

Just a tiny experiment to calculate how much is the market value of coingecko categories without all the ecosystems

## And what is `Ecovalores.ipynb`?

It's my first test to process data from a broker. Download the data from the broker and start testing!

## What about `btc.ipynb`?

I use `yfinance` for downloading the BTC price history

---

# Contributing

I'm open to suggestions or PRs!

Please feel free to contribute as you wish

<!--- template

# Section 1

Text lore ipsum It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

---

# Installation

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

---

# Configuration

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

---

# Contributing

I'm open to suggestions or PRs!
Please feel free to contribute as you wish

<details>
<summary>Linux (tree 1)</summary>

To install zoxide, run this command in your terminal:

```sh
curl -sS https://webinstall.dev/zoxide | bash
```

Alternatively, you can use a package manager:

| Distribution  | Repository            | Instructions             |
| ------------- | --------------------- | ------------------------ |
| Ubuntu 21.04+ | [Ubuntu Packages]     | `apt install zoxide`     |
| Void Linux    | [Void Linux Packages] | `xbps-install -S zoxide` |

</details>

<details>
<summary>macOS (tree 2)</summary>

To install zoxide, use a package manager:

| Repository | Instructions          |
| ---------- | --------------------- |
| [Homebrew] | `brew install zoxide` |
| [MacPorts] | `port install zoxide` |

</details>

<details>
<summary>Windows (tree 3)</summary>

To install zoxide, run this command in your command prompt:

```sh
curl.exe -A "MS" https://webinstall.dev/zoxide | powershell
```

Alternatively, you can use a package manager:

| Repository      | Instructions                    |
| --------------- | ------------------------------- |
| **[crates.io]** | `cargo install zoxide --locked` |
| [Chocolatey]    | `choco install zoxide`          |

</details>

--->
