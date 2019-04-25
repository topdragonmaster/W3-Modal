# web3connect

A react component to connect to multiple wallets using web3 providers

## Preview

![preview](./images/preview.png)

## Example

```js
import Web3Connect from "web3connect";

<Web3Connect
  onConnect={(provider: any) => {
    console.log("[Web3Connect] onConnect", provider);
  }}
  onClose={() => {
    console.log("[Web3Connect] onClose");
  }}
/>;
```
