# Polygon-Figment-io
My jottings
 Ethers.js
 Getting a provider
 const provider = new ethers.providers.Web3provider(window.ethereum)
 
 const address = provider.selectedAddress choosing an address
 const balance = provider.getBalance(address)  to get balance of an address
 formatting balance ethers.utils.formatUnits(balance, 18)
	
