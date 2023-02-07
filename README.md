# KeyLogger

A Python script that captures keystrokes and stores them in a text file.

## Table of Contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Functionality](#functionality)
- [Sending the Log File via Email](#sending-the-log-file-via-email)
- [Note](#note)
- [Contributions](#contributions)

## Requirements

- Python 3
- pynput library
- smtplib library (for sending the log file via email)

To install the pynput and smtplib library, run the following command in your terminal:

```terminal
pip install pynput smtplib
```


## Usage

1. Clone the repository: 

```terminal
git clone https://github.com/raghvmaheshwari/Keylogger.git
```
2. Run the script: 
```terminal
python keylogger.py
```

## Functionality

The script captures all the keystrokes made on the keyboard and stores them in a text file. If the keystroke is a backspace, enter, shift, space, or caps lock, a special string is written to the file instead of the key itself.

## Sending the Log File via Email

The script includes a `send_email` function that can be used to send the log file as an email attachment. To use this feature, you will need to provide your email address, password, and the recipient's email address in the `send_email` function. You will also need to make sure that less secure apps are enabled for your Google account if you are using Gmail.

## Note

Please note that keyloggers can be used maliciously and this script is intended for educational purposes only. Use at your own risk.

## Contributions

Contributions are welcome! If you have any suggestions or bug reports, please open an issue on GitHub. To contribute, follow these steps:

1. Fork the repository
2. Clone the forked repository to your local machine
3. Create a new branch for your changes
4. Make the changes and commit them
5. Push the changes to your forked repository
6. Create a pull request to the original repository

Thank you for considering a contribution to Keylogger!

