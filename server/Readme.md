# NLW Agents

Projeto desenvolvido durante o evento da **Rocketseat**, focado na criação de agentes inteligentes utilizando tecnologias modernas de IA.

## 🚀 Tecnologias Utilizadas

- **Python 3.8+**
- **FastAPI** - Framework web moderno e rápido
- **OpenAI API** - Integração com modelos de linguagem
- **Pydantic** - Validação de dados e serialização
- **Uvicorn** - Servidor ASGI para aplicações Python

## 📁 Estrutura do Projeto

```
nlw-agents/
├── src/
│   ├── agents/          # Lógica dos agentes
│   ├── api/            # Endpoints da API
│   └── models/         # Modelos de dados
├── requirements.txt    # Dependências Python
└── main.py            # Arquivo principal
```

## 🛠️ Setup e Configuração

### Pré-requisitos

- Python 3.8 ou superior
- Conta na OpenAI (para API Key)

### Instalação

1. Clone o repositório:

```bash
git clone <repository-url>
cd nlw-agents
```

2. Crie um ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate     # Windows
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Configure as variáveis de ambiente:

```bash
cp .env.example .env
```

Edite o arquivo `.env` com suas configurações:

```
OPENAI_API_KEY=sua_chave_aqui
```

### Executando o Projeto

```bash
uvicorn main:app --reload
```

A aplicação estará disponível em `http://localhost:8000`

## 📚 Padrões de Projeto

- **Repository Pattern** - Abstração da camada de dados
- **Dependency Injection** - Gerenciamento de dependências
- **Factory Pattern** - Criação de agentes especializados

## 🤖 Funcionalidades

- Criação e gerenciamento de agentes IA
- API RESTful para interação com agentes
- Processamento de linguagem natural
- Integração com modelos OpenAI

---

Desenvolvido com ❤️ durante o evento da Rocketseat
