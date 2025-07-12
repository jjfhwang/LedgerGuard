# LedgerGuard

## Description

LedgerGuard is a TypeScript library providing secure multi-party computation (MPC) protocols and cryptographic primitives. It aims to enable developers to build privacy-preserving applications by leveraging advanced cryptographic techniques. The library provides a robust and efficient implementation of essential MPC building blocks, enabling computations on sensitive data without revealing the data itself to any single party. LedgerGuard allows for a wide range of applications, including secure data aggregation, private machine learning, and anonymous voting systems. The focus is on providing a well-tested, auditable, and easy-to-use library suitable for integration into larger systems.

## Features

*   **Secure Arithmetic Computation:** Implements secure addition, subtraction, multiplication, and division protocols over finite fields, allowing computations on secret-shared data.
*   **Secret Sharing Schemes:** Provides Shamir's Secret Sharing and Additive Secret Sharing, enabling the distribution of sensitive data among multiple parties such that no single party can reconstruct the original data.
*   **Oblivious Transfer (OT):** Offers efficient OT protocols for transferring information securely between two parties, ensuring that the sender remains unaware of which information was received by the receiver.
*   **Cryptographic Primitives:** Includes implementations of fundamental cryptographic primitives such as Elliptic Curve Cryptography (ECC) and Hash functions, optimized for MPC applications.
*   **Modular Design:** The library is designed with a modular architecture, allowing developers to easily integrate specific components into their projects without requiring the entire codebase.

## Installation

To install LedgerGuard, you will need Node.js and npm (Node Package Manager) or yarn installed on your system.

1.  Clone the repository:

    `git clone https://github.com/your-username/LedgerGuard.git`

2.  Navigate to the project directory:

    `cd LedgerGuard`

3.  Install the dependencies using npm:

    `npm install`

    Or, using yarn:

    `yarn install`

4.  Build the project:

    `npm run build`

    Or, using yarn:

    `yarn build`

This will compile the TypeScript code into JavaScript and place the output in the `dist` directory.

## Usage

Here are some examples of how to use LedgerGuard in your TypeScript projects:

**Example 1: Additive Secret Sharing**



**Example 2: Secure Addition**



**Example 3: Shamir Secret Sharing**



These examples demonstrate basic usage of the library's features. Refer to the API documentation within the source code for more detailed information on available functions and options.

## Contributing

We welcome contributions to LedgerGuard! To contribute, please follow these guidelines:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Write clear, concise, and well-documented code.
4.  Include unit tests to ensure the correctness of your changes.
5.  Submit a pull request with a detailed description of your changes.

All contributions will be reviewed by the project maintainers. We appreciate your effort in making LedgerGuard better.

## License

LedgerGuard is licensed under the MIT License. See the `LICENSE` file for more information.