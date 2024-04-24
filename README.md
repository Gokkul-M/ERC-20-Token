# ERC-20-Token
# Aim :
  To create and deploy the ERC-20.
# Procedure :
  1,Create a new project<br>
  2,Open your terminal or command-line application on your computer. In your terminal, create a new folder named Token20. To do that, run the mkdir Token20 command. I usually run this command inside a folder named Projects, where I store all my other development projects.
  3,Go to the Token20 folder (run cd Token20).
  4,To initialize a new project, run truffle init.
  5,Wait for your project to be initialized, and then open the project in Visual Studio Code.
  6,In your terminal, run npm init. That command displays a utility that walks you through the process of creating a package.json file, which describes the project and stores dependencies that are used in the project.
  7,Complete the steps in the utility to easily create a package.json file.
  8,Next, we want to integrate with the OpenZeppelin contracts library.
  9,To do that, in the terminal, run npm install @openzeppelin/contracts.
  10,The package was added as a dependency in the package.json file.
  11,A node_modules folder imported all the available contracts from OpenZeppelin, in the subfolder @openzeppelin/contracts.
  12,To begin, open the Token20 project in Visual Studio Code. When the project is open, in the Explorer, right-click the contracts folder, and then select New File. Save the file name as ERC20MinerReward.sol.
  13,Open the truffle-config.js file, and then search for the line solc.
  14,In the solc section, ensure that the version value is 0.8.11 or greater. This version number is required because the OpenZeppelin contracts specify the pragma directive as pragma solidity ^0.8.0;.
Save the file.
  15,In Visual Studio Code, select Terminal > New Terminal to open a terminal window.
  16,In the terminal, enter ganache-cli to start Ganache CLI. Information for about 10 accounts is generated for tests, followed by the account's private keys and other metadata about the development server. The last line tells you that ganache-cli is listening on 127.0.0.1:8545, the default port location, defined in your truffle-config.js file.
  17,Right-click in the terminal window, and then select New Terminal.
  18,In the new terminal window, enter truffle build.

# Result:
Thus,the ERC-20 token is created .
  



