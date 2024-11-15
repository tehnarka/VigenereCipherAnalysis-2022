# VigenereCipherAnalysis

## Short Description
A Python-based repository for cryptanalysis of the Vigenère cipher. Includes tools for encryption, decryption, key length determination, and statistical analysis of cipher text indices.

## Overview
This repository provides a comprehensive implementation for analyzing and breaking the Vigenère cipher. Key functionalities include:

- **Encryption and Decryption:** Encrypt or decrypt text using the Vigenère cipher.
- **Key Length Detection:** Utilize methods like coincidence index or statistical matching.
- **Key Character Discovery:** Use frequency analysis and Mi(g) function.
- **Cipher Text Analysis:** Compute indices of coincidence for variable key lengths.

## Features
- Automated encryption of plaintext with user-defined keys.
- Decryption support for partially or fully recovered keys.
- Key length analysis using statistical metrics.
- Export of analytical data to Excel for visualization.
- Integration-ready Python scripts for custom use cases.

## Requirements
- Python 3.7+
- pandas
- openpyxl
- random
- A text file (`1.txt`) containing cipher or plaintext.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/VigenereCipherAnalysis.git
   cd VigenereCipherAnalysis
   ```
2. Place your plaintext or ciphertext file in the repository folder as `1.txt`.
3. Run Python scripts for encryption, decryption, or analysis:
   ```bash
   python SymCryptoLab2.py
   ```
4. View exported data and results in the generated Excel files.

## Outputs
- **`encr-text-30.txt`:** Encrypted text with the Vigenère cipher.
- **`indexes1.xlsx`:** Index of coincidence for different key lengths.
- **`Mi(g).xlsx`:** Frequency analysis for key character discovery.
- **`decrypted text -- var1-1.txt`:** Decrypted text using discovered key.

## Example Results
- **Key Length Analysis:**
  - Length 15 has the highest index of coincidence (I = 0.056).
- **Decryption Key:**
  - Key discovered: ['a', 'r', 'u', 'd', 'a', 'z', 'o', 'v', 'a', 'r', 'x', 'i', 'm', 'a', 'g'].
- **Decrypted Text:**
  - "Past fifteen days, the old house gradually began to come alive..."

