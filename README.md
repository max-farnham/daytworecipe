# 1) Create a new repository
1) Go to Github and press New repository
2) Name the repo and initialize it with a readme
3) Create the repo

# 2) Create a Codespace
1) In the repo, click Code --> Codespaces --> Create codespace on main

# 3) Open Codespace
Option 1: 
1) Open VS Code locally
2) Install the GitHub Codespaces extension
3) Connect to the new codespace
4) Sign into your GitHub account
5) Select the repo you created

Option 2 (option I selected as my VS Code wasn't working locally):
1) Open GitHub in your browser
2) Navigate to Codespaces
3) Select the codespace you just created

# 4) Create .py File
1) Create a new .py file
2) Write `# %%` to make it interactive (make sure Python and Jupyter are installed)

# 5) Create and Activate a Virtual Environment
1) Open a bash terminal
2) Write `python3 -m venv venv` to create the virtual environment
3) Write `source venv/bin/activate` to activate it (your terminal path should now show `(venv)` to confirm that it is activated)

# 6) Create requirements.txt file and install required packages
1) In your terminal, write `touch requirements.txt` to create the file
2) Install plotly with `pip install plotly`
3) Check the version you installed `pip show plotly`
4) Freeze dependences into requirements.txt with `pip freeze > requirements.txt`

# 7) Commit and Push to GitHub
1) Check changes with `git status`
2) Stage files with `git add .`
3) Commit changes with `git commit -m "Create new project"`
4) Push changes with `git push`
