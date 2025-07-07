# Chat em Tempo Real com Socket.IO

Este é um projeto de chat em tempo real desenvolvido com Node.js, Express e Socket.IO. Ele permite que múltiplos usuários conectados à mesma rede troquem mensagens instantaneamente, com uma interface simples e diferenciando visualmente quem enviou a mensagem.

---

## Tecnologias utilizadas

- Node.js
- Express
- Socket.IO
- HTML5 + CSS3 + JavaScript

---
## Funcionamento 
Para esse projeto funcionar, foi preciso instalar duas bibliotecas usando o npm (Express e Socket.IO)
No arquivo server.js execute: npm install express socket.io


---

## Estrutura do projeto
├── public
│ ├── index.html
│ ├── style.css
│ └── script.js
├── server.js
└── README.md


## Como executar

### 1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/chat-socketio.git
cd chat-socketio


### execute no terminal (control + j) 
node server.js

###abra:
http://localhost:3000

###caso queira se conectar com outras pessoas
1. de ipconifg no cmd (caso seja windows) e ifconfig se for linux
2. ao ver seu ip, a outra pessoa abre no navegador, usando o ip da sua maquina http://192.168.00:3000
