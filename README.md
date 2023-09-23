# API Docker Container usando Servidor Node.js com Express e CORS

## Conteúdo

- [Visão Geral](#visão-geral)
- [Requisitos](#requisitos)
- [Configuração](#configuração)
- [Como Usar](#como-usar)
- [Configuração do Docker](#configuração-do-docker)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Visão Geral

Uma aplicação Docker Containers com Node.js que serve arquivos estáticos utilizando o Express como framework web e o middleware CORS.

## Requisitos

- Node.js
- npm
- Docker
- Docker Compose

## Configuração

### Clone o repositório:

```bash
git clone https://github.com/HudDavi/Docker-Container-Web-CV.git
```

### Instale as dependências:

```bash
cd Docker-Container-Web-CV
npm install
```

## Como Usar

### Para iniciar:

```bash
cd app
npm start
```

O servidor estará disponível em `http://localhost:3000` e `http://127.0.0.1:3000`.

## Contribuição

Para contribuir:

1. Fork o projeto.
2. Crie uma nova branch: `git checkout -b feature/nova-funcionalidade`.
3. Faça commit das alterações: `git commit -am 'Adicionei uma funcionalidade'`.
4. Faça push para a branch: `git push origin feature/nova-funcionalidade`.
5. Abra uma solicitação pull no GitHub.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).