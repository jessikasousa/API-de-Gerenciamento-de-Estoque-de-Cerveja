<h2>Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.</h2>

Na live coding com o Rodrigo Peleias foram feitos testes de uma API REST para o gerenciamento de estoques de cerveja. 

Pré-requisitos para a execução do projeto:

* Java 14 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.
* Controle de versão GIT instalado na sua máquina.

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

