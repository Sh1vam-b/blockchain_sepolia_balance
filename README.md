Sepolia ERC-20 Balance Checker
A minimal web dApp that reads the ERC-20 token balance of the connected MetaMask account on the Ethereum Sepolia testnet. Read-only – no transactions are sent.

Built for the course Aktuelle Themen der Informatik (Blockchain track) at FH Technikum Wien.

Features
Connects to MetaMask and uses the selected account
Checks that the wallet is on Sepolia (chain ID 11155111)
Calls the token contract's balanceOf, decimals and symbol via a minimal ABI
Formats the raw balance with ethers.formatUnits and shows it with the token symbol
Tech stack
HTML / JavaScript (single file, no build step)
ethers.js v6 (BrowserProvider, Contract)
MetaMask
How to run
Install MetaMask and switch to the Sepolia test network.
Open index.html in your browser (or serve it locally, e.g. npx serve .).
Click the button and approve the connection.
The token contract address is set at the top of the script (0xaFce…8188) – replace it to check a different token.

Related projects
blockchain_sepolia_checker – current block height
blockchain_sepolia_send – send ERC-20 tokens
