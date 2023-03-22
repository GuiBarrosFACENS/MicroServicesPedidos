
# Microsserviços na prática: implementando com Java e Spring

## 🔨 Objetivos do projeto

<p>  O projeto de pedidos, onde usa microsserviços com o banco MySQL.
</p>

<p>  Implementação do Service Discovery utilizando o [Eureka](https://spring.io/projects/spring-cloud-netflix).

     Solução desenvolvida pela Netflix e que faz parte do [Spring Cloud](https://spring.io/projects/spring-cloud).
     
     Arquitetura um [API Gateway](https://spring.io/projects/spring-cloud-gateway), que vai atuar como ponto central para as nossas requisições.
     
     Microsserviço pedidos, onde praticamos a comunicação síncrona e o balanceamento de carga, quando há mais de uma instância do projeto em execução.
</p>

<p>  Conceitos de circuit breaker e fallback, utilizando o [Resilience4J](https://resilience4j.readme.io/docs/getting-started-3) e promovendo uma alternativa quando um        dos serviços está inoperante.</p>
