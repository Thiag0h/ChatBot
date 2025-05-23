
# 🤖 ChatBot com OpenAI API

Este é um chatbot simples baseado na API da OpenAI (modelo GPT-3.5-turbo), feito em Python para interações no terminal.

---

## 💡 Funcionalidades

- Interação com IA via linha de comando
- Integração com o modelo GPT-3.5-turbo
- Uso seguro da chave da API com `.env`
- Tratamento de erros simples

---

## 🚀 Como usar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/chatbot-openai.git
cd chatbot-openai
```

### 2. Instale as dependências

```bash
pip install -r requirements.txt
```

### 3. Crie o arquivo `.env`

Crie um arquivo chamado `.env` na raiz do projeto e adicione sua chave da API da OpenAI:

```
OPENAI_API_KEY=sk-sua-chave-aqui
```

### 4. Execute o chatbot

```bash
python ChatBot.py
```

---

## 🛠 Requisitos

- Python 3.10 ou superior
- Conta na [OpenAI](https://platform.openai.com/)
- Biblioteca `openai` e `python-dotenv`

---

## 📦 Arquivos

| Arquivo       | Descrição                                       |
|---------------|-------------------------------------------------|
| `ChatBot.py`  | Código principal do chatbot                     |
| `.env`        | (não versionado) Chave da API da OpenAI         |                    
| `README.md`   | Documentação do projeto                         |

---

## ⚠️ Avisos

- Nunca compartilhe sua chave da OpenAI publicamente.
- Se quiser usar outros modelos (como GPT-4), altere o valor do parâmetro `model` no código.

---

Feito com 💻 por Thiag0h
