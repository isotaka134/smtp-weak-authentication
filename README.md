## SMTP Exploit Script for Weak Authentication

This repository contains a Python script designed to exploit weaknesses in SMTP authentication mechanisms. The script connects to an SMTP server, analyzes its authentication methods, and attempts to send a spoofed email if authentication is successful. It allows user input to dynamically set parameters such as the SMTP server, credentials, and email content.

## Features

1. **SMTP Server Connection:  Connects to a specified SMTP server and port.**

2. **Authentication Check: Analyzes the server’s authentication mechanisms, including whether it supports weak methods like AUTH LOGIN or AUTH PLAIN.**

3. **STARTTLS Support: Checks if the server supports STARTTLS and attempts to exploit its potential weaknesses.**

4. **Spoofed Email Sending: Sends a spoofed email if authentication is successful, which can be customized by the user.**

5. **User Input: Allows dynamic input for SMTP server details, credentials, and email content.**

## Prerequisites

**To use the script, you need**:

  * Python 3. x: Ensure you have Python 3. x installed on your system. You can download it from python.org.

  * Standard Library: The script uses Python’s built-in `smtplib` library, which is included in the Python standard library.

## Installation

1. Clone the Repository

  To get started, clone this repository to your local machine:
  ```bash
    git clone https://github.com/isotaka134/smtp-weak-authentication.git
  ```

2. Navigate to the Script Directory

  Change into the directory containing the script:
  ```bash
    cd smtp-weak-aythentication
  ```

## Usage

1. Run the Script

   Execute the script using Python. Open a terminal or command prompt and run:
   
  ```bash
    python smtp_exploit.py
  ```
2. Input Parameters

   The script will prompt you to enter the following details:

   * Target SMTP Server: The domain or IP address of the SMTP server you want to test (e.g., `smtp.example.com`).

   * Port: The port number to connect to the SMTP server. The default is 25, but you can specify other ports such as 465 or 587.

    * SMTP Username: The email address or username for SMTP authentication (e.g., `victim@domain.com`).

   * SMTP Password: The password for the SMTP account. Leave this blank if you want to test for weak passwords.

   * Timeout: The timeout period in seconds for the connection attempt (default is 10 seconds).

   * Spoofed Sender Email: The email address that will appear as the sender in the spoofed email.

   * Recipient Email: The target email address that will receive the spoofed email.
   * Email Subject: The subject line of the spoofed email.

   * Email Body: The content of the spoofed email.

3. Review Results

   The script will provide output indicating:

   * The connection status to the SMTP server.

   * Whether authentication was successful.

   * Details of any supported authentication methods.

   * The success or failure of sending the spoofed email.

## Security and Ethical Considerations

  * Ethical Use: This script should only be used in environments where you have explicit permission to test. Unauthorized use against systems you do not own or have not been permitted to test is illegal and unethical.
  
  * Testing Environment: Use this script in a controlled environment or with permission from the system owner. Testing should be performed securely and legally.
  
  * Privacy: Respect privacy and data security. Avoid using this script to harm individuals or organizations.

## Disclaimer

This script is provided for educational and research purposes only. The author is not responsible for any misuse or illegal activities resulting from the use of this script. Use it at your own risk and ensure compliance with all applicable laws and regulations.

## Contact
For questions or support, please contact 
```bash
 contact@isotakanobomaro.work.gd
