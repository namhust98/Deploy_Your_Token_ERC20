# Deploy_Token_ERC20
---------------------------------
1. Create MetaMask Wallet and connect it to MetaMask Extension of Chrome: https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn
2. Go to https://remix.ethereum.org/, then delete all the files and folders you see in the project
3. Import 3 file of this project to Remix. You can change the name of `NamNguyenToken.sol` to the name that you want
4. Look in the menu on the left, select the second icon, then select the compiler version is 0.4.25
![image](https://user-images.githubusercontent.com/38404536/118002780-2860ac80-b372-11eb-8d58-c58a72b26af0.png)
5. Select the third icon in menu, then choose the Environment is `Injected Web3`. This action will automatically connect Remix to your registered MetaMask Wallet.

![image](https://user-images.githubusercontent.com/38404536/118003193-8e4d3400-b372-11eb-9b3e-4b767408fa5e.png)

6. Go back to the first icon in menu, select the `NamNguyenToken.sol` file, then press ctrl + S to compile (You do not need to pay attention to warnings)
7. Go to the third icon again, in `Contract` select `NamNguyenToken - NamNguyenToken.sol`, then click the arrow to the right of the `Deploy` box.

![image](https://user-images.githubusercontent.com/38404536/118003914-306d1c00-b373-11eb-83c7-8266478eaa71.png)

8. Fill in your Token's information in these boxes (name; symbol; number of decimal places after the comma; total number of Tokens). Example:

![image](https://user-images.githubusercontent.com/38404536/118004937-20097100-b374-11eb-9b5c-57e6da81be66.png)

It's a pity that you cannot choose the icon for the token via smart contract. You need to send mail to Ethereum according to the following instructions: https://ethereum.stackexchange.com/questions/31902/how-to-verify-token-after-etherscan-and-submit-icon/31908#31908
9. If you want to deploy on testnet before deploying on real network, at the MetaMask Wallet extension, on the top line, select `Ropsten Test Network`. If you are ready to deploy on real network then choose `Ethereum Mainnet`, this will cost you a fee when deploying the contract.
10. Make sure your wallet has enough funds before deploying the contract, either Mainnet or Testnet. On Testnet, you can get free ETH in https://faucet.ropsten.be/
11. Click `Transact`, you will see a dialog like this:

![image](https://user-images.githubusercontent.com/38404536/118005524-a9b93e80-b374-11eb-89ab-7a85245c7c20.png)

It tells you that you need to pay a small amount in order to deploy your contract. The more money you spend, the more likely your contract will be deployed.
12. Wait about 30 minutes, then check your token in https://ropsten.etherscan.io/ if you use Testnet and https://etherscan.io/ if you use Mainnet
