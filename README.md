# Projeto - Langchain: Crie Agentes e RAGs com IA Generativa

Este repositório contém os materiais e notebooks desenvolvidos durante o curso **"Langchain: Crie Agentes e RAGs com IA Generativa"**.

## Estrutura do projeto

- `slides/`: Materiais de apoio em PDF.
- `langchain/`: Notebooks e fontes do curso em Python.

## Como Começar

1. Clone o repositório:
```bash
git clone https://github.com/dieLopes/cirso_langchain.git
```

2. Crie e ative um ambiente virtual:
```bash
python3.11 -m venv .venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate      # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Crie o arquivo `config.yaml` na pasta `langchain/` do projeto contendo as seguintes chaves:
```yaml
OPENAI_API_KEY: "sua-chave-openai"
PINECONE_API_KEY: "sua-chave-pinecone"
GOOGLE_API_KEY: "sua-chave-google"
```
