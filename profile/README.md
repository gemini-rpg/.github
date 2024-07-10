# GEMINI RPG
A aplicação é um jogo de RPG interativo onde o jogador pode selecionar um personagem. Através do uso de inteligência artificial, o jogo gera histórias únicas baseadas nas características do personagem e nas escolhas do jogador.

## 📋 Pré-requisitos
- Python 3.8
- Conta no Google Cloud com acesso ao serviço Google Generative AI (Gemini) 

## 🚀 Começando
1. Clone o repositório da API
```bash
git clone https://github.com/gemini-rpg/gemini-rpg-api.git
cd gemini-rpg-api
```

3. Crie um ambiente virtual para não instalar as dependências de forma global no seu sistema
```bash
python -m venv .venv
```
3. Rode o script de ativação
- Windows
```bash
.venv\Scripts\activate
```
- Linux
```bash
source venv/bin/activate
```
4. Instale as dependências
```bash
pip install -r requirements.txt
```
5. Configure as variáveis de ambiente
- Crie um arquivo `.env` na raiz do projeto e adicione as seguintes variáveis:
```bash
GEMINI_API_KEY=<your-gemini-api-key>
```

6. Rode a aplicação da API
```bash
flask --app server run
```

6. Clone o repositório do Front-end
```bash
git clone https://github.com/gemini-rpg/gemini-rpg-front.git
cd gemini-rpg-front
```

7. Abra e execute a solução do projeto
   
## ✒️ Autores

* **Gabriel Schorsch** - [Git](https://github.com/gabrielschorsch)
* **Gustavo Henrique** - [Git](https://github.com/GustavoHenriqueFerreira)
* **Gustavo Dionizio** - [Git](https://github.com/gugaSouza-dev)
* **Sabrina Santos** - [Git](https://github.com/sabrinadotsantos)

## 🛠️ Todo o projeto foi construído com:
<div style="display: inline_block"><br>
  <img align="center" alt="rpg-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/html5/html5-original.svg">
  <img align="center" alt="rpg-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="rpg-Csharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/csharp/csharp-original.svg">
  <img align="center" alt="rpg-js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/javascript/javascript-original.svg">
  <img align="center" alt="rpg-expo" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align='center' alt="rpg-azure" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" />
          
  ###

### Descrição das Ferramentas

UX/UI: Prototipação - Figma:

Figma é uma ferramenta de design de interface de usuário baseada na web. É usada para criar wireframes, protótipos interativos e interfaces de usuário completas.

Front-end: MVC:

ASP.NET MVC é um framework para construir aplicações web usando o padrão Model-View-Controller. É parte do ecossistema .NET da Microsoft e permite a criação de aplicações web robustas e escaláveis.


Back-end: Flask – Python – Websocket:

Flask é um microframework para Python que facilita o desenvolvimento de aplicações web com uma abordagem leve e modular. Ele permite a criação de APIs RESTful e é conhecido por sua simplicidade e flexibilidade.

WebSocket é um protocolo de comunicação que permite uma conexão bidirecional em tempo real entre um cliente e um servidor. É útil para aplicações que requerem atualizações instantâneas, como chats, jogos online, e sistemas de notificação. 

IA - Google Gemini:

Gemini é um modelo avançado de inteligência artificial desenvolvido pela Google DeepMind. É utilizado para processamento de linguagem natural, similar ao GPT (Generative Pre-trained Transformer).
