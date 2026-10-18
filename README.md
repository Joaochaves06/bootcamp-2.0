# CryptoDex — Aplicação Web com PokeAPI & Supabase

Projeto prático desenvolvido para a unidade curricular de Aplicações Web, consistindo numa interface moderna integrada a uma API pública e a uma base de dados relacional na nuvem.

## 🚀 Funcionalidades
- **Consulta Assíncrona:** Pesquisa em tempo real de itens através da PokeAPI com tratamento de erros.
- **Persistência de Dados (BaaS):** Ligação direta ao Supabase para guardar e listar favoritos numa tabela relacional dedicada (`favoritos`).
- **Interface Responsiva:** Design limpo utilizando Tailwind CSS e fontes tipográficas modernas.
- **Conteinerização:** Empacotado com Docker utilizando um servidor Nginx leve (Alpine Linux).

---

## 🛠️ Tecnologias Utilizadas
- **Front-end:** HTML5, JavaScript (ES Modules), Tailwind CSS
- **Base de Dados:** Supabase (PostgreSQL)
- **Infraestrutura:** Docker & Nginx

---

## 📦 Instruções de Execução (Docker)

Para rodar a aplicação localmente na porta **`9090`**, certifique-se de que o Docker está ativo e execute os comandos abaixo diretamente na pasta raiz do projeto:

```bash
# 1. Construir a imagem Docker
docker build -t crypto-dex:latest .

# 2. Executar o container na porta 9090
docker run -d -p 9090:80 crypto-dex:latest# bootcamp-2.0
