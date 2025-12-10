# QR Code Generator

A simple Node.js command-line application that takes a URL as input from the user, generates a QR code image for that URL, and saves the input text to a file.

## 🚀 Features

* **User Input:** Prompts the user to enter a URL via the command line.
* **QR Code Generation:** Converts the entered URL into a PNG image (`qr_img.png`).
* **File Logging:** Saves the user-entered URL into a text file (`message.txt`) for reference.

## 🛠️ Technologies Used

* **Node.js**: Runtime environment.
* **[Inquirer](https://www.npmjs.com/package/inquirer)**: Used for interactive command-line user interface.
* **[qr-image](https://www.npmjs.com/package/qr-image)**: Used to generate the QR code from the text.
* **fs (File System)**: Native Node.js module used to write files.

## 📦 Installation

1.  **Clone or download** this repository.
2.  Open your terminal and navigate to the project folder.
3.  Install the required dependencies using npm:

    ```bash
    npm install
    ```

## ▶️ How to Use

1.  Run the application using Node.js:

    ```bash
    node index.js
    ```

2.  When prompted, type the URL you want to convert:
    ```text
    ? Type your URL: [https://www.google.com](https://www.google.com)
    ```

3.  The program will generate two files in your project directory:
    * `qr_img.png`: The visual QR code of your URL.
    * `message.txt`: A text file containing the URL you entered.

## Cc Project Structure

* `index.js`: The main entry point containing the logic for prompts and file generation.
* `package.json`: Manages project metadata and dependencies.
* `qr_img.png`: The output image file (generated after running the script).
* `message.txt`: The output text file (generated after running the script).
