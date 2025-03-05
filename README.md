📦 Sistema de Gerenciamento de Estoque
Descrição
Sistema CRUD desenvolvido com Spring Boot, PostgreSQL e Thymeleaf para gerenciar produtos, categorias e fornecedores.

🚀 Tecnologias Utilizadas
Java 17 + Spring Boot 3
Spring Data JPA (para comunicação com o banco)
PostgreSQL (banco de dados relacional)
Thymeleaf (para renderizar páginas HTML)
Maven (para gerenciamento de dependências)
⚙ Instalação e Configuração
📌 1. Pré-requisitos
Antes de iniciar, você precisará ter instalado:

Java 17+
PostgreSQL
Maven
📌 2. Configurar Banco de Dados
Abra o PostgreSQL e crie o banco:
sql
Copy
Edit
CREATE DATABASE estoque_db;
Edite o arquivo src/main/resources/application.properties para definir suas credenciais:
properties
Copy
Edit
spring.datasource.url=jdbc:postgresql://localhost:5432/estoque_db
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
📌 3. Clonar e Rodar o Projeto
Clone o repositório

sh
Copy
Edit
git clone https://github.com/AlexandreHilario/Sistema_Estoque.git
cd Sistema_Estoque
Compilar e rodar a aplicação

sh
Copy
Edit
mvn spring-boot:run
Acesse no navegador

bash
Copy
Edit
http://localhost:8080/produtos
🛠 Funcionalidades do Sistema
✅ Criar, editar e excluir Produtos
✅ Gerenciar Categorias e Fornecedores
✅ Interface web dinâmica com Thymeleaf
✅ Banco de dados PostgreSQL para persistência
✅ API compatível com Postman para testes

🎯 Endpoints da API (Testes via Postman)
Método	Endpoint	Descrição
GET	/produtos	Listar todos os produtos
POST	/produtos/salvar	Criar um novo produto
PUT	/produtos/editar/{id}	Atualizar um produto existente
DELETE	/produtos/deletar/{id}	Excluir um produto
🎨 Screenshots do Sistema
🖼️ Adicione imagens do sistema rodando (exemplo abaixo)

🤝 Contribuição
Se quiser contribuir:

Faça um fork do projeto
Crie uma branch para sua feature:
sh
Copy
Edit
git checkout -b minha-feature
Faça o commit das alterações:
sh
Copy
Edit
git commit -m "Adicionando nova feature"
Envie para o GitHub:
sh
Copy
Edit
git push origin minha-feature
Abra um Pull Request 🚀
📜 Licença
Este projeto é open-source e distribuído sob a licença MIT.
