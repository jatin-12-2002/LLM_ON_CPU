# LLM_ON_CPU

## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main

## And Copy the Llama2 model into the 'model' Folder

## How to run?

### Step 1- Create a conda environment after opening the repository

```bash
conda create -p env python=3.10 -y
```
### Step 2- Activate the environment

```bash
conda activate ./env
```

### Step 3 - Install the requirements
```bash
pip install -r requirements.txt
```
### Step 4 - Run the application
```bash
python run_local.py
```