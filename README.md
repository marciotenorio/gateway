# Gateway

Este projeto faz parte da tarefa final da disciplina de Programação Distribuída do semestre 2022.2 BTI/IMD/UFRN, ministrada pelo   

Prof. Dr. Nélio Alessandro Azevedo Cacho.   

### Descrição

- Serviço de gateway utilizando [Spring Cloud Gateway](https://spring.io/projects/spring-cloud-gateway) para os microserviços: finance, procurement e inventory management.
- Se registra automaticamente no discovery service
- Utiliza load balancer
- Utiliza a estratégia de retry
- Utiliza actuator para saúde do serviço

### Microserviços 
- Cloud function
- Discovery service
- Finance
- Gateway
- Inventory Management
- Procurement
- Config Server
