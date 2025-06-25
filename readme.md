# QR Code Generator - IS601 Module 7

A Python application to generate QR codes from user input, created for the IS601 Web Systems Development course.

---

## QR Code for Github Repo:

![Github Repository](/qr_codes/QRCode_github.png "My QR Code Link")

## QR Code for Docker Image:

![Github Repository](/qr_codes/QRCode_docker.png "My QR Code Link")

---

## About The Project

This project is a simple command-line tool that allows a user to generate a QR code from a given URL or text input. The script will prompt the user for data, a filename, and then generate a corresponding QR code image and save it as a `.png` file.

### Built With

- [Python](https://www.python.org/)
- [qrcode](https://pypi.org/project/qrcode/)
- [Pillow](https://pypi.org/project/Pillow/)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Python 3 installed on your system.

- Python 3

### Installation & Usage

1.  **Clone the repo:**
    ```sh
    git clone [https://github.com/RoddyCodes/RPmodule7_is601.git](https://github.com/RoddyCodes/RPmodule7_is601.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd RPmodule7_is601
    ```
3.  **Create and activate a virtual environment:**

    ```sh
    # Create the virtual environment
    python3 -m venv venv

    # Activate it (on macOS/Linux)
    source venv/bin/activate

    # On Windows, use: venv\Scripts\activate
    ```

4.  **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```
5.  **Run the application:**
    ```sh
    python main.py
    ```
    The script will then prompt you to enter the data you want to encode and the desired filename for the QR code image.
