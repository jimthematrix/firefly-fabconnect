# firefly-fabconnect
A reliable REST and websocket API to interact with a Fabric network and stream events.

## Architecture
### High Level Components
![high level architecture](/images/arch-1.jpg)

### Objects and Flows
![objects and flows architecture](/images/arch-2.png)
![kafkal handler architecture](/images/arch-3.png)


The component provides 3 high level sets of API endpoints:
- Client MSPs (aka the wallet): registering and enrolling identities to be used for signing transactions
- Transactions: submit transactions and query for transaction result/receipts
- Events: subscribe to events with regex based filter and stream to the client app via websocket

### License
This project is licensed under the Apache 2 License - see the [`LICENSE`](LICENSE) file for details.
