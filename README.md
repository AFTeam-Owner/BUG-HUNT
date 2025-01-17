<div align="center">
  <img src="https://envs.sh/HFQ.jpg" alt="Bug Hunter Pro Logo" width="200px">
  
  <h1>🔍 Bug Hunter Pro</h1>
  
  <p>
    <img src="https://img.shields.io/badge/version-2.0.0-blue.svg" alt="version 2.0.0">
    <img src="https://img.shields.io/badge/python-3.7+-green.svg" alt="python 3.7+">
    <img src="https://img.shields.io/badge/license-MIT-orange.svg" alt="license MIT">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome">
  </p>

  <h3>🚀 Advanced Security Testing & Bug Hunting Tool</h3>
</div>

## 🎯 Available Scanners

1. **Injection Vulnerabilities**
   - SQL Injection (using Ghauri)
   - Command Injection (using Commix)
   - NoSQL Injection
   - LDAP Injection
   - XXE Injection (using Nuclei)

2. **Cross-Site Scripting (XSS)**
   - Reflected XSS
   - Stored XSS
   - Using XSStrike

3. **CSRF Testing**
   - Form Analysis
   - Token Validation
   - Using CSRFmap

4. **Authentication Testing**
   - Using Hydra
   - Using Medusa

5. **Additional Security Tests**
   - Misconfiguration Scanner
   - Sensitive Data Scanner
   - Directory Traversal Scanner
   - File Upload Scanner
   - SSRF Scanner
   - Subdomain Takeover Scanner
   - API Security Scanner
   - Open Redirect Scanner
   - Crypto Scanner

## 🚀 Installation

```bash
git clone https://github.com/AFTeam-Owner/BUG-HUNTER.git
cd bug-hunter-pro

pip3 install -r requirements.txt

git clone https://github.com/r0oth3x49/ghauri.git
cd ghauri && python3 setup.py install

git clone https://github.com/commixproject/commix.git

git clone https://github.com/s0md3v/XSStrike.git

git clone https://github.com/Pradeepjairam/CSRFmap.git

sudo apt-get install hydra medusa
```

## 💻 Usage

```bash
python3 bug_hunter.py
```

## 📋 Requirements

- Python 3.7+
- Required Python packages:
  - requests
  - httpx
  - beautifulsoup4
  - rich

## 🔧 Features

### Batch URL Scanning
- Support for scanning multiple URLs from a file
- Results saved with timestamps
- Detailed vulnerability reports

### Real-time Progress Tracking
- Total URLs counter
- Vulnerable URL counter
- Results saved to timestamped files

### Interactive Menus
- User-friendly interface using Rich library
- Clear categorization of vulnerability types
- Easy navigation between different scanners

## ⚠️ Disclaimer

<table>
  <tr>
    <td>⚠️</td>
    <td>This tool is for educational and authorized testing purposes only. Always obtain proper authorization before testing any systems.</td>
  </tr>
</table>

## 📞 Support

For support and queries:
- Telegram: [@AF_Team_Owner](https://t.me/AF_Team_Owner)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

<div align="center">
  <sub>Built with ❤️ by the security community | Developed by AF Farhan Jihady</sub>
</div>
