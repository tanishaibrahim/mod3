#   Token Creation using Openzeppelin

In this repository , the solidity code is used to create a token using the openzeppelin ERC20 contract.

## Description 

A token called Solidity and symbol SOL is created and deployed on the local hardhat node. User can also mint, burn, transfer, allow and check the balance of the tokens.

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., create_token.sol). Copy and paste the following code into the file:

To deploy it on the hardhat network , try running the following commands 

```shell
npx hardhat init
npx hardhat compile
```
```shell
npx hardhat run scripts/deploy.js
```

## Authors

Tanisha Ibrahim

@tanishaassii@gmail.com

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
