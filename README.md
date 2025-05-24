# CRVV Cipher Solution

A simple web-based application that provides encryption and decryption tools for multiple classical ciphers:

- **Caesar Cipher**
- **Rail Fence Cipher**
- **Vigenère Cipher**
- **Vernam Cipher**

## Features

- Encrypt and decrypt messages using four popular classical ciphers.
- User-friendly, responsive interface.
- Validates input and preserves formatting.
- Each cipher has its own dedicated page with consistent styling.

## How to Use

1. Open the `index.html` page in your browser.
2. Select the cipher you want to use from the homepage.
3. On the cipher page, input your plaintext or ciphertext and the required key.
4. Click **Encrypt** to encode or **Decrypt** to decode your message.
5. View the output in the result box.

## Ciphers Implemented

### Caesar Cipher

- Shifts letters by a fixed number.
- Key is a number from 0-25.

### Rail Fence Cipher

- Transposes letters by writing them diagonally on rails.
- Key is the number of rails.

### Vigenère Cipher

- Uses a keyword to perform letter shifts.
- Supports encryption and decryption preserving non-alphabet characters.

### Vernam Cipher

- Uses a key of equal length to plaintext.
- Adds values modulo 26 to encrypt.
- Perfectly secure if key is random and used once.

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## Project Structure

```
CRVV-Cipher-Solution/
├── index.html          # Homepage with cipher selection
├── about.html          # About Us page
├── caesar.html         # Caesar Cipher page
├── railfence.html      # Rail Fence Cipher page
├── vigenere.html       # Vigenère Cipher page
├── vernam.html         # Vernam Cipher page
└── README.md           # Project documentation
```


## Link For Our Web Application

https://superb-alpaca-60d01b.netlify.app/

## Contributors

- **Ahmed Ur Razzak**(ID: 2122020050)
- **Ishmam Rahman Shuhan**(ID: 2122020054)
- **Shourov Roy Ratul**(ID: 2122020059)
