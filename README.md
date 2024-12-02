# MyToken - ERC20 Token Contract

This project is a Solidity smart contract that implements a basic ERC20 token called "MyToken" with the symbol "MTK". The contract includes the standard ERC20 functionality and additional features for minting, transferring, and burning tokens.

## Description

The MyToken contract is built using the OpenZeppelin library, providing a secure and community-tested implementation of the ERC20 token standard. The contract allows the owner to mint new tokens and users to transfer or burn their tokens. The basic functionality provided includes:

- **Minting**: The contract owner can mint new tokens to a specified address.
- **Transferring**: Token holders can transfer tokens to another address.
- **Burning**: Token holders can burn their own tokens, reducing their balance.

## Getting Started

### Prerequisites

Before deploying this contract, ensure that you have the following:

- **Solidity Compiler**: Version `^0.8.20` or higher
- **Remix IDE**: An online Solidity development environment (https://remix.ethereum.org)

### Executing the Program

1. Open Remix IDE (https://remix.ethereum.org).
2. Create a new Solidity file with a `.sol` extension (`MyToken.sol`).
3. Copy and paste the provided code into the file.
4. Compile the code using the "Solidity Compiler" tab.
   - Make sure the compiler version is set to `0.8.20` or higher.
5. Deploy the contract using the "Deploy & Run Transactions" tab in Remix.
   - Select the `MyToken` contract and click on "Deploy".
6. Once deployed, interact with the contract by calling functions like `mint` (only available to the owner), `transfer`, and `burn` (available to all users).

### Functions

1. **Minting Tokens**: Only the owner of the contract can mint new tokens. To mint tokens, use the `mint(address, uint256)` function.
2. **Transferring Tokens**: Token holders can transfer tokens to another address using the `transfer(address, uint256)` function.
3. **Burning Tokens**: Token holders can burn their own tokens by calling the `burn(uint256)` function in Remix.

## Authors

- Eimee Suzanne Marzan

## License

This project is licensed under the MIT License.

