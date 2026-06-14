# Local Environment Setup

This section prepares the local Python environment used to run the notebooks later in the walkthrough.

The Azure resources are created in the earlier sections, but the notebooks need a local virtual environment, dependencies, environment variables, Azure CLI authentication, and a Jupyter kernel.

## Step 4.1 — Clone or open the project folder

* Clone the repository locally if you have not already.
* Open a terminal in the project root folder.
* Confirm that the expected project files are present.

```
pwd
ls
```

Expected files and folders include:

```
requirements.txt
.env.example
synthetic_data/
walkthrough/
```

## Step 4.2 — Create and activate a virtual environment

* Create a Python virtual environment.

```
python -m venv .venv
```

* Activate the virtual environment.

```
source .venv/bin/activate
```

## Step 4.3 — Install project dependencies

* Upgrade pip.

```
python -m pip install --upgrade pip
```

* Install the required packages.

```
python -m pip install -r requirements.txt
```


## Step 4.4 — Create the local environment file

* Copy the example environment file.

```
cp .env.example .env
```

* Open the local `.env` file with your preferred editor.

```
vim .env
```

The `.env` file should contain the same variable names as `.env.example`:

```
AIPROJECT_ENDPOINT=
CHAT_MODEL=
AZURE_AI_SEARCH_INDEX=
```

Fill these values after the matching Azure resources have been created:

```
AIPROJECT_ENDPOINT=<Azure AI Foundry project endpoint>
CHAT_MODEL=<chat model deployment name>
AZURE_AI_SEARCH_INDEX=<Azure AI Search index name>
```

## Step 4.5 — Sign in with Azure CLI

* Check whether Azure CLI already has an active account.

```
az account show
```

* If no account is active, sign in.

```
az login
```

* Confirm the active account again.

```
az account show
```

## Step 4.6 — Register the Jupyter kernel

* If the project virtual environment does not appear as a notebook kernel, register it manually.

```
python -m ipykernel install --user --name "$(basename "$PWD")" --display-name "Python ($(basename "$PWD"))"
```

* Confirm that the kernel is available.

```
jupyter kernelspec list
```

When opening the notebooks, select the kernel that matches this project folder.

## Step 4.7 — Launch Jupyter Notebook

* Start Jupyter Notebook from the project root.

```
jupyter notebook
```

