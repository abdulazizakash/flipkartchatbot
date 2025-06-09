# Flipkart Chat Bot 

## If you don't have anaconda download from here
```bash 
https://www.anaconda.com/download/success 
```
## Create a Conda environment:

```bash
conda create -p <env_name> python=3.10 -y
```
## Activate your conda environment

```bash
conda activate <env_path>
```
- If activating on bash terminal use this command:

```bash
source activate ./<env_name> 
```
ELSE
```bash
conda activate <env_path>
```

## Create a requirement.txt file and install it

```bash
pip install -r requirements.txt
```
## Create a .env file for keeping your environment variable.
- GROQ_API_KEY = ["add the your api key"](https://console.groq.com)
- ASTRA_DB_API_ENDPOINT = ["add the your api key"](https://console.groq.com)
- ASTRA_DB_APPLICATION_TOKEN = ["add the your api key"](https://console.groq.com)
- ASTRA_DB_KEYSPACE = "default_keyspace"
- HF_TOKEN = ["add the your api key"](https://huggingface.co/settings/tokens)


## Use setup.py for installing your local package.

- <either mention -e . inside your requirements.txt Or run python setup.py install >

