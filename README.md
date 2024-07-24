# Information-Retrieval-System with PaLM2

# How to run
### STEPS:

Clone the repository

```bash
Project repo: https://github.com
```

### STEP 1: Create a conda environment after opening the repository

```bash
conda create -n llmapp python=3.8 -y
```

```bash
conda activate llmapp
```

### STEP 2: Install the requirements

```bash
pip install -r requirements.txt
```

Create a .env file in the root directory and add your GOOGLE_API_KEY as shown below

```bash
GOOGLE_API_KEY = "XXXXXXXXXXXXXXXXX"
```

```bash
Finallly run the following command
streamlit run app.py
```
Now, 
```bash
open up: http://localhost:8501
```

Techstack Used:
Python
Streamlit
Langchain
PaLM2
FAISS
