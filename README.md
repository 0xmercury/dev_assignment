# dev_assignment

### Problem statement for Python developer position.

There is a bit of reading material that the candidate needs to go through before actually getting to the coding part. 

- you must know answers to the questions like what is blockchain?, different types of blockchains, architecture of ethereum blockchain, what are the limitations of its arch?, what is the current solution of those limitations right now? Read about side-chains like arbitrum, optimism they'll answer your limitation questions somewhat.

- Read about what is REST, websocket, gRPC. What are their use-cases & their limitations?
- Read about arbitrum & optimism architecutre. How does sequencers, relayers works & communication with ethereum happens?
- And how does sync/async websocket works. what's the difference b/w them etc.
- After doing the above, you're expected to code in python for the following:
  
   Subscribe to the websocket feed to get the latest transactions from arbitrum & optimism sequencers either both of them i.e. optimism & arbitrum together or possibly two different scripts of Optimism and Arbitrum seperately. Show your txns in a log file.
   
   **Plus points for**: if possible try to make use of **async** code flow in your script and get both arb & optmism txns using the same script in async fashion. Code should be non-blocking in nature.
   
   
### Resources:

* https://ethereum.org/en/what-is-ethereum/
* https://www.youtube.com/watch?v=mcunD9S0P_s
* https://medium.com/loom-network/dappchains-scaling-ethereum-dapps-through-sidechains-f99e51fff447
* https://www.web3.university/article/sidechains-vs-layer2s
* https://arbitrum.io/
* https://www.optimism.io/
* https://docs.alchemy.com/reference/sdk-websockets-endpoints
* https://bbc.github.io/cloudfit-public-docs/asyncio/asyncio-part-1
