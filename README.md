# Docker Nodejs
## DockerfileNode
Este é um projeto de exemplo que demonstra como implantar uma aplicação Node.js em um contêiner Docker.

## Pré-requisitos 
Certifique-se de ter o Docker instalado em sua máquina. Você pode encontrar instruções de instalação [aqui](https://docs.docker.com/get-docker/).
## Como usar 
1. Clone este repositório em sua máquina local:
```bash
    git clone https://github.com/seu-usuario/DockerfileNode.git
```
2. Navegue até o diretório do projeto:
```bash
    cd DockerfileNode
```
3. Construa a imagem Docker:
```bash
    docker build -t node-app .
```
4. Execute o contêiner a partir da imagem criada:
```bash
    docker run -p 3000:3000 -d node-app
```
5. Acesse a aplicação em seu navegador em `http://localhost:3000`.

## Estrutura do projeto
 - **Dockerfile:** Arquivo de configuração do Docker para construir a imagem da aplicação.
 - **app.js:** Arquivo principal da aplicação Node.js.
 - **package.json:** Arquivo de manifesto do Node.js com as dependências da aplicação.

## Tecnologias utilizadas
 - Node.js
 - Docker
