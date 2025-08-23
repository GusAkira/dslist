Essa semana rolou um Intensivo em Desenvolvimento Backend com Java organizado pelo professor Nelio Alves https://github.com/devsuperior.

Esse projeto consiste em organizar e posicionar jogos em base do criterio do usuario, utilizando uma arquitetura moderna e boas práticas de desenvolvimento.

<img width="831" height="347" alt="image" src="https://github.com/user-attachments/assets/7ef31efc-db5d-42c5-a609-0524715ada5c" />



Tecnologias e Ferramentas:
- Linguagem: Java
- Framework: Spring Boot
- Banco de Dados: H2 (para testes) e PostgreSQL (produção)
- Comunicação Web: Requisições HTTP e manipulação de dados em formato JSON
- Containerização: Docker para empacotamento e execução de aplicações em ambientes isolados
  
Arquitetura e Boas Práticas:
- Estrutura em múltiplas camadas:
- Controladores REST com uso de DTOs para transferência segura de dados
- Camada de Serviço com lógica de negócio e controle de transações
- Camada de Persistência com JPA/Hibernate, mapeamento de Entities e uso de Spring Data Repositories

 Docker & Deploy:
- Criação de Dockerfiles para empacotar a aplicação backend
- Uso de docker-compose para orquestrar serviços como banco de dados e aplicação
- Simulação de ambientes de produção com containers isolados
- Facilidade de testes e deploy em diferentes ambientes com consistência
  
Destaques Técnicos:
- Criação de APIs RESTful robustas e escaláveis
- Validação de dados e tratamento de exceções
- Testes com banco H2 para simulação de ambiente
- Integração com PostgreSQL para persistência real
- Aplicação de princípios SOLID e Clean Code
