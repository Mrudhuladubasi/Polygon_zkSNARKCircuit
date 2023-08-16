# Polygon_zkSNARKCircuit
Designing a new zkSNARK circuit in Polygon that implements some logical operations. Also implementing the circuit and deploying a verifier on-chain to verify proofs generated from this circuit For this project, you will create a circuit using the circom programming language.

## Requirements 
* Node.js
* Circom (npm install -g circom) 
* SnarkJS (npm install -g snarkjs)
* Polygon Network (for on-chain deployment)

## Description
Create a circuit using the circom programming language that implements the following logical gate:

<img width="592" alt="image" src="https://github.com/s0HaNp/PolygonModule3/assets/95775561/e15a0cee-4fff-4571-8a63-8db8defcb4d8">

## Usage
1. Clone this project.
2. Install the necessary packages and type `npm i` in the terminal.
3. Open circom file and make the changes to implement the above logic gate.
5. Configure the hardhat.config.ts to deploy it in the Mumbai testnet.
6. Add the mumbai public rpc according to your choice and private key prior.
7. The account you add should have the test matics to deploy, which can be requested from the website:https://mumbaifaucet.com/
9. Back in the terminal, run the command `npx hardhat circom`.
10. In order to deploy the contract, run npx hardhat run scripts/deploy.ts --network mumbai.

## Verifier Deployment
The verifier contract needs to be deployed on the Polygon network. You can use tools like Hardhat or Truffle to deploy the contract. The verifier contract will include the verifying key and logic to verify proofs on-chain.
    
## Output
A contract address where it is deployed is produced and "verifier result: true" is shown on the terminal.

## Authors

Mrudhula Dubasi
21BCS4636
mrudhuladubasi@gmail.com

## License

This project is licensed under the [GNU General Public License v3.0] License - see the LICENSE file for details
