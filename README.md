### Simple Node application to query and invoke the [Genome Data Sharing Blockchain](https://github.com/ma-rius/fabric-multihost-setup)
(Adapted from Hyperledger Fabric [fabcar tutorial](https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html))

To install the required packages, run

`npm install`

Before the first query of the blockchain, run 

`node enrollAdmin.js`

After the admin is enrolled, the blockchain can be queried and invoked: 

`node query.js` / `node invoke.js`

