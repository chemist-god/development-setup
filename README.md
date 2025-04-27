# Week 2 Lecture 1: Development Environment Setup

**Tutor:** Bratipah Kioko

## Assignment

### Part 1: 

- Difference Between Hardhat and Foundry Enviroments
  
| Feature                      | Hardhat                                                                 | Foundry                                                   |
|------------------------------|------------------------------------------------------------------------|----------------------------------------------------------|
| **When Building**            | Requires Node.js and npm/yarn for dependency management                | No external dependencies                                 |
| **When Compiling**           | Uses the `hardhat compile` command to compile contracts into ABI and bytecode | Uses the `forge build` command to compile contracts into ABI and bytecode |
| **When Deploying Smart Contracts** | Uses `hardhat deploy` or custom scripts for deployment                  | Uses `forge script` for deployment via Solidity scripts or CLI commands |


- Difference Between Local IDE (Visual Studio) and Remix for Smart Contract Development

| Feature                            | Local IDE (e.g., Visual Studio)                                   | Remix                                                     |
|------------------------------------|------------------------------------------------------------------|----------------------------------------------------------|
| **Setup Requirements**             | Requires installation and configuration of the IDE on your local machine | Browser-based; no installation required                  |
| **Environment Flexibility**        | Offers more flexibility to integrate third-party tools and extensions | Limited to what is supported within the Remix interface  |
| **Offline Support**                | You can use it offline, and your code will be safely stored                    | Requires internet connection to access Remix             |
| **Ease of Use for Beginners**      | Can be complex for beginners due to setup and configuration      | Beginner-friendly with an intuitive interface            |


