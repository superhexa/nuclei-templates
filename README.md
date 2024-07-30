# Nuclei Templates 

Welcome to the Nuclei Templates Repository! This repository contains a collection of Nuclei templates for various security testing purposes. Nuclei is a fast and flexible vulnerability scanner that helps automate the process of identifying vulnerabilities and security issues. I only publish the templates that I have personally created and tested.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Nuclei is an open-source vulnerability scanner that uses a template-based approach to detect various types of security issues. This repository aims to provide a comprehensive set of Nuclei templates that can be used to perform security assessments and vulnerability scans.

## Getting Started

To use the templates in this repository, follow these steps:

1. **Install Nuclei**: If you haven't already, install Nuclei by following the [official installation guide](https://nuclei.projectdiscovery.io/installation/).

2. **Clone the Repository**: Clone this repository to your local machine.
   ```bash
   git clone https://github.com/superhexa/nuclei-templates.git
   ```

3. **Update Templates**: Make sure you have the latest templates.
   ```bash
   nuclei -update-templates
   ```

4. **Run Templates**: Use the Nuclei command to scan using the templates from this repository.
   ```bash
   nuclei -t <templates_path>
   ```

## Contributing

Contributions to this repository are welcome! If you have a new template or improvements to existing ones, please follow these steps:

1. **Fork the Repository**: Create a fork of this repository to make changes.

2. **Create a Pull Request**: Submit a pull request with your changes. Please ensure your templates are well-documented and tested.
   
## License

This repository is licensed under the [MIT License](./LICENSE). See the [LICENSE](./LICENSE) file for more details.
