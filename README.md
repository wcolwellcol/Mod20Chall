# Mod20Chall
This is a project in which I create a smart contract with permissions for two specified accounts to withdraw from the contract. It is essentially a shared wallet, which you could imagine could be useful for a married couple, for instance. I utilized the [remix IDE](https://remix.ethereum.org/) for this project and wrote in solidity and used pragme 0.5.0.

## Technologies
Remix IDE

## Installation
To recreate this project, one merely needs to fire up the remix IDE online.

## Usage

### Code
Code is found in the [joint_savings.sol](https://github.com/wcolwellcol/Mod20Chall/blob/main/joint_savings.sol) file. Therein, the contract JointSavings is created with withdraw, deposit, and setAccounts functions. These allow you to specify the accounts that can interact with the contract, then these accounts can withdraw and deposit.

### Run the Code
To run the code, make sure that you compile the code with the proper compiler, and deploy in any of the Remix VM environments offered. After deploying, expand the "Deployed Contracts" section and use the buttons and value fields to accomplish your goals.

## Contributors

This code was written by me, but the framework was provided by the Columbia Fintech Bootcamp

## License

MIT License

Copyright (c) [2023] [willcolwell]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
