# OMAX Token List

## Extending Fields for token list:

### Mandatory 

-  `chainId`:   Chain id. Mainnet - 311, Testnet - 332. As Number and not String.
-  `symbol`:    Short ticker style symbol of token.
-  `name`:      Longer human version of token.
-  `address`:   Address of ERC-20 token, in [ERC-55](https://eips.ethereum.org/EIPS/eip-55) mixed-case format.
-  `decimals`:  The decimals of the token. As Number and not String.

### Optional

-  `logoURI`: An optional logo of your token. Must be a **square** (recommended: 128x128) PNG w/ transparent background. Please compress using https://tinypng.com. By default: https://raw.githubusercontent.com/OMAX-Development/token-list/master/assets/${address}/logo.png
-  `tags`:    An array of tag identifiers associated with the token.

#  IMPORTANT !
 
Use **CHECKSUMMED** address (with lower and upper cases)

✅ 0xf3ff0c99dfe3a50C3E1e8ceF4399aF047e75416a

❌ 0xf3ff0c99dfe3a50c3e1e8cef4399af047e75416a

### Double check this condition when you are:
1) Creating new folder in `assets` directory
2) Updating | Adding token info into `mainnet.tokenlist.json` or `testnet.tokenlist.json` 

# A last note

This list is maintained by volunteers in the community &amp; people like you around the internet. It may not always be up to date, and it may occasionally get it wrong. If you find an error or omission, please open an issue or make a PR with any corrections.

---

If you have a problem with git please don't hesitate to contact me on Telegram: [@romanow_eth](https://t.me/romanow_eth)




## Blocked

```json
{
  "token": "address",
  "name": "token name",
  "description": "Description of the project or account",
  "stolen": 100,
  "tags": [
    "rugpull",
    "scam"
  ],
  "addresses": {
    "bounded address": {
      "link": "link to action",
      "text": "action description"
    }
  }
}
```