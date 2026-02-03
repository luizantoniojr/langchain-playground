# LangChain Playground

Um projeto de aprendizado e experimentação com LangChain, focado em explorar as capacidades de LLMs (Large Language Models) e construir aplicações com IA.

**Repositório:** [https://github.com/luizantoniojr/langchain-playground](https://github.com/luizantoniojr/langchain-playground)

## 📋 Sobre

Este repositório contém notebooks Jupyter e scripts para experimentar com:
- Integração de LLMs (OpenAI, Hugging Face)
- Processamento de documentos (PDF, texto)
- Extração de conteúdo de mídia (YouTube, áudio)
- Construção de chains e agents com LangChain
- Integração com APIs do Google

## 🚀 Como Começar

### Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/luizantoniojr/langchain-playground.git
cd langchain-playground
```

2. Crie um ambiente virtual (recomendado):
```bash
python -m venv .venv
```

3. Ative o ambiente virtual:
   - **Windows:**
     ```bash
     .venv\Scripts\activate
     ```
   - **Linux/Mac:**
     ```bash
     source .venv/bin/activate
     ```

4. Instale as dependências:
```bash
pip install -r requirements.txt
```

5. Configure as variáveis de ambiente:
   - Crie um arquivo `.env` na raiz do projeto
   - Adicione suas chaves de API:
     ```
     OPENAI_API_KEY=sua_chave_aqui
     ```

## 📚 Estrutura do Projeto

```
langchain-playground/
├── notebooks/
│   └── 01-first-test.ipynb    # Primeiros testes com LangChain
├── requirements.txt            # Dependências do projeto
├── .gitignore                  # Arquivos ignorados pelo Git
└── README.md                   # Este arquivo
```

## 📦 Dependências Principais

- **langchain**: Framework principal para construir aplicações com LLMs
- **langchain-openai**: Integração com modelos OpenAI
- **langchain-community**: Integrações com várias ferramentas e serviços
- **openai**: SDK oficial da OpenAI
- **transformers**: Biblioteca Hugging Face para modelos de NLP
- **pypdf**: Processamento de arquivos PDF
- **yt_dlp**: Download e extração de conteúdo do YouTube
- **beautifulsoup4**: Web scraping
- **google-api-python-client**: Integração com APIs do Google

## 🧪 Uso

Abra os notebooks Jupyter para explorar os exemplos:

```bash
jupyter notebook notebooks/
```

Ou use JupyterLab:

```bash
jupyter lab
```

## 📝 Notebooks

### 01-first-test.ipynb
Introdução básica ao LangChain:
- Inicialização de LLMs
- Chamadas simples e streaming
- Processamento em lote
- Chat models e mensagens

## 🔐 Segurança

⚠️ **Importante**: Nunca commite suas chaves de API no repositório. Use o arquivo `.env` para armazenar credenciais sensíveis, que já está configurado no `.gitignore`.

## 🤝 Contribuindo

Este é um projeto de aprendizado pessoal, mas sinta-se à vontade para fazer fork e adaptar para suas necessidades!

## 📄 Licença

Este projeto é para fins educacionais e de aprendizado.

## 🔗 Recursos Úteis

- [Documentação do LangChain](https://python.langchain.com/)
- [Documentação da OpenAI](https://platform.openai.com/docs)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers)
