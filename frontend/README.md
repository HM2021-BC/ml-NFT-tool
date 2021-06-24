# NFT Frontend Component

Web app to facilitate in launching NFT to Ethereum network with the in-browser Metamask extension.

The target ETH network is determined by Metamask current connection.

## Installation

`npm i`

## Deployment

`pm2 start script_deploy.sh`

The frontend server is listenning at port `8080` (as specified in the `.env` file)

**Notice**

`pm2` tool needs to be installed (if not yet) with this cmd `npm i pm2 -g`

## Start With Development Mode

For development on localhost, please use the below command to start

`npm start`
