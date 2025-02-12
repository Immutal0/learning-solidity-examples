# Ethereum Smart Contracts for Learning

This repository contains a collection of smart contract challenges designed to help you learn the fundamentals of Ethereum smart contract development. Each challenge provides a problem statement and a specific functionality that the smart contract should implement.

Before reviewing the solutions in the repository, try to implement the contract yourself to enhance your learning experience!

---

## Challenges

### 01 - `say_hello.sol`
- Set a greeting on contract creation, allowing the owner (creator) to change it.
- Implement a `sayHello` method to return the greeting to anyone who calls it.
- Return "Hello Daddy" specifically to the contract's creator.

### 02 - `balance_address_checker.sol`
- Return the contract's address.
- Return the contract owner's address.
- Return the sender's address.
- Return the contract's balance.
- If the caller is the owner, return the owner's balance.
- Return the sender's balance.

### 03 - `basic_random.sol`
- Generate a random number between 0 and 99.
- Ensure the computational cost is lower than the reward a miner would receive for mining a block.

### 04 - `lottery_10_users.sol`
- Limit the lottery to 10 users.
- Each user must pay 0.1 ether to enter the lottery.
- Each user can only enter once.
- The contract owner is allowed to participate.
- Once 10 users have entered, the winner is selected.
- The winner receives the entire pot.
- A new lottery starts after the winner is selected.

### 05 - `lottery_no_limit.sol`
- No limit on the number of users.
- Each user must pay 0.1 ether to enter.
- Users can enter multiple times.
- The contract owner can participate as well.
- The owner decides when to select a winner.
- The winner receives the entire prize pool.
- A new lottery begins once a winner is selected.

### 06 - `lottery_multiple_winners.sol`
- No limit on the number of users.
- Users join by paying 0.1 ether and picking a number between 1 and 100.
- The contract owner decides when to generate the random number.
- Users who select the winning number(s) will receive a share of the prize pool.
- The prize is distributed proportionally among all winners.

### 07 - `fundraising.sol`
- The fundraising contract has a target amount that must be reached.
- A time limit is set upon contract creation.
- Anyone can contribute any amount until the goal is reached or time expires.
- After the time limit expires:
  - If the goal was not met, contributors can withdraw their funds.
  - If the goal is met, the contract owner can withdraw the full amount.

### 08 - `basic_token.sol`
- An initial token supply is set upon contract creation.
- The contract creator receives the initial token supply.
- Tokens can be transferred to any address.
- Protection from overflow should be implemented.
- Users can check balances.

### 09 - `ERC20_token.sol`
- Implement an ERC-20 token based on the [EIP-20 specification](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md).

### 10 - `ERC20_usage.sol`
- Create your own ERC-20 token using the OpenZeppelin implementation.
- Inherit from `StandardToken`.
- Add custom functionality such as name, symbol, decimals, and initial supply.

### 11 - `ERC721_usage.sol`
- Create your own ERC-721 token using the OpenZeppelin implementation.
- Inherit from `ERC721Token`.
- Add custom name and symbol for your token.

---

## Contribution Guidelines

We encourage contributions to this repository! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Add your solution or new challenge to the appropriate directory.
   - For example, if you want to add another implementation for a basic token contract, add it to the `07_basic_token` directory.
3. Submit a pull request (PR).
4. I will review your submission and merge it.
5. Enjoy contributing to the project!

---

## How to Add a New Challenge

If you'd like to propose a new challenge, follow these steps:

1. Fork the repository.
2. Add a new challenge description in the `README.md`.
3. Add your solution as a new contract file in the appropriate directory.
4. Submit a pull request with your changes.

---

## Contact to me
- **Telegram**: [@Immutal0](https://t.me/Immutal0)
- **Twitter**: [@Immutal0](https://x.com/Immutal0)

If you like my repos give me start