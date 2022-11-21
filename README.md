# Theme for Altcoin Investor

This is the website theme for [AltcoinInvestor.com](https://altcoininvestor.com)

# Instructions

1. [Download this theme](https://github.com/TryGhost/Lyra/archive/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file
3. Unzip the theme archive on your computer and locate the file called `routes.yaml`
4. Inside Ghost admin, go to the `Labs` settings area and scroll down until you see the `Custom Routes` section
5. Upload the `routes.yaml` from this theme

That's it! If you need help, check out the <a href="https://ghost.org/docs/members/">Ghost members documentation</a> or chat with other Ghost users on <a href="https://forum.ghost.org">Ghost forum</a>.

![screenshot](https://user-images.githubusercontent.com/120485/67228748-1fdd1400-f464-11e9-921f-ecbf5f412ed5.png)


# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
yarn zip
```

# PostCSS Features Used

- Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.
- Variables - Simple pure CSS variables
- [Color Function](https://github.com/postcss/postcss-color-function)


# Copyright & License

Copyright (c) 2013-2021 Ghost Foundation - Released under the [MIT license](LICENSE).


# Website Links & Articles
[Best Crypto to Buy Now](https://altcoininvestor.com/best-crypto-to-buy-now/)

[Best Low Cap Altcoins](https://altcoininvestor.com/low-cap-gems/)

### Cryptocurrency Analysis
[Brief History of Bitcoin Bull & Bear Markets](https://altcoininvestor.com/history-of-bitcoin-bull-bear-market/)

[How to Evaluate a Cryptocurrency](https://altcoininvestor.com/how-to-evaluate-crypto/)

[Bitcoin Halving Cycle](https://altcoininvestor.com/bitcoin-halving-cycle/)

[Crypto Chart Patterns](https://altcoininvestor.com/crypto-chart-patterns-cheat-sheet-pdf/)

[Bitcoin Rainbow Chart](https://altcoininvestor.com/bitcoin-rainbow-chart/)

[What is an Altcoin?](https://altcoininvestor.com/altcoin/)

[Today's Fear & Greed Index](https://altcoininvestor.com/fear-and-greed-index/)

[The 4 Phase of a Crypto Market](https://altcoininvestor.com/crypto-market-cycle/)

[The Shemitah Cycle](https://altcoininvestor.com/shemitah-cycle/)

[FOMO (Fear of Missing Out)](https://altcoininvestor.com/fomo/)

[FUD (Fear, Uncertainty & Doubt)](https://altcoininvestor.com/fear-uncertainty-doubt/)

[ROI Calculator (Percentage Gain / Loss  Calculator)](https://altcoininvestor.com/crypto-profit-calculator/)

[Market Capitalization Levels](https://altcoininvestor.com/market-capitalization/)

### NFTs
[Guide to Flipping SOL NFTs for Profit](https://altcoininvestor.com/guide-to-flipping-nfts-for-profit/)

### ISO 20022 & CBDCs
[Biggest Change to our Financial system in 50 years](https://altcoininvestor.com/biggest-change-to-our-financial-system-in-50-years/)

[What is ISO 20022](https://altcoininvestor.com/what-is-iso-20022/)

[Top ISO 20022 Compliant Cryptocurrencies](https://altcoininvestor.com/top-iso20022-crypto)

[What is a Central Bank Digital Currency](https://altcoininvestor.com/cbdc/)

[What is a medium of exchange](https://altcoininvestor.com/medium-of-exchange/)

### Fan Tokens
[What are Fan Tokens?](https://altcoininvestor.com/fan-tokens/)

[Top Fan Tokens 2022](https://altcoininvestor.com/best-fan-tokens/)

### Masternodes
[Best Masternodes](https://altcoininvestor.com/best-masternodes/)
