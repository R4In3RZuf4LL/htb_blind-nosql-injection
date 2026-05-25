# Blind NoSQL Injection Extractor

> This Python script automates the extraction of a secret tracking number from a vulnerable NoSQL‑based web application using a blind regex oracle.
> By sending crafted JSON payloads and analyzing the server’s responses, the script reconstructs the value character by character.
> How It Works

- Sends POST requests with MongoDB‑style $regex payloads

- Detects whether a guessed prefix matches based on the server response

- Brute‑forces the secret value one character at a time

- Reconstructs the full tracking number automatically

### Requirements

- Python 3

- requests library

### Disclaimer

This script is for educational purposes only and must be used only on systems you own or are authorized to test.
