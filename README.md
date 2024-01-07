# Blockchain_with_Python
This repository contains a implementation of a blockchain in Python. Also includes a Flask web application to interact with the blockchain

## Features

- **Blockchain Initialization**: Creation of a genesis block and basic blockchain structure.
- **Adding New Blocks**: Functionality to add new blocks with proof of work.
- **Proof of Work Algorithm**: Implementation of a proof of work algorithm to secure the blockchain.
- **Blockchain Validation**: Method to validate the integrity of the entire blockchain.
- **Web Interface**: Flask web application to mine new blocks, view the blockchain, and check its validity.

## How to Run

1. Install Flask: `pip install Flask==0.12.2`
2. Run the script: `python blockchain.py`
3. Access the web application at `http://localhost:5000`.

## Endpoints

- `/mine_block`: Mines a new block.
- `/get_chain`: Returns the current blockchain.
- `/is_valid`: Checks if the blockchain is valid.

