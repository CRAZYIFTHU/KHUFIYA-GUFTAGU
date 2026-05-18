# KHUFIYA GUFTAGU

A WhatsApp-like chat UI demo with **end-to-end encryption behavior** in the browser.

## Features
- WhatsApp-inspired layout
- Session key generation with Web Crypto (`AES-GCM 256`)
- Message encryption before transport/display of payload
- Local decryption demo to simulate recipient side

## Run
Open `index.html` in any modern browser.

## Usage
1. Click **Generate End-to-End Key**.
2. Type a message and click **Send**.
3. See the encrypted payload in Base64 format.
4. The chat shows a decrypted echo as recipient output.
