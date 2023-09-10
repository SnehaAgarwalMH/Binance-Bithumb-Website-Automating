# Binance-Bithumb-Website-Testing
Automated Website Management with Java, Selenium, and Parallel Threading

# Automated Website Management

This repository contains scripts for automating website management tasks using Java, Selenium WebDriver, JavaScript, and parallel threading. The scripts enable the automated management of two popular websites, Binance and Bithumb, using Chrome and Edge browsers.

## Overview

These automation scripts perform the following tasks:

- **Manual Login**: Automate the login process by entering user credentials, handling OTP authentication, and initiating scheduled actions.

- **Scheduled Actions**: Execute actions on a predefined schedule, including navigating to specific tabs, starting screen recording, taking screenshots, and handling pagination.

- **Screen Recording**: Capture screen recordings for specific tasks, providing a visual record of website interactions.

- **Screenshot Capture**: Take screenshots at various points during the automation process, allowing for detailed examination of specific actions.

- **Pagination Handling**: Manage pagination on the Binance website, automatically clicking through multiple pages and capturing data.

## Technology Stack

This project leverages several technologies:

- **Java**: The core programming language used for scripting and automation.

- **Selenium WebDriver**: A powerful tool for automating web browsers, enabling interaction with web pages.

- **JavaScript**: Utilized for enhanced web interactions and dynamic page elements.

- **Parallel Threading**: Parallel threading is implemented to execute actions simultaneously in two browsers (Chrome and Edge).

## Usage

Follow these steps to use the scripts:

1. **Prerequisites**: Ensure you have the necessary dependencies installed (e.g., Java, Selenium WebDriver).

2. **Configuration**: Update the configuration files with your login credentials and other settings.

3. **Execution**: Run the main scripts to initiate the automation workflow.

4. **Screen Recordings**: Screen recordings will be saved to the specified directory.

5. **Screenshots**: Screenshots will be saved during script execution.

## Configuration

- `config-binance.properties` and `config-bithumb.properties`: Update these files with your respective website login credentials and other configuration settings.

## Dependencies

- Java
- Selenium WebDriver
- ...

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute the code.

## Contributing

Contributions to this project are welcome. Please follow our contribution guidelines for details on how to get involved.

---

**Disclaimer**: This project is intended for educational and personal use. Be aware of the terms of service of the websites you interact with and use this project responsibly.

For detailed information on the CI/CD process, refer to the [CI/CD Documentation](/docs/cicd-docs.md).

