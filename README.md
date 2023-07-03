
# FUNCTION IMPLEMENTATION

This is a Solidity smart contract that demonstrates different error handling techniques using `assert`, `revert`, and `require` functions.

## License

This contract is using the MIT License.

## Prerequisites

- Solidity ^0.8.17

## Contract Details

ThIS contract Contains the following functions:

### `testAssert(uint num)`

- This function demonstrates the usage of the `assert` function.
- It takes a `num` parameter and checks if num is greater than x or not using the `assert` statement.
- If the condition fails, it triggers an "Internal error" and aborts the execution.

### `drivingAge(uint _age)`

- This function demonstrates the usage of the `require` function.
- It takes an `_age` paramenter.
- If the `_age` is less than 18 then it reverts the transaction with a custom error message is displayed "Age must be greater than or equal to 18"".
- If the condition is met, it returns 1.

### `minOrder(uint _i)`

- This function demonstrates the usage of the `revert` function.
- It takes an `_odr` parameter it stands for order.
- It first checks if `odr` is less than 5 or not.
- If the condition fails, it reverts the transaction with a custom error message "mininum order value is at least 5".
- If the condition is met, it returns the order value.

## Usage

1. Make sure you have Solidity ^0.8.17 installed.
2. Compile and deploy the `FUNCTION IMPLEMENTATION` contract to a supported Ethereum network.
3. Interact with the deployed contract by calling the available functions and providing the required parameters.

## Author

NAME: NILESH SHARMA.

EMAIL: nileshsharma5661@gmail.com.
