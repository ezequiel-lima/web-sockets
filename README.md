# Projeto de estudo: WebSockets em C#

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/ezequiel-lima/web-sockets/blob/main/LICENSE)

Este é um pequeno projeto de estudo em C# que utiliza a tecnologia WebSockets para enviar a hora atual de um servidor para um cliente.

O projeto consiste em um servidor simples escrito em C# que utiliza a biblioteca System.Net.WebSockets para estabelecer uma conexão WebSocket com um cliente. Quando a conexão é estabelecida, o servidor envia a hora atual para o cliente a cada segundo.

O cliente também é escrito em C# e utiliza a mesma biblioteca System.Net.WebSockets para se conectar ao servidor e receber as atualizações de hora. Quando uma nova hora é recebida, o cliente atualiza a informação no console.

Este projeto é um excelente exemplo de como a tecnologia WebSocket pode ser utilizada para criar comunicações bidirecionais em tempo real entre um servidor e um cliente. Além disso, o projeto também demonstra o uso da biblioteca System.Net.WebSockets em C# para estabelecer uma conexão WebSocket.

## Como executar o projeto
Para executar o projeto, siga as seguintes etapas:

1. Clone este repositório em sua máquina local usando o comando git clone https://github.com/ezequiel-lima/web-sockets.git
2. Abra o projeto no Visual Studio ou em outra IDE de sua preferência.
3. Compile o projeto e execute o servidor.
4. Em outra janela do Visual Studio, compile e execute o cliente.
5. Observe o console do cliente para ver a hora atualizada a cada segundo.

## Conclusão
Este projeto de estudo em C# é uma ótima maneira de aprender como a tecnologia WebSocket pode ser utilizada para criar comunicações em tempo real entre um servidor e um cliente.
