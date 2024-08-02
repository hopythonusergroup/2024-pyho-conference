# 2024 PyHo  Community Conference Website

## Contributing

1. Fork a copy of the repository

2. Clone your forked repo locally via the terminal, replacing the username in the URL with your own (note: not all operating systems will use a **$** as a terminal prompt).

    ```
    https://github.com/<your-username-here>/2024.PyHo.Conference.git
    ```

3. Change directory into the folder

    ```
    cd 2024.PyHo.Conference
    ```

4. Verify that you are on the develop branch

    ```
    git branch
    ```

5. Create a virtual environment

    ```
    python -m venv myvenv
    ```

6. Activate virtual environment

    ```
    source myvenv/bin/activate
    ```

7. Pip install requirements

    ```
    pip install -r requirements.txt
    ```

8. Run dev server

    ```
    mkdocs serve
    ```

## Pushing your code to GitHub

After you have made your changes, you will need to push the local files with the changes back to GitHub in order to submit a pull request. Assuming you are still on the develop branch, you will be pushing your changes from the local develop branch to the develop branch of the forked repo at your GitHub account.

    ```
    git add .
    git commit -m "Your commit message"
    git push origin develop
    ```
