# OnlyUps SDK and Keep3rs
OnlyUps Offchain SDK and API Codebase

### OnlyUps EARN - run your own keep3r: 

* Currently OnlyUps.xyz provides a rate-limited API endpoint serving essential params for matching Seaport orders - not required for clients running their own OpenSea API nodes
* matchOrders() is permissionless (fillable by any EOA or contract)
* matchOrders() requires an ABI (published in this repo) and two matchable OnlyUps orders in the OpenSea Seaport format
* stay tuned for upcoming keep3r+SDK release
