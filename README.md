# CREATING-ERC20-TOKEN
### Make an account on any cryptocurrency wallet, such as Metamask, Coinbase, or another.
### A Solidity contract that implements the ERC20 token standard is required to create an ERC20 token. The attributes of the token, including the total quantity, symbol, name, decimals, and token balances for each address, are specified in this contract.
### At this point, you have the option of coding or utilising pre-existing tools like 20Lab, Kaleido, etc. This is what I used https://20lab.app to make my ERC-20 token. Once you provide your options, your contract will be created and used.
### Gas price is charged to publish your token. Mine erc20 in advance (I mined GoerliETH testnet).
### NOW CHECK THE ERC20 TOKEN ON https://etherscan.io/
![image](https://github.com/Prashant-0809/HYPERLEDGER_FABRIC/assets/121038235/3bc0617d-1a5a-49d0-912a-dc82612096aa)
Careful planning, coding, and consideration of security best practices are required while developing an ERC20 coin. Understanding the consequences as well as the requirements of the Ethereum network and the ERC20 standard is crucial.
# INSTALLATION OF HYPERLEDGER FABRIC IN UBUNTU 
We'll use the Fabric-samples repository to launch the first Hyperledger Fabric network. For understanding and utilising the basis of Fabric, this repository contains Fabric Docker Images and CLI tool binaries. Installing the following dependencies is mandatory before starting the project:
### 1. INSTALL DOCKER 
sudo apt-get -y install docker-compose 
### 2. INSTALL GOLANG-GO
sudo apt install golang-go

### 3. INSTALL JQ
(jq is like sed for JSON data )
sudo apt install jq

### 4. Install Node/java
sudo apt install npm
npm install node
### 5. INSTALLING FABRIC-SAMPLES REPOSITORY
curl -sSLO https://raw.githubusercontent.com/hyperledger/fabric/main/scripts/install-fabric.sh && chmod +x install-fabric.sh
#### Then you can pull docker containers by running one of these commands:
##### ./install-fabric.sh docker samples
##### ./install-fabric.sh d s
#### To install binaries for Fabric samples you can use the command below:
./install-fabric.sh binary
# Building First N etwork
### 1. Navigate through the Fabric-samples folder and then through the Test network folder where you can find script files using these we can run our network.

#### cd fabric-samples/test-network
### 2. We would be running ./network.sh down command to remove any previous network containers or artifacts that still exist.

#### ./network.sh down
### 3. We can bring up a network using the following command. This command creates a fabric network that consists of two peer nodes and one ordering node

 #### ./network.sh up
# Now our first Hyperledger Fabric Network is successfully running.
















