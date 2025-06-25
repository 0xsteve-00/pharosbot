![Node.js](https://img.shields.io/badge/node-%3E=18.0.0-brightgreen)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)



# 🦊 PharosBot

Automated bot for the [Pharos Testnet](https://pharosnetwork.xyz), designed for daily check-ins, faucet claims, token swaps, liquidity adding, and more.

## ✨ Features

- ✅ Auto faucet claim
- ✅ Daily check-in automation
- ✅ Auto-swap and liquidity add
- ✅ Proxy support

## Installation ⚙️

1. Clone the repository:
   ```bash
   git clone https://github.com/0xsteve-00/pharosbot.git
   cd pharosbot
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory with your private keys:
   ```
   PRIVATE_KEY_1=your_first_private_key_here
   PRIVATE_KEY_2=your_second_private_key_here
   ```

4. (Optional) Add proxies to `proxies.txt` (one per line):
   ```
   http://user:pass@ip:port
   socks5://user:pass@ip:port
   ```
   
## Usage 🚀

   Run the bot:
   ```bash
   node index.js
   ```
MIT License

Copyright (c) 2025 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
