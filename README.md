# Projeto Web Services com Spring Boot e JPA / Hibernate

Este é um projeto desenvolvido como parte do curso "Java COMPLETO Programação Orientada a Objetos + Projetos" ministrado pelo Dr. Nelio Alves no link: https://www.udemy.com/course/java-curso-completo/.
O objetivo deste projeto é criar um sistema de Web Services utilizando Spring Boot e JPA/Hibernate para realizar operações CRUD (Create, Retrieve, Update, Delete) em um banco de dados.

## Objetivos do Projeto

- Criar um projeto Spring Boot Java.
- Implementar o modelo de domínio.
- Estruturar as camadas lógicas: resource, service, repository.
- Configurar um banco de dados de teste (H2).
- Povoar o banco de dados com dados de teste.
- Implementar operações CRUD.
- Tratar exceções de forma adequada.

## Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- H2 Database
- Maven

## Configuração do Ambiente de Desenvolvimento

1. Certifique-se de ter o Java JDK instalado na sua máquina. Você pode baixá-lo e instalá-lo a partir do site oficial da Oracle ou de outras fontes confiáveis.

2. Instale o Maven ou o Gradle na sua máquina, dependendo de qual gerenciador de dependências você preferir usar.

3. Clone este repositório para a sua máquina local:

   ```bash
   git clone https://github.com/Luis-Fernando-Almeida/workshop-springboot3-jpa
   ```

4. Navegue até o diretório do projeto e inicie a aplicação Spring Boot:

   ```bash
   cd projeto-web-services
   mvn spring-boot:run
   ```

5. O servidor estará rodando em http://localhost:8080.

## Como Usar

- Descreva aqui como usar a API, incluindo endpoints disponíveis, payloads esperados e respostas retornadas. Por exemplo:
    - `GET /usuarios`: Retorna todos os usuários cadastrados.
    - `POST /usuarios`: Cria um novo usuário no sistema.
    - `PUT /usuarios/{id}`: Atualiza as informações de um usuário existente.
    - `DELETE /usuarios/{id}`: Exclui um usuário do sistema.

## Contribuição

Se você quiser contribuir para este projeto, siga estas etapas:

1. Faça um fork do projeto.
2. Crie uma nova branch (`git checkout -b feature/nova-feature`).
3. Faça commit das suas alterações (`git commit -am 'Adicione uma nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Crie um novo Pull Request.

## Licença

Este projeto está licenciado sob a MIT License. Consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

