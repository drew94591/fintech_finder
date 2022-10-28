# Fintech Finder
Fintech Finder is an application that customers can use to find fintech professionals from among a list of candidates, hire them, and pay them instantly with cryptocurrency.  The application also integrates a local Ethereum blockchain network using the Genache application. 

---

## Technologies

This application leverages python 3.7 with the following libraries and packages:

* [streamlit](https://streamlit.io) - An open-source app python framework that turns data scripts into shareable web apps in minutes.

* [Web3](https://web3py.readthedocs.io/en/stable/overview.html) - A Python library for connecting to and performing operations on Ethereum-based blockchains.

* [ethereum-tester](https://pypi.org/project/ethereum-tester/0.1.0a4/) - A Python library that provides access to the tools we'll use to test Ethereum-based applications.

* [mnemonic](https://pypi.org/project/mnemonic/) - A Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.

* [bip44](https://pypi.org/project/bip44/) - A Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.

* [Ganache](https://trufflesuite.com/ganache/) - A program that allows you to quickly setup a local blockchain, which you can use to test and develop smart contracts.

---

## Installation Guide

Before running the application first install the following dependencies.

### Python Modules
```python
  $ pip install w3==5.17
```

### Python Modules
```python
  $ pip install eth-tester==0.5.0b3
```

### Python Modules
```python
  $ pip install mnemonic
```

### Python Modules
```python
  $ pip install bip44
```

### Python Modules
```python
  $ pip install streamlit
```

---

## Usage

To use the Fintech Finder application you must first launch Streamlit by executing the following command within Git Bash:

```python
streamlit run fintech_finder.py
```

As is illustrated below:

![Fintech Finder](Images/fintech_finder.gif)


---

## Contributors

Brought to you by [Drew Herrera](https://www.linkedin.com/in/andrewjherrera).

---

## License

Licensed under the MIT License. Copyright 2022 Drew Herrera.
