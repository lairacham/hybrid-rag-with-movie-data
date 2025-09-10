# Hybrid RAG with Movie Data
This project uses RAG to improve a response from an LLM using a vector DB and a graph DB. The data comes from [this source](https://www.cs.cmu.edu/~ark/personas/).

## Requirements
Create a virtual environment.
```
conda create -n env python=3.13
```

Activate the virtual environment.
```
conda activate env
```

Install the requirements.
```
pip install -r requirements.txt
```

Run the notebook.
```
jupyter notebook
```

## How to run
- Get the data from the [Google Drive link](https://drive.google.com/drive/folders/1Jhy5TN9MK_qbtJ86T35XP5udYu7O4jYL?usp=sharing) and paste it in the `data` folder.
- Create a Zilliz and OpenAI account. Set up your `.env` like in the `.env.example`.
- Run all the cells in the notebook.
