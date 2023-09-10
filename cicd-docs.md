# Continuous Integration and Continuous Deployment (CI/CD)

This project uses GitHub Actions for continuous integration and continuous deployment (CI/CD). The CI/CD process automates testing and deployment tasks when code changes are pushed to the repository.

## Workflows
- `binance_testing.yml`: Defines the workflow for testing actions on the Binance website.
- `bithumb_testing.yml`: Defines the workflow for testing actions on the Bithumb website.

## Configuration
Each workflow is configured with specific steps to execute automated tests. You can customize these workflows to suit your project's requirements.

## Usage
To use the CI/CD workflows, ensure that your repository contains the required scripts and dependencies. GitHub Actions will automatically trigger workflows when code changes are pushed to the `main` branch.

## Documentation
For detailed information on setting up and customizing CI/CD workflows, refer to the [CI/CD Documentation](/docs/cicd-docs.md).

For details on using the automation testing scripts, check the [Testing Documentation](/docs/testing-docs.md).

## License
This CI/CD setup is part of the project and is also licensed under the MIT License.

## Contributing
Contributions to improve the CI/CD setup are welcome. Please follow our contribution guidelines for details on how to get involved.

# CI/CD Process

Our CI/CD (Continuous Integration/Continuous Deployment) process automates testing and deployment for this project. It ensures that changes are thoroughly tested before being deployed to production.

## Workflow

1. **Code Changes**: Whenever changes are pushed to the repository, whether through pull requests or direct commits, the CI/CD process is triggered.

2. **Automated Testing**: Automated tests are run to verify the stability and functionality of the code changes.

3. **Deployment**: If the tests pass successfully, the changes are deployed to the production environment.

## Benefits

- Ensures code quality and stability.
- Enables rapid and reliable deployment of new features and bug fixes.
- Provides a streamlined and automated development workflow.

## CI/CD Tools

Our CI/CD process is powered by GitHub Actions, which offers a flexible and customizable way to automate workflows. We use GitHub Actions to define our build, test, and deployment processes.

For detailed information on our CI/CD process and GitHub Actions configuration, please refer to the [CI/CD Documentation](/docs/cicd-docs.md).
