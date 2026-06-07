# CHATBOT

## Sobre o Projeto

Este projeto consiste no desenvolvimento de um assistente virtual inteligente focado em educação tecnológica e suporte ao desenvolvedor. Construído em Python através do script `dsa_assistente.py`, a aplicação cria um chatbot interativo que consome um modelo de linguagem de grande escala (LLM) por meio de uma integração direta de chaves de API.

O grande diferencial do assistente está na sua especialização e blindagem lógica: o código do projeto define uma diretriz sistêmica estrita (system prompt) antes de processar as requisições. Esta instrução força a Inteligência Artificial a atuar exclusivamente como uma especialista em Python, recusando ou redirecionando qualquer questionamento que fuja do escopo da linguagem, garantindo uma ferramenta de consulta precisa e focada.

---

## Funcionalidades

* Interface de usuário limpa, amigável e totalmente responsiva integrada ao navegador.
* Autenticação e conexão segura com o modelo de IA através do gerenciamento de chaves de API.
* Engenharia de Prompt (*System Prompting*) aplicada no código para restringir o escopo de atuação do modelo.
* Filtro de escopo automatizado que restringe as respostas e o suporte técnico unicamente para tópicos relacionados à linguagem Python.

---

## Tecnologias Utilizadas

* **Python 3**
* **Streamlit** (Biblioteca para construção de interfaces web e dashboards de dados)
* **API de LLM** (Integração com provedor de modelo de linguagem)

---

## Objetivo

O principal objetivo deste projeto é explorar o desenvolvimento de aplicações voltadas à Inteligência Artificial Generativa e design de prompt (*Prompt Engineering*). O foco técnico está em compreender como acoplar interfaces visuais modernas em Python sem a necessidade de frameworks complexos de front-end (usando o Streamlit), gerenciar dependências de projetos locais de IA de forma isolada com ambientes virtuais (`.venv`) e parametrizar o comportamento e as restrições de uma LLM.

---

## Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados conceitos como:

* Isolamento e gerenciamento de escopo de dependências utilizando ambientes virtuais do Python (`.venv`).
* Criação de arquivos de manifesto de pacotes (`requirements.txt`) para listar e instalar facilmente todas as bibliotecas de terceiros necessárias.
* Utilização do ecossistema Streamlit para renderizar caixas de chat, históricos de conversação e inputs de texto de forma dinâmica.
* Configuração e injeção de prompts de sistema para guiar e blindar o comportamento ético e conceitual da Inteligência Artificial.
* Gerenciamento de credenciais e chaves de acesso a serviços de terceiros de forma segura.

---

## Como Executar

1. Certifique-se de ter o Python instalado em sua máquina.
2. Acesse a pasta do projeto através do terminal:
```bash
cd CHATBOT
```

3. Ative o seu ambiente virtual (comandos variam por sistema operacional):

- Windows: .venv\Scripts\activate

- Linux/macOS: source .venv/bin/activate

4. Instale as dependências listadas no projeto:

```bash
pip install -r requirements.txt
```

4. Certifique-se de configurar sua chave de API nas configurações ou variáveis de ambiente do projeto.

5. Execute a aplicação por meio do comando do Streamlit:

```Bash
streamlit run dsa_assistente.py
```

---

## Estrutura do Projeto

```text
CHATBOT/
│
├── .venv/               # Ambiente virtual com as dependências instaladas
├── .vscode/             # Configurações de workspace do editor
├── dsa_assistente.py    # Script principal do chatbot e interface Streamlit
├── requirements.txt     # Listagem de dependências do projeto para instalação
└── README.md
```

---

## Licença
Este projeto foi desenvolvido exclusivamente para fins educacionais e de aprendizado.

Desenvolvido como prática de desenvolvimento de ferramentas inteligentes de IA, engenharia de prompt e criação de interfaces web ágeis com Streamlit e Python.
