# Vigenère Cipher & Cryptanalysis Tool

A comprehensive Python implementation of the **Vigenère cipher**, featuring encryption, decryption, and automated/interactive cryptanalysis tools (including the **Friedman test**, **Kasiski examination**, and statistical frequency analysis optimized for the **Polish language**).

---

## 🚀 Features

*   **Encryption & Decryption**: Securely encode and decode text using a custom keyword
*   **Key Length Estimation**:
    *   *Friedman Method*: Estimates key length based on the index of coincidence
    *   *Kasiski Examination*: Analyzes repetitive patterns and distances in the ciphertext
*   **Statistical Cryptanalysis**: Frequency analysis using predefined letter probabilities (customized for Polish text, including spaces and common letter weights)
*   **Interactive Caesar Brute-Force**: Breaks down ciphertext columns by key length and allows interactive selection of the most probable plaintext fragments

---

## 📂 Project Structure

```text
├── vigenere.py         # Main script containing cipher logic and cryptanalysis methods
└── Vigenere.txt        # Input ciphertext file for analysis
```

## ⚙️ How to Run
1. Clone the repository:
  ```bash
    git clone https://github.com/cazadorista/vigenere-cipher-cryptanalysis.git
    cd vigenere-cipher-cryptanalysis
  ```
2. Prepare your ciphertext in a file named ```Vigenere.txt``` in the root directory.

3. Run the script:
  ```bash
    python vigenere.py
  ```

4. Follow the interactive prompts in the terminal to perform Kasiski analysis, determine the key length, and decrypt the message.

