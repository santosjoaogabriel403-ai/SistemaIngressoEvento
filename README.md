# Sistema de Ingressos para Eventos

## Descrição

Este projeto é um sistema web desenvolvido em Java para gerenciamento de ingressos de eventos.

O sistema permite:

- cadastro de clientes
- login
- visualização de eventos
- reserva de ingressos
- geração de QR Code
- validação administrativa de ingressos

O projeto foi desenvolvido utilizando conceitos de Programação Orientada a Objetos, como herança, polimorfismo e encapsulamento.

---

## Tecnologias utilizadas

- Java
- Spring Boot
- Maven
- MongoDB Atlas
- Thymeleaf

---

## Funcionalidades

### Cliente

- Cadastro de cliente
- Login
- Visualização de eventos
- Reserva de ingressos
- Consulta dos ingressos reservados
- Visualização do QR Code

### Administrador

- Visualização das reservas
- Validação de ingressos
- Controle de status
- Relatório simples de ingressos

---

## Estrutura do projeto

O sistema foi dividido em camadas:

### Controller
Responsável pelas requisições da aplicação.

### Service
Contém as regras de negócio.

### Repository
Responsável pelo acesso ao banco de dados.

### Model
Contém as classes do sistema.

---

## Banco de dados

O projeto utiliza MongoDB Atlas para armazenamento dos dados.

As principais coleções utilizadas são:

- clientes
- eventos
- reservas
- ingressos

---

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone LINK_DO_REPOSITORIO
```

---

### 2. Abrir o projeto

Abrir o projeto no NetBeans.

---

### 3. Configurar o MongoDB

No arquivo:

```text
src/main/resources/application.properties
```

Adicionar a conexão do MongoDB Atlas:

```properties
spring.data.mongodb.uri=sua_conexao_mongodb
```

---

### 4. Executar o projeto

Executar a aplicação pelo NetBeans.

---

### 5. Acessar no navegador

```text
http://localhost:8080
```

---

## Conceitos aplicados

- Herança
- Polimorfismo
- Encapsulamento
- Arquitetura multicamadas
- Integração com banco NoSQL
- Geração de QR Code

---

## Diagramas UML

O projeto possui:

- Diagrama de Classes
- Diagrama de Caso de Uso
- Diagrama de Componentes
