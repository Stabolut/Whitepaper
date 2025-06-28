# Stabolut Whitepaper

This repository contains the LaTeX source code for the Stabolut Whitepaper.

## Latest Version

The latest version of the whitepaper is [Stabolut_WP_0_7_2.pdf](./Stabolut_WP_0_7_2.pdf).

## Abstract

Stablecoins, which maintain a stable value, are a popular alternative to traditional cryptocurrencies. However, the most common type, fiat-backed stablecoins, have drawbacks such as centralization, counterparty risk, and lack of transparency.

USB, a crypto-asset-backed stablecoin, is introduced as a solution. It mimics the US dollar's value using a unique mechanism of shorting crypto assets through inverse perpetual swaps. This approach makes USB free from the constraints of traditional fiat-backed stablecoins. Moreover, USB doesn't require bank accounts or other centralized entities, enhancing its decentralization and reducing its susceptibility to regulatory crackdowns or frozen funds.

This whitepaper introduces a revolutionary enhancement to the Stabolut ecosystem: a comprehensive value accrual framework for the SBL governance token. This framework transforms SBL from a simple utility token into a multi-dimensional asset that captures value directly from the protocol's success. Key features include governance-controlled treasury surplus distribution, progressive revenue sharing, deflationary buyback mechanisms, and tiered utility benefits. This positions Stabolut as a leader in next-generation DeFi tokenomics and sustainable protocol design.

## Compiling the PDF

To compile the whitepaper into a PDF, you will need a LaTeX distribution (such as TeX Live, MiKTeX, or MacTeX). Once installed, you can compile the `main.tex` file.

```bash
pdflatex main.tex
```

## Project Structure

- `main.tex`: The main LaTeX file.
- `general.tex`: Contains package imports and general settings.
- `content/`: Contains the individual chapters of the whitepaper.
- `figure/`: Contains the figures used in the whitepaper.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
