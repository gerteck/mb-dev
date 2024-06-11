# Markbind Website Test Repository

This repository is created to test the usage of Markbind before contributing to the main open-source project. Markbind is a flexible and powerful site generator, and this repo serves as a sandbox for experimentation and learning.

## Introduction

This repository hosts a Markbind website intended for testing purposes. It allows users to explore Markbind's features and functionalities, enabling smooth contributions to the main repository.

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/en/) (version 10 or above)
- [npm](https://www.npmjs.com/) (version 6 or above)
- [Markbind CLI](https://markbind.org/cli/)

### Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/gerteck/mb-dev
    cd mb-dev
    ```

2. **Install Dependencies:**

    ```bash
    npm install
    ```

### Running the Project

1. **Serve the Markbind Site:**

    ```bash
    markbind serve -d
    ```

2. Open your browser and navigate to `http://localhost:8080` to see the website. (Or other ports if 8080 is used)

## Project Structure

The project structure follows the standard Markbind setup. Key directories and files include:

- `site/`: Contains the Markbind site source files.
- `_markbind/`: Markbind specific configurations and template files.
- `index.md`: The homepage content.
- `node_modules/`: Node.js dependencies.
- `package.json`: Project metadata and npm scripts.
- `README.md`: This file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
