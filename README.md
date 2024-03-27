## Chat com WebSocket em Node.js e Socket.IO

Este é um projeto simples de chat utilizando Node.js, Express, e Socket.IO para comunicação em tempo real.

## Estrutura do Projeto
# Arquivos Principais:
- index.js: O arquivo principal que configura o servidor Express, inicia o servidor WebSocket com Socket.IO e define os eventos de comunicação.
- index.html: A interface do chat em HTML com Bootstrap para estilização.
- package.json: Arquivo de configuração do Node.js com as dependências necessárias.
- nodemon.json: Configuração do Nodemon para reiniciar automaticamente o servidor durante o desenvolvimento.

# Configuração e Instalação:

- Clone o repositório:

git clone https://github.com/RafaelCLopes/projeto-chat
cd projeto-chat
- Instale as dependências:

npm install
- Inicie o servidor de desenvolvimento:

npm run dev
- Acesse o chat no navegador:

Abra o navegador e vá para http://localhost:3333.

# Funcionalidades
- Envio de Mensagens em Tempo Real: Utilizando Socket.IO para transmitir mensagens em tempo real entre clientes e servidor.
- Interface Simples: Página HTML básica com Bootstrap para uma interface de chat simples.

# Como Usar
- Informe seu Usuário: Preencha o campo "Informe seu Usuário" na interface.
- Envie Mensagens: Digite mensagens no campo de texto e clique no botão "ENVIAR" ou pressione Enter.

# Eventos Socket.IO
- Conexão (connect): Estabelece a conexão entre o cliente e o servidor.
- Mensagem de Teste (teste): Permite o envio e recebimento de mensagens de teste.
- Desconexão (disconnect): Desconecta um cliente do servidor.

# Tecnologias Utilizadas
- Node.js: Ambiente de execução JavaScript do lado do servidor.
- Express: Framework para construção de aplicativos web com Node.js.
- Socket.IO: Biblioteca para comunicação em tempo real entre clientes e servidor.



https://github.com/RafaelCLopes/projeto-chat/assets/36003878/44f8c7dd-3edb-495e-8f0b-2a339c29c387




