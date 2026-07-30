# Duco Wallet

<p align="center">
A simple command-line client for interacting with Duino-Coin accounts.
</p>

---

## About

Duco Wallet is a small Python CLI application that allows users to interact with their Duino-Coin account directly from the terminal.

This project was built to practice:
- API requests
- command-line interfaces
- file handling
- user interaction in Python

---

## Features

Current features:

- ✅ Check account balance
- ✅ View connected miners
- ✅ Send transactions
- ✅ Check transactions using hash or ID
- ✅ View recent transactions
- ✅ Save username locally for easier login
- ✅ Terminal color interface

---

## Preview

Example:

```
hello welcome to cmd wallet

what do you want me to do for you?

[1] remove saved username
[2] check balance
[3] check miners
[4] do transaction
...
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/amirsamgoharpey/duco-wallet
```

Install required packages:

```bash
pip install requests colorama keyboard
```

Run:

```bash
python cliduco.py
```

---

## How it works

The program communicates with the Duino-Coin API to retrieve account information and perform actions.

The username can optionally be saved locally in:

```
ducouser.txt
```

The application does **not** save your password.

---

## Requirements

- Python 3.x
- requests
- colorama
- keyboard

---

## Future ideas

Possible improvements:

- Better GUI interface
- More wallet features
- Improved error handling
- Transaction history export

---

## License

This project is open source and free to use.

Feel free to modify and improve it.
