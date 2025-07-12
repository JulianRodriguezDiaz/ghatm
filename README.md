# ghatm - GitHub Actions Timeout Manager ⏳

![GitHub Actions](https://img.shields.io/badge/Actions-Timeout%20Manager-brightgreen.svg)
![Releases](https://img.shields.io/badge/Releases-latest-blue.svg)

Welcome to **ghatm**, a simple command-line tool designed to set timeout minutes for all GitHub Actions jobs in your workflows. This tool is perfect for developers looking to manage their CI/CD processes more effectively.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

GitHub Actions is a powerful feature that allows you to automate your software workflows. However, managing timeouts for jobs can become cumbersome, especially in larger projects. **ghatm** simplifies this process by allowing you to set timeout minutes for all jobs with a single command. 

You can download the latest release of **ghatm** from the [Releases section](https://github.com/JulianRodriguezDiaz/ghatm/releases). Simply download the appropriate file for your system and execute it to get started.

## Features

- **Easy to Use**: Set timeout minutes for all jobs in your workflows with one command.
- **Flexible**: Customize timeout settings according to your project needs.
- **Open Source**: Contribute to the project and help improve it for everyone.

## Installation

To install **ghatm**, follow these steps:

1. Visit the [Releases section](https://github.com/JulianRodriguezDiaz/ghatm/releases).
2. Download the appropriate file for your operating system.
3. Execute the file to install the tool.

Make sure you have the necessary permissions to run executables on your system.

## Usage

Using **ghatm** is straightforward. Here’s how you can set the timeout for your GitHub Actions jobs:

1. Open your terminal.
2. Navigate to your project directory.
3. Run the command:

   ```bash
   ghatm --timeout <minutes>
   ```

Replace `<minutes>` with the desired timeout value.

## Examples

Here are a few examples of how to use **ghatm** effectively:

### Example 1: Set a Timeout of 30 Minutes

To set a timeout of 30 minutes for all jobs, run:

```bash
ghatm --timeout 30
```

### Example 2: Set a Timeout of 60 Minutes

For a longer timeout, use:

```bash
ghatm --timeout 60
```

## Contributing

We welcome contributions to **ghatm**! If you want to help, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes.
4. Submit a pull request.

Please ensure your code adheres to the existing style and includes appropriate tests.

## License

**ghatm** is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out to the maintainer:

- **Julian Rodriguez Diaz**
- [GitHub Profile](https://github.com/JulianRodriguezDiaz)

Thank you for using **ghatm**! We hope it helps streamline your GitHub Actions workflows. Don't forget to check the [Releases section](https://github.com/JulianRodriguezDiaz/ghatm/releases) for the latest updates and features.