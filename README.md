# Polygon-Figment-io
My jottings
 Ethers.js
 Getting a provider
 const provider = new ethers.providers.Web3provider(window.ethereum)
 
 const address = provider.selectedAddress choosing an address
 const balance = provider.getBalance(address)  to get balance of an address
 formatting balance ethers.utils.formatUnits(balance, 18)
 request account:  await provider.send('eth_requestAccounts', []);
next add Polygon Mumbai to metamask with config :

Network Name: Polygon Mumbai
New RPC URL: https://rpc-mumbai.maticvigil.com/
Chain ID: 80001
Currency Symbol: MATIC
Block Explorer URL : https://mumbai.polygonscan.com


then signup on https://datahub.figment.io/ for API keys
