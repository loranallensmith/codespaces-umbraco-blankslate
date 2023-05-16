# Umbraco Blank Site Template

This repository serves as a GitHub Codespaces template for creating a blank Umbraco site. With this template, you can quickly set up a development environment for Umbraco projects using GitHub Codespaces.

## Getting Started

To get started with this template, follow these steps:

1. Click on the "Use this template" button at the top of the repository to create a new repository based on this template.
2. Clone the newly created repository to your local machine using Git or your preferred Git client.
3. Open the cloned repository in GitHub Codespaces by clicking on the "Open with Codespaces" button in the GitHub web interface.
4. GitHub Codespaces will provision a container environment for your project with all the necessary dependencies.
5. Once the Codespace is ready, you can start working on your Umbraco site using the provided development environment.

This template provides a basic structure for an Umbraco site. The configuration file for the Codespace is set up to automatically run `dotnet restore` and to trust the environment's HTTPS certificate when you create the Codespace.  You can change this behavior by updating the `postCreatCommand` value in the `.devcontainer/devcontainer.json` file.

## Umbraco Setup

To set up your Umbraco instance, follow these steps:

1. In the Codespaces environment, navigate to the project's root directory.
2. Run the following commands to build the solution:

```bash
dotnet build
```
3. Once the build is successful, run the following command to start up your server:

```bash
dotnet run
```

This will start the Umbraco installation wizard.

4. Follow the on-screen instructions to set up your Umbraco site, including database configuration, admin account creation, and other relevant settings.

## Contributing

If you want to contribute to this GitHub Codespaces template, you can do so by submitting a pull request. Contributions are welcome and encouraged!

## License

This template is licensed under the [MIT License](LICENSE). Feel free to modify and adapt it to suit your needs.

## Resources

For more information about Umbraco, refer to the following resources:

- [Umbraco Documentation](https://our.umbraco.com/documentation)
- [Umbraco Community](https://our.umbraco.com/community)

## Acknowledgments

This template was inspired by the Umbraco community and aims to provide a starting point for developing Umbraco sites using GitHub Codespaces.

Note: Parts of this README were generated using the help of AI.  If you notice errors or omissions, please help us fix it by opening an Issue or PR. 🤓