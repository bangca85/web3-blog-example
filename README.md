# Sample project for learning Web3

This is project clone from https://github.com/dabit3/full-stack-web3. I have custom for run local for me. You can read from blog post to view detail.

## To run app:
1. Clone this project
    ```bash
    git clone git@github.com:bangca85/web3-blog-example.git
    ```
2. Prerequisites
- Node.js installed on your local machine
- MetaMask Chrome extension installed in your browser
3. Install the dependencies
     ```bash
        npm install
    ```
4. Run the local node
    ```bash 
        npx hardhat node
    ```
5. Add first account to metamask plugin on chrome
6. Deploy smart contract to localhost
    ```bash
        npx hardhat run scripts/deploy.js --network localhost
    ```
7. Start the app
    ```bash
       npm run build
       npm start
    ```
