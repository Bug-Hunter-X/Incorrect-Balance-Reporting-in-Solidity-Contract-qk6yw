# Incorrect Balance Reporting in Solidity Contract

This repository demonstrates a common error in Solidity smart contracts: incorrect access to storage variables.

The `bug.sol` file contains a contract with a faulty `balanceOf` function that incorrectly accesses storage variables, resulting in an inaccurate balance calculation. The correct implementation can be found in `bugSolution.sol`.  This demonstrates the importance of careful attention to detail when working with storage variables in Solidity. 