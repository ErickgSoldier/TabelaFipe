Tabela FIPE – Consulta de Veículos (Java + Spring Boot)

Projeto desenvolvido durante os estudos no Oracle Next Education (ONE), com o objetivo de consumir a API pública da Tabela FIPE e permitir consultas interativas via terminal.

📌 Funcionalidades

Escolha do tipo de veículo:

Carro

Moto

Caminhão

Listagem de marcas disponíveis

Consulta de modelos por marca

Filtro de modelos por nome

Consulta de valores de avaliação por ano

Exibição de todos os preços do modelo selecionado

🛠️ Tecnologias Utilizadas

Java

Spring Boot

CommandLineRunner

Consumo de API REST

Streams API

Jackson (conversão JSON)

Paradigma Orientado a Objetos

▶️ Como Executar o Projeto

Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git


Acesse o diretório do projeto:

cd TabelaFipeApplication


Execute a aplicação:

mvn spring-boot:run


Utilize o menu interativo no terminal para realizar as consultas.

🌐 API Utilizada

Tabela FIPE (Parallelum)
https://parallelum.com.br/fipe/api/v1/

📂 Estrutura do Projeto (resumida)
src/main/java
├── principal
│   └── Principal.java
├── model
│   ├── Dados.java
│   ├── Modelos.java
│   └── Veiculo.java
├── service
│   ├── ConsumoApi.java
│   └── ConverteDados.java
└── TabelaFipeApplication.java

🎯 Objetivo do Projeto

Consolidar conhecimentos em:

Consumo de APIs REST

Manipulação de JSON

Organização de código em camadas

Boas práticas com Java e Spring Boot
