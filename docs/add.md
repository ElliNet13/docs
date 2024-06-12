Welcome to the documentation on how to contribute to GitHub repositories! Whether you're fixing a bug, adding a feature, or just improving the documentation, your contributions are welcome and appreciated.

## Getting Started

1. **Fork the Repository**: Click on the "Fork" button in the top-right corner of the repository's GitHub page to create a copy of the repository in your GitHub account.

2. **Clone the Repository**: Clone your forked repository to your local machine using the following command:
   ```bash
   git clone https://github.com/YourUsername/repository-name.git
   ```

3. **Make Changes**: Make the necessary changes to the code or documentation on your local machine.

4. **Commit Changes**: Commit your changes to your forked repository using Git:
   ```bash
   git add .
   git commit -m "Your commit message here"
   ```

5. **Push Changes**: Push your changes to your forked repository on GitHub:
   ```bash
   git push origin master
   ```

6. **Create a Pull Request**: Go to the original repository on GitHub and click on the "New Pull Request" button. Follow the instructions to create a pull request to merge your changes into the original repository.

## Adding Documentation

If you're adding or modifying documentation, you can contribute to the documentation in the `docs` folder of the repository. Follow these steps:

1. Create or Edit Documentation Files: Create or edit Markdown files (.md) in the `docs` folder to add or modify documentation.

2. Update `mkdocs.yml`: Open the `mkdocs.yml` file in the root of the repository and add the path to your documentation file under the `nav` section to make it appear in the navigation bar of the documentation website. For example:
   ```yaml
     - Page name: Markdown_file_name.md  # Add this line in nav
   ```

3. Commit and Push Changes: Commit your changes to repo and push them to your forked repository.

4. Create a Pull Request: Create a pull request to merge your documentation changes into the original repository.

That's it! Thank you for contributing to ElliNet13/docs.
