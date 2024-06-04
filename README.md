# Hello World Cookiecutter Template

This is a Cookiecutter template for a simple Hello World project.

## Usage

To create a new project using this template, follow these steps:

1. Ensure you have Cookiecutter installed. If not, you can install it using pip:
    ```bash
    pip install cookiecutter
    ```

2. Generate a new project using this template:
    ```bash
    cookiecutter gh:yourusername/hello-world-cookiecutter
    ```

    Replace `yourusername` with your GitHub username.

3. Navigate to the newly created project directory:
    ```bash
    cd your_project_name
    ```

4. Initialize a new Git repository:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    ```

5. Create a new repository on GitHub and push your project:
    ```bash
    git remote add origin <https://github.com/yourusername/your_repository_name.git>
    git push -u origin main
    ```

## Template Variables

The following variables are available in this template:

- `project_name`: The name of the project.
- `project_slug`: The project name in a URL-friendly format.
- `author_name`: Your name.
- `email`: Your email address.
- `description`: A brief description of the project.

## Example

Here is an example of creating a project with this template:

```bash
cookiecutter gh:hcheng-chwy/hello-world-cookiecutter
