# Week 2 Lecture 1: Development Environment Setup

**Tutor:** Bratipah Kioko

## Assignment

### Part 1: Contrast Between Hardhat and Foundry Environments
| Feature                      | Hardhat                                                                 | Foundry                                                   |
|------------------------------|------------------------------------------------------------------------|----------------------------------------------------------|
| **When Building**            | Requires Node.js and npm/yarn for dependency management                | No external dependencies                                 |
| **When Compiling**           | Uses the `hardhat compile` command to compile contracts into ABI and bytecode | Uses the `forge build` command to compile contracts into ABI and bytecode |
| **When Deploying Smart Contracts** | Uses `hardhat deploy` or custom scripts for deployment                  | Uses `forge script` for deployment via Solidity scripts or CLI commands |
