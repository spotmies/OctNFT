# OctNFT Project README
![image](https://github.com/spotmies/OctNFT/assets/90003260/f687fef9-3f08-4844-be4b-cb57724b615b)

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Welcome to the OctNFT project! This README provides an overview of the project and guides you through the installation and usage of OctNFT. OctNFT is a project that utilizes Next.js, Ethereum, and other dependencies to create and manage non-fungible tokens (NFTs). 

## Installation
To install the project and its dependencies, follow the steps below:

1. Clone the repository to your local machine:
```bash
gh repo clone spotmies/OctNFT
```

2. Navigate to the project directory:
cd OctNFT

3. Install the required dependencies by running the following command:
```bash
npm install
```

This command will read the `package.json` file and install all the dependencies listed in the `"dependencies"` section.

## Usage
To use OctNFT, follow the steps below:

1. Make sure all dependencies are successfully installed.

2. Customize the project files to fit your specific requirements. Update the necessary configuration files, such as Ethereum network settings or any other environment-specific settings.

3. Start the development server:
```bash
npm run dev
```

This command will start the Next.js development server, allowing you to preview and make changes to the project. The server will automatically reload whenever you save any file.

4. Open your web browser and navigate to `http://localhost:3000` to see the running application.

5. You're now ready to use OctNFT!

Note: The provided scripts can also be used for building, starting, and linting the project. Refer to the [Scripts](#scripts) section for more details.

## Dependencies
The project relies on the following dependencies:

- buffer: A JavaScript buffer implementation.
- ethers: A library for interacting with Ethereum and Ethereum-like blockchains.
- keccak256: A library for calculating Keccak-256 cryptographic hash functions.
- merkletreejs: A library for constructing Merkle trees.
- next: A React framework for building server-side rendered applications.
- react: A JavaScript library for building user interfaces.
- react-dom: The entry point to the DOM and server renderers for React.
- react-ga: A library for Google Analytics integration with React applications.

## Scripts
The project includes the following predefined scripts:

- `dev`: Starts the Next.js development server.
- `build`: Builds the project for production.
- `start`: Starts the production server.
- `lint`: Lints the project using ESLint.

To execute a script, run the following command:
```bash
npm run <script-name>
```

## Contributing
Contributions to the OctNFT project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on the project's repository.

## License
This project is licensed under the `BSD 3-Clause License`. See the `LICENSE` file for more information
