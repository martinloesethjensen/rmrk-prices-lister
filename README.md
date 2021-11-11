# rmrk-prices-lister

This script will list an owner's NFT with an amount that is determined in an array over a specified timeinterval.

[Follow LIST spec for RMRK::1.0.0 protocol](https://github.com/rmrk-team/rmrk-spec/blob/master/standards/rmrk1.0.0/interactions/list.md)

This script doesn't account for checking if NFT is belonging to the account address.

## Commands

Example

```sh
node run.js --id "<RMRK_ID>" -e wss://westend-rpc.polkadot.io -s .seed -t 60 --prices 1 2 3 4 5
```

```text
Options:
      --help          Show help                                        [boolean]
      --version       Show version number                              [boolean]
      --id            A file with RMRK IDs.                  [string] [required]
  -e, --endpoint      The wss endpoint. [Westend =
                      wss://westend-rpc.polkadot.io] [Kusama =
                      wss://kusama-rpc.polkadot.io]          [string] [required]
  -s, --secret-key    A file with secret key or seed phrases. It is not saved
                      anywhere.                              [string] [required]
      --prices        array of prices, space separated
                                                [array] [required] [default: []]
  -t, --timeinterval  Timeinterval for listing in seconds             [required]
```

## Tipping

KSM address

```text
HtSKUKWRPCxCtzsnNfdbN1NN5uVq4yMizb2FqeHSC3YoRTi
```
