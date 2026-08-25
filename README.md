# Stabolut Core Whitepaper (USB & SBL)

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](https://opensource.org/licenses/GPL-3.0)

This repository contains the LaTeX source code and latest compiled PDF for the **Stabolut Decentralized Stablecoin Protocol (USB & SBL Tokens)**.

---

## 📄 Read the Whitepaper

- 📥 **[Download Latest Compiled PDF (Stabolut_WP_0_7_2.pdf)](./Stabolut_WP_0_7_2.pdf)**

---

## 💡 Abstract

Stablecoins that maintain a stable value are essential for the digital economy. However, fiat-backed stablecoins suffer from central points of failure, counterparty risks, and regulatory freeze risks.

**USB** is a decentralized, crypto-asset-backed stablecoin that maintains its peg to the US Dollar using a unique mechanism of shorting crypto assets through inverse perpetual swaps (delta-neutral hedging). USB operates without custodial bank accounts, significantly enhancing decentralization and resilience.

The **SBL Governance Token** implements a value-accrual tokenomics model capturing protocol surplus, revenue sharing, deflationary buybacks, and tiered staking rewards.

---

## 🛠️ Compiling from Source

To compile the LaTeX source into a PDF:

### Prerequisites
Install a TeX distribution:
- **macOS**: MacTeX (`brew install --cask mactex`)
- **Ubuntu/Debian**: `sudo apt install texlive-full`
- **Windows**: [MiKTeX](https://miktex.org/) or TeX Live

### Build Command
```bash
pdflatex main.tex
```

---

## 📂 Repository Structure

- `main.tex`: Master document configuration.
- `general.tex`: Packages and formatting rules.
- `content/`: Individual chapter source files.
- `figure/`: Flowcharts, diagrams, and asset images.

---

## 📄 License

This repository is licensed under the **GNU General Public License v3.0** - see [LICENSE](LICENSE) for details.
