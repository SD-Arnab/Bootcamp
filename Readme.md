# Learning GitHub: Practice Repository

This repository is for practicing and learning GitHub commands. Below are the steps and commands used for cloning the project, creating branches, and pushing changes.

## Basic Git Commands

### 1. Cloning the Repository

- Clone the repository from GitHub:
    ```sh
    git clone https://github.com/yourusername/dummy-repository.git
    ```

- Navigate to the project directory:
    ```sh
    cd dummy-repository
    ```

- Open the project in your code editor:
    ```sh
    code .
    ```

### 2. Adding and Committing Changes

- Add your changes to the staging area:
    ```sh
    git add .
    ```

- Commit your changes with a message:
    ```sh
    git commit -m "message"
    ```

### 3. Pushing Changes

- Push your changes to the remote repository:
    ```sh
    git push
    ```

### 4. Branching

#### Creating a New Branch

- Create a new branch:
    ```sh
    git checkout -b test
    ```

- Push the new branch to the remote repository:
    ```sh
    git push --set-upstream origin test
    ```

#### Checking Out an Existing Branch

- Check out an existing branch:
    ```sh
    git checkout branch-name
    ```

#### Listing Branches

- List all branches:
    ```sh
    git branch
    ```

## Deployment

- Go to the repository settings.
- Navigate to the "Pages" section.
- Select the branch you want to deploy from.
- Deploy your project.

## Cloning a Project from GitHub to Local

- Clone the repository:
    ```sh
    git clone <repository-url>
    ```

## Additional Git Commands

- Initialize a new Git repository:
    ```sh
    git init
    ```

- Check the status of your files in the working directory and staging area:
    ```sh
    git status
    ```

- View the commit history:
    ```sh
    git log
    ```

## Additional Information

For more detailed instructions and information, please refer to the documentation provided in this repository.

## License

This project is licensed under the MIT License.
