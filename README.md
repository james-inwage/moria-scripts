# Moria Utility Scripts

## Prerequisites

Obtain a free API key at https://infura.io/

The key needed is just the string of letters+numbers at the end of the URL's sent to you in the registration email

Node.js is required to run the script

## Installation

```console
> npm init
```

## Running

```console
> node token-balances.js API-KEY BLOCK-HEIGHT
```

where API-KEY is you infura API Key and (optionally) BLOCK-HEIGHT is the height at which you want balances at. If omitted BLOCK-HEIGHT defaults to the latest block.
