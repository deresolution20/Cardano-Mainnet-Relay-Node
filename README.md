# Cardano-Mainnet-Relay-Node

<h1>Bash script to build a Cardano Mainnet Relay Node</h1>

### [Cardano project](https://cardano.org/)
Cardano is a proof-of-stake blockchain platform: the first to be founded on peer-reviewed research and developed through evidence-based methods. It combines pioneering technologies to provide unparalleled security and sustainability to decentralized applications, systems, and societies

<h2>Description</h2>
Project consists of a simple Bash script that will run inside an Ubuntu VM and automatically deploy a Cardano Main net Relay Node.  These server nodes are responsible for communicating with other relays in the network and broadcasting blocks that are created by block producing server nodes.
For security purposes, block producing nodes are not directly connected to the network, and must only connect to its relay nodes.

![block node](https://user-images.githubusercontent.com/85902399/203392154-b13f2afa-2492-43c4-ac4b-065c568f35f3.png)

<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b> 
- <b>VMware Workstation 16 Player</b>
- <b>Ubuntu 22.04 desktop</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Ubuntu 22.04 LTS desktop

<h2>Program walk-through:</h2>

<p align="left">
- Copy script to Ubuntu desktop: <br/>
- open terminal in Ubuntu
- run sudo sh mainnet_relay.sh to start the script
  
<img width="480" alt="start script" src="https://user-images.githubusercontent.com/85902399/203393126-46acf16a-f4fd-4f44-8a28-4c63af76cbc4.png">

<br />
<br />
Script installing Haskell:  <br/>
  
<img width="1183" alt="installing haskell" src="https://user-images.githubusercontent.com/85902399/203393301-9639e78b-ef4f-49e6-a4d1-fd333f4f0d42.png">

<br />
<br />
Once the script is completed (approx: 2-3 hours depending on your VM setup) it will launch glive viewer <br/>
- gLive viewer gives a detailed overview of the node status
- once the node is live, it will need to download all the block data to catch up to the current block before it can start contributing to the network
-this process can take several hours to download
  
![glive](https://user-images.githubusercontent.com/85902399/203393819-8cfdacd6-5a7c-486d-82ad-d39512e5d2f6.png)

<br />
</p>
