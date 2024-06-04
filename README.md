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
    
3. Generate a new project using this template (coping from Github):
    ```bash
    cookiecutter gh:Rsirp0c/hello-world-cookiecutter
    ```
    After running the command, you will enter values for the following variables (default values are in parentheses): 
    ```bash
    [1/4] project_name (Hello World): cookiecutter_demo
    [2/4] project_slug (cookiecutter_demo): 
    [3/4] author_name (Author's Name): hcheng
    [4/4] description (A simple coockiecutter demo project.):
    ```

4. Navigate to the newly created project directory:
    ```bash
    cd your_project_name
    ```

5. Push the updated repository:
    ```bash
    git add .
    git commit -m "commit after cookiecutter project creation"
    ```