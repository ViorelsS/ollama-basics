# Ollama Basics

Ollama Basics is a simple Node.js application that uses the `ollama` library to interact with AI models and provides a REST API for querying them.

## Prerequisites

-   Ensure that `ollama` is installed on your computer. You can find installation instructions in the [ollama website](https://ollama.com/).

## Features

-   Query AI models using the `ollama` library.
-   Simple REST API built with Express.js.
-   Supports dynamic questions via query parameters.

## Installation

1. Clone the repository:

    ```bash
    git clone <repository-url>
    cd ollama-basics
    ```

2. Install dependencies:
    ```bash
    bun install
    ```

## Usage

1. Start the server:

    ```bash
    bun start
    ```

2. Open your browser or use a tool like curl or Postman to send a GET request to the server:
   `http://localhost:3000/?question=Your+question+here`

3. If no question is provided, the server will respond with a message prompting you to use the ?question= parameter.

## Dependencies

-   [ollama](https://www.npmjs.com/package/ollama): Library for interacting with AI models.
-   [express](https://expressjs.com/): Web framework for building REST APIs.

## License

This project is licensed under the MIT License.
