# MSF in Termux

> Installer script for Metasploit Framework on Termux (no root required).

## Overview

This repository contains a bash installer that automates downloading and installing **Metasploit Framework** in Termux.

> **Legal & ethical notice:** Use Metasploit only on systems you own or where you have explicit, written permission to test. Unauthorized use is illegal and unethical.

---

## Prerequisites

* Termux installed on an Android device (no root required).
* Stable internet connection.
* At least 1.5–2 GB free storage (more recommended).

---

## Quick install (example)

1. Save the installer script as `msf-install.sh` in Termux.
2. Make it executable and run it:

```bash
pkg update -y && pkg upgrade -y
pkg install ruby clang make libxml2 libxslt libiconv -y
pkg install wget -y
wget https://raw.githubusercontent.com/IamTechyAnimesh/msf-termux/refs/heads/main/msf-install.sh
chmod +x msf-install.sh
./msf-install.sh
```

3. When installation finishes, start Metasploit with:

```bash
msfconsole
```
---

## Security & ethics

Do not use Metasploit for unauthorized access, privacy breaches, or damage. Keep Termux and packages updated.

---

## License

MIT License — © 2025 IamTechyAnimesh
