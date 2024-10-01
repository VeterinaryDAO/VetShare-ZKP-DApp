# Tests

## Overview
This directory contains the test cases for the smart contracts and middleware contracts developed for the VetShare ZKP DApp. The tests ensure the functionality and security of the contracts, especially around Zero-Knowledge Proof (ZKP) and selective data disclosure.

## Structure
- **Unit Tests**: These are isolated tests for individual smart contracts. They check each contract's functionality in detail.
- **Integration Tests**: These tests ensure the correct interaction between the smart contracts and middleware, as well as the successful integration with the Midnight Network.
- **Security Tests**: Focused on ensuring the contracts are resistant to attacks such as reentrancy, overflow, and unauthorized data disclosure.

## Running the Tests
To run the tests:
1. Ensure the development environment is properly set up.
2. Use the following command to run all tests:
   ```bash
   npm test

## Planned Enhancements
- **Performance Benchmarks**: Add performance-related tests for contract efficiency, particularly around data encryption and selective disclosure with ZKP.
- **Advanced Security Tests**: Include fuzzing, formal verification, and additional vulnerability scans for enhanced security. Tests will ensure compliance with the security standards expected for the Midnight Network integration.

Contributions and feedback are welcome! Please use issues and pull requests for discussions.
