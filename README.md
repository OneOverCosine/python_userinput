# For the python_userinput task

## Task 1.0 - Creating a GitHub repo

1. In PyCharm (or VS Code, as that's what I'm using) open project in a folder named ``python_userinput``. This is going to be the same name as the repository
2. Create a README.md file and populate it.
3. Create a .gitignore file and add the names of the files you don't want added. For those using PyCharm, that would be the environment files in ``venv/`` and ``.idea``.
4. Now, create a new repository on Github, giving it the same name as the folder you're working in. For this example, that's ``python_userinput``. Leave all the tickboxes empty when you create it.
5. Following the steps shown in your new empty repository:  
    - Move to the command line (works in VS Code and PyCharm) use ``git init`` to initialise the directory.
    - Enter ``git status`` to check which files are going to be pushed to the repository. Make sure it's only README.md (and .gitignore).
    - Enter ``git add .`` - This adds all the files shown with the previous command to the files that are going to be commited.
    - Enter ``commit -m "Useful message about what files you're adding"``
    - Enter ``git branch -M main``
    - Enter ``git remote add origin git@github.com:github_name/repository_name.git``
    - Enter ``git push -u origin main`` to push the changes to the reposiory.
6. Go back to the GitHub repository and refresh the page. You should see your README.md and .gitignore files.

## Task 1.1 - User Input Task

