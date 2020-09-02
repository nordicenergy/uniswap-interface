[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/nordicenergy/uniswap-interface) [![Netlify Status](https://api.netlify.com/api/v1/badges/7ba1490a-5215-43f3-9d9a-f409dad9ba12/deploy-status)](https://app.netlify.com/sites/nordicenergy-uniswap/deploys)

# Nordic Energy - Uniswap Interface

[![Tests](https://github.com/nordicenergy/uniswap-interface/workflows/Tests/badge.svg)](https://github.com/nordicenergy/uniswap-interface/actions?query=workflow%3ATests)
[![Styled With Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io/)

An custom interface for Nordic Energy´s Uniswap -- a protocol for decentralized exchange of Ethereum tokens.

- Website: [uniswap.nordicenergy.io](https://uniswap.nordicenergy.io/)
- Interface: [uniswap.nordicenergy.io](https://uniswap.nordicenergy.io)
- Docs: [uniswap.nordicenergy.io/docs/](https://uniswap.nordicenergy.io/docs/)
- Twitter: [@UniswapProtocol](https://twitter.com/UniswapProtocol)
- Reddit: [/r/Uniswap](https://www.reddit.com/r/Uniswap/)
- Email: [contact@uniswap.org](mailto:contact@uniswap.nordicenergy.io)
- Discord: [Uniswap](https://discord.gg/Y7TF6QA)
- Whitepaper: [Link](https://hackmd.io/C-DvwDSfSxuh-Gd4WKE_ig)

## Accessing the Nordic Energy´s Uniswap Interface

To access the Nordic Energy´s Uniswap Interface, use an IPFS gateway link from the
[latest release](https://github.com/nordicenergy/uniswap-interface/releases/latest), 
or visit [uniswap.nordicenergy.io](https://uniswap.nordicenergy.io).

## Listing a token

Please see the
[@uniswap/default-token-list](https://github.com/uniswap/default-token-list) 
repository.

## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to e.g. `"https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"` 

Note that the interface only works on testnets where both 
[Uniswap V2](https://uniswap.org/docs/v2/smart-contracts/factory/) and 
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Contributions

**Please open all pull requests against the `master` branch.** 
CI checks will run against all PRs.

## Accessing Uniswap Interface

The Nordic Energy´s Uniswap Interface supports swapping against, and migrating or removing liquidity from Uniswap. However,
if you would like to use Uniswap V1 source code. The Uniswap V1 interface for mainnet and testnets is accessible via IPFS gateways 
linked from the [v1.0.0 release](https://github.com/Uniswap/uniswap-interface/releases/tag/v1.0.0).
