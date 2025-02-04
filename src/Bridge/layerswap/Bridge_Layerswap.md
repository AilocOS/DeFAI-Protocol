# BRIDGE

## Description
Transfer tokens between different blockchain networks using cross-chain bridge protocols. This supports multiple token types (e.g., ERC20, NFTs) and chains, including Ethereum, BSC, Polygon, and more.

## Keywords
Bridge tokens, cross-chain transfer, bridge crypto, token bridge, cross-chain bridge, bridge ETH, bridge BNB, bridge assets, blockchain bridge, bridge cryptocurrency, bridge to Polygon, bridge to BSC, cross-chain swap, bridge to Arbitrum, bridge to Optimism, bridge to L2, chain transfer, bridge digital assets, cross-chain movement, bridge wallet, token bridging, bridge network transfer, bridge to mainnet, bridge coins, network bridge.

## JSON 

```json
"action": "BRIDGE"
"network": "1"
"inputs": [
    {
        "name": "inputToken",
        "type": "string",
        "default": ""
    },
    {
        "name": "inputNetwork",
        "type": "string",
        "default": ""
    },
    {
        "name": "outputToken",
        "type": "string",
        "default": ""
    },
    {
        "name": "outputNetwork",
        "type": "string",
        "default": ""
    },
    {
        "name": "amount",
        "type": "string",
        "default": ""
    },
    {
        "name": "toAddress",
        "type": "string",
        "default": ""
    }
]
"outputs": [
    {
        "name": "success",
        "type": "boolean"
    }
]
"protocol": {
    "name": "LAYERSWAP",
    "quote": "https://api.layerswap.io/api/v2/swaps"
}
