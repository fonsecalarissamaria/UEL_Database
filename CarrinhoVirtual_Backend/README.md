# 🛍️ Projeto Carrinho de Produtos  

## Sobre o Projeto  
O **Carrinho de Produtos** é uma aplicação web desenvolvida em **Java** com **Spring Boot**, permitindo a gestão eficiente de produtos em um carrinho.  

**Funcionalidades:**  
- Cadastro, listagem, edição e remoção de produtos  
- Adição e remoção de produtos do carrinho  
- Visualização do carrinho de compras  

---

## Tecnologias Utilizadas  
- **Backend:** Java 17, Spring Boot, Spring MVC, Spring Data JPA  
- **Frontend:** Thymeleaf, Bootstrap  
- **Banco de Dados:** H2 Database (padrão, em memória) com suporte a MySQL  

---

## Endpoints  

### Gerenciamento de Produtos  
- **`GET /index` ou `/`** → Lista produtos  
- **`GET /novo-produto`** → Formulário para novo produto  
- **`POST /adicionar-produto`** → Cadastra um novo produto  
- **`GET /editar/{id}`** → Formulário de edição  
- **`POST /atualizar/{id}`** → Atualiza um produto  
- **`GET /remover/{id}`** → Remove um produto  

### Funcionalidades do Carrinho  
- **`GET /adicionar-carrinho/{id}`** → Adiciona produto ao carrinho  
- **`GET /remover-carrinho/{id}`** → Remove produto do carrinho  
- **`GET /carrinho`** → Exibe os produtos no carrinho  

---

