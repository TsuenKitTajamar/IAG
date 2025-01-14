# IAG Module - Modulo de IAG - Inteligencia Artificial Generativa
## Configuration
1.Install necessary libraries:
- Install `OpenAI` library in your python environment
```python
pip install openai
```
- Load standard helper libraries and set your typical OpenAI security credentials for the OpenAI Service that you've created
```python
pip install python-dotenv
```
- Create a `.env` file to save your Azure credentials where the following code will access to the `KEY` and `ENDPOINT`
```python
azure_endpoint = os.getenv("AZURE_OPENAI_ENDPOINT"), 
api_key=os.getenv("AZURE_OPENAI_API_KEY"), 
```

Your `.env` will be like the following sample:
```python
AZURE_OPENAI_ENDPOINT = "YOUR_AZURE_ENDPOINT" 
AZURE_OPENAI_API_KEY = "YOUR_AZURE_OPENAI_API_KEY"
```

## Exercises List
1. Exercise 1 -> https://github.com/tamasma/master-ia-tajamar/tree/main/preprocessing
2. Exercise 2 -> https://learn.microsoft.com/en-us/azure/ai-services/openai/chatgpt-quickstart?tabs=command-line%2Ckeyless%2Cjavascript-keyless%2Ctypescript-keyless%2Cpython-new&pivots=programming-language-python
3. Exercise 3 -> https://github.com/tamasma/master-ia-tajamar/blob/main/01_OpenAI_getting_started.ipynb