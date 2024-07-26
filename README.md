# keyloggerextended
This repository contains an advanced keylogger designed for educational purposes. The keylogger

This repository contains an advanced keylogger designed for educational purposes. The keylogger includes a range of functionalities to gather comprehensive information from the target system. Key features include:

- **Basic Keylogging**: Captures all keystrokes made on the target system.
- **Email Functionality**: Periodically sends gathered data to a specified email address.
- **System Information Gathering**: Collects detailed information about the target computer, including OS details, hardware specifications, and network information.
- **Clipboard Monitoring**: Captures and logs the contents of the clipboard.
- **Audio Recording**: Records audio from the system's microphone.
- **Screenshot Capture**: Takes periodic screenshots of the target system's screen.
- **File Encryption**: Encrypts the gathered data files to ensure security during storage and transmission.

## Features

- **Keylogging**: Logs all keystrokes in real-time.
- **Email Reporting**: Configurable email reporting to send logs and captured data.
- **System Information**: Gathers information such as IP address, system specifications, and running processes.
- **Clipboard Content**: Monitors and logs clipboard content.
- **Microphone Recording**: Records audio inputs from the microphone.
- **Screenshots**: Takes regular screenshots and stores them securely.
- **Encryption**: Encrypts log files and screenshots to prevent unauthorized access.

## Usage

This project is intended for educational and research purposes only. Unauthorized use of this software to monitor individuals without their explicit permission is illegal and unethical. Always ensure you have proper authorization before deploying this software.

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/advanced-keylogger.git
    ```

2. Navigate to the project directory:
    ```
    cd advanced-keylogger
    ```

3. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```

4. Configure the email settings and other parameters in the `config.json` file.

5. Run the keylogger:
    ```
    python keylogger.py
    ```

For this project, install all of the following modules (name is exactly the name of the 
package)
- pywin32
- pynput
- scipy
- cryptography
- requests
- pillow
- sounddevice

## Contribution

Contributions are welcome! Please fork the repository and submit pull requests for any improvements or bug fixes.

## Disclaimer

This software is provided "as is" for educational purposes only. The author is not responsible for any misuse of this software. Use responsibly and ethically.
