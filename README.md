# keyp-backend-challenge
A short challenge designed to take 1-2 hours for backend developer candidates 

## Goal: Build a transaction scheduler queue which can handle for delays, failed transactions, gas issues, and nonce errors. Demonstrate an understanding of ethers.js, API server design, databases, and transactions in web3. 

## Basic Outline:
- Deploy a JavaScript serverful or serverless backend-only application to a hosting provider such as Render.com or Vercel
- Upon hitting an endpoint (no arguments necessary), the server adds multiple new transactions to a queue. 10 at a time is a good goal. All transactions can be signed by the same wallet in the server. To build the queue/scheduler you can use any method or tool, i.e. your own solution, vercel's chron-job feature, or a 3rd party tool like https://taskless.io/, https://repeater.dev/, or https://quirrel.dev/
- Transactions are fully "processed" once they are confirmed on-chain
- Demonstrate that all transactions were processed successfully

## Deliverables: 
- A hosted server with at least one exposed endpoint
- A wallet which submits transactions on polygon network, just ask for some testing gas money if you need it :)
