# Continuous Intelligence and Interactive Analytics - Initial App

- Interactive app: [cintel-02-app](https://denisecase.shinyapps.io/cintel-02-app/)
- Repository: [cintel-02-app](https://github.com/denisecase/cintel-02-app)
- Author: [Denise Case](https://github.com/denisecase)

Purpose: Create an interactive analytics dashboard using Shiny for Python.

## Before

1. Join GitHub
2. Install Git
3. Configure Git with user.name and user.email
4. Install current Python. Important: Add Python to PATH during installation
5. Install VS Code Editor
6. Install VS Code Extension: [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
7. Install VS Code Extension: [Shiny](https://marketplace.visualstudio.com/items?itemName=posit.shiny-python)

Add the following extension now - or just add the json file later and VS Code will prompt you to install.

1. Install VS Code Extension: [Pyright](https://marketplace.visualstudio.com/items?itemName=ms-pyright.pyright)

## Shiny Hosting

1. Sign up for a free account on shinyapps.io. You can sign in via GitHub for convenience.

## Browser: Start a new GitHub Project with Default Files

1. Open browser and log in to GitHub
2. Create a new repo (e.g. cintel-02-app) with Default **README.md** and **.gitignore** (for Python).

## Local Machine: Clone repo to your Documents folder

1. Open VS Code.
2. Clone GitHub repo into Documents folder.

## Local Machine: Set Up Project Virtual Environment

Open your project folder in VS Code. Open a VS Code terminal (PowerShell or Bash or zsh) using Terminal / New Terminal.

1. Add file: pyrightconfig.json (see example in this repo).
2. Upgrade pip and install wheel.
3. Create local project virtual environment (just once at the beginning)
4. Activate the local project virtual environment (whenever you open a new terminal).
5. Install packages into active environment (once at the start and whenever you add new packages).
6. Freeze to requirements.txt (after adding or upgrading packages - see example in this repo).
7. Document your workflow and commands in your README.md.

Example Terminal Commands for Windows - record your process in your README.md:

```shell
py -m pip install --upgrade pip wheel
py -m venv .venv
.\.venv\Scripts\Activate.ps1
py -m pip install --upgrade -r requirements.txt
```

Example Terminal Commands for Mac/Linux - record your process in your README.nd:

```bash
python3 -m pip install --upgrade pip wheel
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade -r requirements.txt
```

## Create A Basic Shiny Express App

1. In VS Code with your project folder open, create a new file app.py in the root project folder.
2. See the example in this repo.

## Run the Shiny App

In the terminal window, run the app with the following command.
Note that the terminal will be busy running the app.
If you need to run any additional terminal commands, you'll have to open a new terminal window.

Choose one of the following commands.
The first command will not open a browser window.
The second command will open a browser window and continuously refresh based on changes to the app.py file.

```shell
shiny run app.py
shiny run --reload --launch-browser ./app.py
```

You should see the following output:

```shell
INFO:     Started server process [8112]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
```

## Open the Shiny App in Your Browser

Open your browser and go to [http://127.0.0.1:8000](http://127.0.0.1:8000)

## References

- [Shiny Express](https://shiny.posit.co/blog/posts/shiny-express/)
- [Shiny for Python - main](https://shiny.posit.co/py/)
- [Verify all installed packages with Python Package Index](https://pypi.org/)
- [Font Awesome free icons](https://fontawesome.com/search?m=free&o=r)
