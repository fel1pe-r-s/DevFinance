**Tags**: #CSS #Docker #Html #JavaScript #Markdown

#DevFinance # DevFinance

**Status**: `#Project/Static` `#Finance` `#Frontend`

## 📝 Descrição
O **DevFinance** é uma aplicação de controle financeiro desenvolvida durante a Maratona Discover. Ele permite cadastrar e visualizar entradas e saídas financeiras de forma simples e intuitiva.

> [!NOTE]
> Este projeto é uma aplicação estática (HTML, CSS, JS) servida via Nginx/Docker.

## 🔗 Repositório
*Este projeto possui código fonte local.*
- ** Código Fonte**: [Local Files](./)

## 🚀 Como Rodar (Docker)

Esta aplicação foi containerizada para fácil execução.

### Pré-requisitos
- Docker & Docker Compose instalados.

### Passos
1. Navegue até a pasta do projeto:
   ```bash
   cd 01_Projetos/DevFinance
   ```
2. Suba o container:
   ```bash
   docker-compose up -d
   ```
3. Avesse no navegador:
   http://localhost:8080

## 📂 Estrutura
- `index.html`: Estrutura da página.
- `style.css`: Estilização.
- `script.js`: Lógica de transações e DOM.
- `Dockerfile`: Configuração Nginx.
