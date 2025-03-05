# 📦 Sistema de Gerenciamento de Estoque  

**Descrição**  
Sistema CRUD desenvolvido com **Spring Boot, PostgreSQL e Thymeleaf** para gerenciar produtos, categorias e fornecedores.  

---

## 🚀 Tecnologias Utilizadas  
- ☕ **Java 21** + **Spring Boot 3**  
- 🗄 **Spring Data JPA** (para comunicação com o banco)  
- 🛢 **PostgreSQL** (banco de dados relacional)  
- 🎨 **Thymeleaf** (para renderizar páginas HTML)  
- 📦 **Maven** (para gerenciamento de dependências)  

---

## ⚙ Instalação e Configuração  

### 📌 1. Pré-requisitos  
Antes de iniciar, você precisará ter instalado:  
- ☕ [Java 21+](https://adoptium.net/)  
- 🛢 [PostgreSQL](https://www.postgresql.org/)  
- 📦 [Maven](https://maven.apache.org/)  

### 📌 2. Configurar Banco de Dados  
1. Abra o PostgreSQL e crie o banco:  
   ```sql
   CREATE DATABASE estoque_db;
   ```
2. Edite o arquivo `src/main/resources/application.properties` para definir suas credenciais:  
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/estoque_db
   spring.datasource.username=seu_usuario
   spring.datasource.password=sua_senha
   ```

### 📌 3. Clonar e Rodar o Projeto  
Clone o repositório:
   ```sh
   git clone https://github.com/AlexandreHilario/Sistema_Estoque.git
   cd Sistema_Estoque
   ```
Compilar e rodar a aplicação:
   ```sh
   mvn spring-boot:run
   ```
Acesse no navegador:
   ```sh
   http://localhost:8080/produtos
   ```

---

## 🛠 Funcionalidades do Sistema  
✔ Criar, editar e excluir Produtos  
✔ Gerenciar Categorias e Fornecedores  
✔ Interface web dinâmica com Thymeleaf  
✔ Banco de dados PostgreSQL para persistência  
✔ API compatível com Postman para testes  

---

## 🎯 Endpoints da API (Testes via Postman)  

| Método  | Endpoint                | Descrição                        |
|---------|-------------------------|----------------------------------|
| GET     | `/produtos`              | Listar todos os produtos        |
| POST    | `/produtos/salvar`       | Criar um novo produto           |
| PUT     | `/produtos/editar/{id}`  | Atualizar um produto existente  |
| DELETE  | `/produtos/deletar/{id}` | Excluir um produto              |

---

## 🎨 Screenshots do Sistema  
Adicione imagens do sistema rodando aqui! Exemplo:  
![Screenshot](exemplo-imagem.png)

---

## 🤝 Contribuição  
Se quiser contribuir:
1. Faça um fork do projeto  
2. Crie uma branch para sua feature:
   ```sh
   git checkout -b minha-feature
   ```
3. Faça o commit das alterações:
   ```sh
   git commit -m "Adicionando nova feature"
   ```
4. Envie para o GitHub:
   ```sh
   git push origin minha-feature
   ```
5. Abra um Pull Request 🚀

---

## 📜 Licença  
Este projeto é open-source e distribuído sob a licença MIT.  

---

## 🎯 **O que fazer agora?**  
1. **Crie um arquivo `README.md` na raiz do seu projeto.**  
2. **Copie e cole esse conteúdo dentro do arquivo.**  
3. **Adicione e envie para o GitHub:**  
   ```sh
   git add README.md
   git commit -m "Adicionando README.md"
   git push origin main
   ```

