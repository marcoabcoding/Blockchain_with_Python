# Basic Blockchain Implementation with Flask

This repository contains a Python-based basic implementation of a blockchain, along with a Flask web application to interact with it.

## Features

- **Blockchain Implementation**: A `Blockchain` class that handles the creation and management of blocks.
- **Proof of Work Algorithm**: Includes a proof of work algorithm to secure the blockchain.
- **Blockchain Validation**: Functionality to check the integrity of the entire blockchain.
- **Flask Web Application**: A Flask app that allows users to mine new blocks, view the entire blockchain, and check its validity.

## How to Run

1. Ensure Python and Flask are installed on your system.
2. Clone the repository and navigate to the project directory.
3. Run `python blockchain.py` to start the Flask server.
4. Access the web application at `http://localhost:5000`.

## Endpoints

- `/mine_block`: Mines a new block in the blockchain.
- `/get_chain`: Returns the entire blockchain and its current length.
- `/is_valid`: Checks the validity of the blockchain.

## Getting Started

To get started with this project, clone the repository and ensure you have Python and Flask installed. Run the `blockchain.py` script to start the Flask server. You can interact with the blockchain through the defined endpoints using a web browser or tools like Postman.

## Educational Purpose

This project is intended for educational purposes to demonstrate the basic workings of blockchain technology and how it can be integrated with a web application using Flask.

## Requirements

- Python 3
- Flask 0.12.2 (`pip install Flask==0.12.2`)
