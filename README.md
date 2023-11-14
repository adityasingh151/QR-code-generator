# QR Code Generator

A Node.js script that utilizes the inquirer and qr-image packages to generate a QR code image from a user-entered URL and save both the QR code image and the URL in a text file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/qr-code-generator.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd qr-code-generator
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

## Usage

1. **Run the script:**

    ```bash
    node index.js
    ```

2. **Enter the URL:**

    You will be prompted to input a URL. Type in the desired URL and press Enter.

3. **Generate QR code:**

    The script will create a QR code image and save it as "qr_img.png" in the project directory.

4. **Save URL to a file:**

    The entered URL will be saved in a text file named "URL.txt."

## Dependencies

- [inquirer](https://www.npmjs.com/package/inquirer): A collection of common interactive command line user interfaces.
- [qr-image](https://www.npmjs.com/package/qr-image): QR Code generator for JavaScript.

    Install these dependencies using:

    ```bash
    npm install inquirer qr-image
    ```

## Contributing

Contributions are welcome! Feel free to open issues and pull requests. Please follow the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
