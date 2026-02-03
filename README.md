EVM Smart Contract ProjectA comprehensive development framework for deploying and testing Solidity smart contracts on the Ethereum Virtual Machine (EVM). This project utilizes Hardhat for compilation, testing, and deployment orchestration.🛠 FeaturesAutomated Testing: Robust test suite using Mocha and Chai.Gas Reporting: Built-in hardhat-gas-reporter to optimize contract efficiency.Deployment Scripts: Streamlined JS/TS scripts for multi-network deployment.Security Built-in: Configuration ready for Etherscan verification and Slither analysis.🚀 Getting Started1. InstallationClone the repository and install dependencies using your preferred package manager:Bashnpm install
# or

yarn install
2. Environment SetupCreate a .env file in the root directory to manage your private keys and RPC endpoints:PlaintextPRIVATE_KEY=0x...
INFURA_API_KEY=your_key
ETHERSCAN_API_KEY=your_key

💻 Development WorkflowUse the following commands to interact with the development environment:TaskCommandDescriptionCompilenpx hardhat compileCompiles Solidity files and generates artifacts.Testnpx hardhat testRuns the full test suite.Gas ReportREPORT_GAS=true npx hardhat testRuns tests and outputs a gas usage table.Local Nodenpx hardhat nodeStarts a local JSON-RPC network for debugging.Deploynpx hardhat run scripts/deploy.jsDeploys the contract to the default/local network.🧪 Testing & DebuggingThe project uses Hardhat Network, a local Ethereum network designed for development. It allows you to:Use console.log() directly inside Solidity contracts.Simulate different network states and account balances.Debug failing transactions with detailed stack traces.📜 LicenseThis project is licensed under the MIT License.
