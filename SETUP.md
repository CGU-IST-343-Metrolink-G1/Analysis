# Setup

## Setup Environment

Create Virtual Environment<br>
`python -m venv venv`<br>

Activate Virtual Environment<br>
*Windows*<br>
`.\venv\Scripts\Activate`<br>
*macOS / Linux*<br>
`source venv/bin/activate`<br>

Install Dependencies<br>
`pip install -r requirements.txt`<br>

Use Virtual Environment in JupyterLab<br>
`python -m ipykernel install --user --name=venv --display-name "Python (venv)"`<br>

## Update Requirements

Update requirements.txt with Installed Packages<br>
`pip freeze > requirements.txt`<br>

## Setup Github Repository

Clone Repo<br>
`git clone https://github.com/CGU-IST-343-Metrolink-G1/Analysis.git`<br>

Move to Repo Directory<br>
`cd Analysis`<br>

Set Display Name for This Repo<br>
`git config user.name "<name>"`<br>

Switch to Your Branch<br>
`git switch <branch>`<br>

Update Your Branch from Main<br>
`git pull origin main`<br>

## Choose IDE

### Launch VS Code

Open Project Folder in VS Code<br>

Select Kernel<br>
Open a `.ipynb` file → Click **Select Kernel** (top right) → Choose **venv (...)**<br>

### Launch Jupyter Lab

Launch JupyterLab<br>
`jupyter lab`<br>

### Launch Google Colab (Local Runtime)

Start Local Jupyter Server<br>
`jupyter notebook --NotebookApp.allow_origin='https://colab.research.google.com' --port=8888 --NotebookApp.port_retries=0`<br>

Copy Token URL from Terminal Output<br>
`http://localhost:8888/tree?token=...`<br>

Connect in Colab<br>
**Click Connect Dropdown** (top right) → **Connect to a Local Runtime** → **Paste Token URL**<br>

## Github Updating

Stage Changes<br>
`git add <file>`<br>

Commit Changes<br>
`git commit -m "<message>"`<br>

Push to Your Branch<br>
`git push`<br>

Merge into Main<br>
Open the repo on GitHub → **Pull Requests** → **New Pull Request** → Set base to **main** and compare to **your branch** → **Create Pull Request**<br>