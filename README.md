# Hello World Cookiecutter Template

This is a Cookiecutter template for a simple Hello World test.

## Usage

To create a new project using this template, follow these steps:

1. Though you can create a new repository starting from local end, it is simpler to **create a new repository on GitHub and clone it to your local machine**. <br>Once you did that, clone that empty repository to your local machine:
   ```bash
    git clone <git-repo-link>
    ```
    
2. Install Cookiecutter:
    ```bash
    pip install cookiecutter
    ```
    
3. Generate a new project using this template:
    ```bash
    cookiecutter gh:Rsirp0c/hello-world-cookiecutter
    ```

4. Navigate to the newly created project directory:
    ```bash
    cd your_project_name
    ```

5. Initialize a new Git repository:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    ```

6. Create a new repository on GitHub and push your project:
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
