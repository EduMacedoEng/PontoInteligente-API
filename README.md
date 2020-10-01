# API Smart Point System
API de sistema de ponto inteligente com Java e Spring Boot.
### Detalhes da API RESTful
A API RESTful Smart Point contém as seguintes características:
* Projeto criado com Spring Boot e Java 8
* Banco de dados MySQL com JPA e Spring Data JPA
* Autenticação e autorização com tokens Spring Security e JWT (JSON Web Token)
* Migração de banco de dados com Flyway
* Testes de unidade e integração com JUnit e Mockito
* Cache com EhCache
* Integração contínua com TravisCI
### Como executar o aplicativo
Certifique-se de ter o Maven instalado e adicionado ao PATH do seu sistema operacional, bem como ao Git.
``
git clone https://github.com/EduMacedoEng/Smart_Point_System-API.git
cd dot-smart-api
mvn spring-boot: run
Acesse os endpoints por meio do url http: // localhost: 8080
``
### Importando o projeto para Eclipse ou STS
No terminal, execute a seguinte operação:
``
Eclipse mvn: eclipse
``
No Eclipse / STS, importe o projeto como um projeto Maven.
