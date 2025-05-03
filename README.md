# EnvHunter - .env Secret Extractor

**EnvHunter** is a simple but powerful Python tool designed to hunt down `.env` files and extract sensitive secrets.

## 🚀 Features

- Auto detect `.env` files in target directories
- Parse and extract sensitive environment variables
- Identify and report AWS keys, API keys, DB passwords and more
- Save results to a clean text report for later review
- Lightweight and fast — perfect for OSINT, leak hunting, and security auditing

## 📦 Example Output

```
[+] Found .env at /target/.env

DB_USERNAME=root
DB_PASSWORD=supersecret123
AWS_ACCESS_KEY_ID=AKIAxxxxxxxxxxx
AWS_SECRET_ACCESS_KEY=xxxxxxxxxxxxxxxxxxxx
MAIL_PASSWORD=mailpass2024

[+] Results saved to report.txt
```

## 📌 Usage

```bash
python3 envhunter.py /path/to/scan
```

## 🛡️ Legal Disclaimer

This tool is intended for educational and authorized testing only. Unauthorized scanning or accessing of systems without permission may be illegal.

## Copyright (c) 2025 LeakData-Slyfrosty

** Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

** The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

** THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE

## 📖 License

MIT License (see LICENSE file for details) EnvHunter/.gitignore

# Python
__pycache__/
*.py[cod]
*.egg
*.egg-info/
dist/
build/

# Env files
.env
*.env

# Logs
*.log

# Zips / Dumps
*.zip
