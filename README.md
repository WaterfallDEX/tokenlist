---
description: 'Build on Waterfall and need help? let us know.'
---

## ✨ Building on Waterfall and Arbitrum 🌊

## **Waterfall Contracts:**

**Waterfall Token Address**: `0x4e6482b05D13085f1C4A7e2Ef612ba43104f71b9`

**Router Address**: `0x8420672ee90F43c46A13715F714c919d04296F07`

**Factory Address**: `0x63FD0a6acBfFB128E7BC7753BFA3B8639A233d50`

**wETH Address**: `0x82af49447d8a07e3bd95bd0d56f35241523fbab1`

## How to get your token LOGO on Waterfall:

### 1. Image for the Token Logo <a id="1-image-for-the-token-logo"></a>

> * **File Extension**: `png` . Uppercase `PNG` is considered invalid
> * **File Name**：`logo.png`
> * **Size**: `256px by 256px`
> * **Background**: Transparent is a must

### 2. Token Information File <a id="2-token-information-file"></a>

> * Fork the repository and add the token information (example below) to mainnet.tokenlist.json
> * Create a folder under assets/{blockchainName}/{tokenAddress}
> * Add the token icon (logo.png) under the folder created in the previous step
> * Add the token information in the mainnet.tokenlist.json file, in the format shown below

The sample below shows what information has to be included on the `mainnet.tokenlist.json` file.  
Please make sure that the details are accurate and follows the formatting.  
The contract address should follow the checksum address format \(see next requirement\).

```
{
      "name": "Waterfall DEX",
      "symbol": "WTFX",
      "address": "0x4e6482b05D13085f1C4A7e2Ef612ba43104f71b9",
      "chainId": 42161,
      "decimals": 18,
      "logoURI": "https://raw.githubusercontent.com/WaterfallDEX/tokenlist/main/assets/arbitrum/0x4e6482b05D13085f1C4A7e2Ef612ba43104f71b9/logo.png"
},

```
