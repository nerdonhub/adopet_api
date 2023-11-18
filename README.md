# Adopet API

## Descrição

A Adopet é uma plataforma fictícia dedicada à adoção de pets, oferecendo um ambiente para o cadastro de tutores, abrigos e pets, além de facilitar o processo de adoção. Este repositório contém o código-fonte da API Rest desenvolvida em Java para a Adopet.

O projeto foi concebido pela Alura e implementado por mim. A API serve como o backend do sistema, fornecendo endpoints para realizar operações relacionadas ao cadastro de tutores, abrigos, pets e adoções.

## Funcionalidades

1. **Cadastro/Atualização de Tutores**
   - Endpoint para registrar novos tutores ou atualizar informações existentes.

2. **Cadastro de Abrigos**
   - Endpoint para adicionar abrigos à plataforma.

3. **Cadastro de Pets do Abrigo**
   - Funcionalidade para registrar novos pets pertencentes a um abrigo.

4. **Listagem de Pets Disponíveis para Adoção**
   - Endpoint para obter uma lista de pets disponíveis para adoção.

5. **Solicitação de Adoção**
   - Funcionalidade que permite aos usuários solicitar a adoção de um pet.

6. **Aprovação/Reprovação de Adoção**
   - Endpoint para que os abrigos possam aprovar ou reprovar solicitações de adoção.

## Tecnologias Utilizadas

- Java 17
- Spring Boot 3
- Maven
- MySQL
- Hibernate
- Flyway

## Layout

O layout do projeto está disponível no Figma. [Clique aqui para acessar o layout no Figma](https://www.figma.com/file/TlfkDoIu8uyjZNla1T8TpH?embed_host=notion&kind=&node-id=518%3A11&t=esSUkfGQEWUeUASj-1&type=design&viewer=1).

## Instruções de Instalação

1. Clone este repositório.
2. Configure as informações de banco de dados no arquivo de configuração.
3. Execute as migrações do banco de dados usando o Flyway.
4. Inicie a aplicação.

```bash
# Clone o repositório
git clone https://github.com/nerdonhub/adopet_api.git

# Configure o banco de dados no arquivo application.properties (não fornecido por motivos de segurança).

# Execute as migrações do banco de dados
mvn flyway:migrate

# Inicie a aplicação
mvn spring-boot:run
```

A API estará acessível em `http://localhost:8080`.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
