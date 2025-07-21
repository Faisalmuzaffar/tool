# Comprehensive Online Tools

A complete web-based toolkit for text processing, encoding/decoding, hashing, and various utility functions.

## Features

### Text Processing Tools
- Text case conversion (camelCase, PascalCase, snake_case, kebab-case)
- Text reversal (characters, words, lines, word order)
- Text formatting and cleanup
- Find and replace with regex support
- Text sorting and duplicate removal
- Line numbering

### Encoding/Decoding Tools
- Base64, Base32, Base58 encoding/decoding
- URL encoding/decoding
- HTML encoding/decoding
- Hex encoding/decoding

### Hashing Tools
- MD5, SHA-1, SHA-256, SHA-512 hashing
- CRC32 calculation
- File hashing support

### Cryptography Tools
- RSA key generation, encryption, decryption, signing, verification
- ECDSA key generation, signing, verification

### Utility Tools
- QR Code generation with customization options
- JSON formatting, validation, and minification
- XML formatting and validation
- Password generation with strength analysis
- UUID generation (v1 and v4)
- Random number generation
- Text statistics and word counting
- Timestamp conversion
- Lorem Ipsum generation
- Text diff comparison

## Usage

1. Open `comprehensive-online-tools.html` in a web browser
2. Select the desired tool from the categories
3. Enter your input text or upload a file (for file-based tools)
4. Use the tool options to customize the processing
5. View results and copy/download as needed

## Features

- **Real-time processing** for most tools
- **File upload support** for applicable tools
- **Drag and drop** file upload
- **Keyboard shortcuts** (Ctrl+Enter to process, Ctrl+C to copy)
- **Responsive design** that works on desktop and mobile
- **Dark mode support** (follows system preference)
- **Download results** as text files
- **Copy to clipboard** functionality

## Keyboard Shortcuts

- `Ctrl + Enter`: Process input
- `Ctrl + C`: Copy output
- `Ctrl + L`: Clear input/output
- `Ctrl + E`: Add example text
- `Ctrl + /`: Show shortcuts help

## Technology Stack

- Pure HTML, CSS (Tailwind), and JavaScript
- External libraries:
  - CryptoJS for cryptographic functions
  - JSEncrypt for RSA operations
  - QRCode.js for QR code generation

## Browser Compatibility

Works in all modern browsers that support:
- ES6+ JavaScript features
- Web Crypto API (for ECDSA operations)
- Canvas API (for QR code generation)

## License

This project is open source and available under the MIT License.
