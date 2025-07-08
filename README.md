# Deep Researcher - Alternativa OpenSource ao Deep Research

## 🎯 Sobre o Projeto

Este é um Agente simples construído em Python (usando Agno) capaz de substituir completamente Deep Research da OpenAI. 

Ele utiliza o módulo principal do Agno de criação de agentes, o Tavily para pesquisas e um prompt especificando como a pesquisa deve ser feita. Adapte-a conforme suas necessidades.

## 🚀 Como rodar o projeto?

```bash
# Entre no diretório
cd deep-researcher

# Crie um arquivo .env e adicione sua API Key da OpenAI e do Tavily
cp .env.example .env

# Instale o uv
pip install uv

# Instale as dependências
uv sync

# Execute o projeto
uv run researcher.py

# O mesmo estará disponível em: https://app.agno.com/
# Você também pode alterar últimas linhas do researcher.py para utilizá-lo de outra forma.
```
