# 🚀 API de Cadastro de Usuário e Autenticação  

Bem-vindo à **API de Cadastro de Usuário e Autenticação**! Esta API foi desenvolvida com boas práticas para um projeto inicial sólido, utilizando **Java** e **Spring Boot**.  

## 🛠️ Tecnologias Utilizadas  

- **Java** ☕  
- **Spring Boot** 🚀  
- **Docker** 🐳  
- **Render** 🌐 *(Hospedagem em produção para testes)*  

## 📌 Funcionalidades  

✅ Cadastro de usuários  
✅ Autenticação de usuários  
✅ Proteção com autenticação JWT  
✅ Estruturada com boas práticas  

## 🚀 Como Rodar o Projeto  

### 🔧 Pré-requisitos  
Antes de começar, você precisará ter instalado em sua máquina:  

- **Java 17+**  
- **Docker** *(caso queira rodar com container)*  
- **Maven** *(para build e gerenciamento de dependências)*  

### 🏗️ Passos para rodar  

1️⃣ Clone o repositório  
```sh
2️⃣ Configure as variáveis de ambiente (caso necessário)

3️⃣ Execute o projeto via Maven

sh
Copiar
Editar
mvn spring-boot:run
4️⃣ A API estará rodando em:

arduino
Copiar
Editar
http://localhost:8080
🐳 Rodando com Docker
Se quiser rodar a aplicação em um container Docker:

sh
Copiar
Editar
docker build -t meu-projeto .
docker run -p 8080:8080 meu-projeto
🌎 Deploy no Render
A aplicação foi testada no Render, um serviço de deploy simples e eficiente.

Caso queira testar, basta acessar:

arduino
Copiar
Editar
https://sua-api.render.com
📝 Contribuição
Se quiser contribuir, fique à vontade! Abra uma Issue ou envie um Pull Request.

