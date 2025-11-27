# Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS

# How to run?
### STEPS:

Clone the repository

```bash
project repo: https://github.com/mohdamaan9897/Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a .env file in the root directory and add your Pinecone & GROQ credentials as follows:
```bash
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxx"
GROQ_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxx"
```
```bash
#run the following command to store embeddings to pinecone
python store_index.py
```
```bash
# Finally run the following command
python app.py
```

#### Now,
```bash
open up localhost:
```

### Techstack used:
- python
- LangChain
- Flask
- GROQ
- Pinecone