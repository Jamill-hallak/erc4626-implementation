# ERC-4626 Implementation with Unit Tests

This project implements the ERC-4626 Tokenized Vault Standard using Solidity. It includes comprehensive unit tests to verify the functionalities of the vault contract. 
The project uses Hardhat and TypeScript for the development and testing environment.

## Contracts

### MyERC4626Vault

A vault contract that implements the ERC-4626 standard. It allows for deposits, withdrawals, minting, and redeeming of shares in exchange for underlying assets.

### TestERC20

A simple ERC20 token contract used for testing purposes.

## Project Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Jamill-hallak/ERC-4626-implementation.git
   cd ERC-4626-implementation
   npm install
   Compile contracts:
   npx hardhat compile
   Run unit tests:
   npx hardhat test


# The unit tests cover various functionalities of the MyERC4626Vault contract, including deposits, withdrawals, minting, and redeeming of shares.
## Example Output
Below is a screenshot of the successful unit tests:
![Screenshot 2024-07-19 004841](https://github.com/user-attachments/assets/227c2c23-4068-43a3-857f-13f193b1d132)

## File Structure
* contracts/
   MyERC4626Vault.sol :  Implementation of the ERC-4626 vault.

   TestERC20.sol :  Simple ERC20 token for testing.
  
* test/
MyERC4626Vault.test.ts :  Unit tests for the vault contract.

## License
This project is licensed under the MIT License.
