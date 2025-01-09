# Zimperium zScan Plugins

Welcome to the official repository for **Zimperium zScan plugins**. Here, you'll find plugins designed to integrate Zimperium's powerful mobile app security scanning capabilities with popular CI/CD platforms, allowing you to seamlessly incorporate mobile app security checks into your development pipeline.

## Overview

Zimperium zScan helps you automate the security assessment of your mobile applications, detecting potential vulnerabilities and ensuring compliance with security standards. 

Our plugins are open source, providing flexibility and community-driven improvements to help you tailor integrations that meet your CI/CD needs. 
By using our plugins, you can integrate zScan directly into your CI/CD workflow, enabling continuous mobile app security testing across various stages of development.

## Available Plugins

Currently, we offer plugins for the following CI/CD platforms:

1. [**Jenkins**](https://github.com/Zimperium/zscan-plugin-jenkins): Integrate zScan directly into your Jenkins pipeline, enabling automated security scans for every build.
2. [**GoCD**](https://github.com/Zimperium/zscan-plugin-gocd): Add zScan as a step in your GoCD workflows to maintain mobile app security in every deployment.
3. [**Bitrise**](https://github.com/Zimperium/zscan-plugin-bitrise): Leverage zScan within Bitrise to automatically scan mobile applications during your CI/CD process.
4. [**Harness**](https://github.com/Zimperium/zscan-plugin-harness): Integrate zScan in Harness to ensure security compliance and manage vulnerabilities before each release.
5. [**GitHub Action**](https://github.com/marketplace/actions/zimperium-zscan): Configure zScan Workflow for your repository to enable automated scanning of changes made to the application.
6. [**GitLab**](https://github.com/Zimperium/zscan-plugin-gitlab): Add zScan to a GitLab Pipeline to enable automated scanning and vulnerability reporting as part of your CI/CD process.
7. [**TeamCity**](https://github.com/Zimperium/zscan-plugin-teamcity): Add zScan to a TeamCity Build Configuration enable automated scanning as part of your CI/CD process.

Each plugin includes detailed documentation and configuration options to get you up and running quickly.

## Getting Started

1. **Installation**: Check the README for each plugin for specific installation instructions tailored to each CI/CD platform.
2. **Configuration**: Both zScan and the plugin offer configuration options to customize scan settings, thresholds, and reporting.
3. **Usage**: Initiate scans as part of your CI/CD workflows and monitor the results directly within your platform.

## Documentation

To learn more about Zimperium zScan and its capabilities, visit the [Zimperium zScan](https://www.zimperium.com/zscan/) webpage or see the documentation provided within each plugin directory.

## Contributing

We welcome contributions from the community! Whether you want to add new features, improve existing code, or suggest new integrations.
New integrations can be requested by opening an issue in this repository. Plugin-specific contributions can be made by raising an issue or submitting a pull request to the respective plugin repository.

## License

Each plugin in this repository is licensed under the [MIT License](./LICENSE). You are free to use, modify, and distribute the code as permitted under the terms of the MIT License.
