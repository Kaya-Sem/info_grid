# CasperLabs

[Casper Network](https://casperlabs.io/) is a blockchain protocol built from the ground up to remain true to core Web3 principles and adapt to the needs of our evolving world.

- Make sure you have a [wallet](./wallet_connector.md)
- Click on the **Casperlabs** tab

__Process__ :

![ ](./img/casper1.png)

- Enter an Application Name. It's used in generating a unique subdomain on one of the gateways on the network alongside your twin ID. Ex. ***cl98casp*.gent02.dev.grid.tf**

- Select a capacity package:
    - **Minimum**: {cpu: 1, memory: 1024 * 2, diskSize: 100 }
    - **Standard**: {cpu: 2, memory: 16384, diskSize: 500 }
    - **Recommended**: {cpu: 4, memory: 32768, diskSize: 100 }
    - Or choose a **Custom** plan
- Choose the network
   - `Public IPv4` flag gives the virtual machine a Public IPv4

- `Dedicated` flag to retrieve only dedeicated nodes 
- `Certified` flag to retrieve only certified nodes 
- Choose the location of the node
   - `Country`
   - `Farm Name`
- Choose the node to deploy on 
- `Custom Domain` flag lets the user to use a custom domain
- Choose a gateway node to deploy your Casperlab instance on.

After that is done you can see a list of all of your deployed instances

![ ](./img/casper4.png)

Click on ***Visit*** to go to the homepage of your Casperlabs instance! The node takes a long time in order for the RPC service to be ready so be patient!

![ ](./img/casper5.png)