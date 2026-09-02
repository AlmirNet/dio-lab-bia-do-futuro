# Passo a passo de execução

Esta pasta contém o código do seu agente financeiro.

## Setup do Ollama

```
# 1. Instalar Ollama (ollama.com)
# 2. Baixa um modelo que seja leve.
ollama pull gtp.oss

# 3. Testar se funciona
ollama run gpt-oss

```
## Código completo

``
Todo o código-fonte está no arquivo 'app.py'
``


## Estrutura Sugerida

```
src/
├── app.py              # Aplicação principal (Streamlit/Gradio)

```

## Exemplo de requirements.txt

```
streamlit
openai
python-dotenv
```

## Como Rodar

```bash
# Instalar dependências
pip install -r requirements.txt

# Rodar a aplicação
streamlit run app.py
```
