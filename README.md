### financial_bank. Projeto acadêmico de auditoria de Laissa Albuquerque, Lucas Medina, Kallel dos Santos e Michel Pereira, com objetivo de apresentação do treinamento de Java Spring Boot.

##Entidades do Modelo Lógico
Campos do Cliente:

+ ID
+ Nome
+ CPF
+ Telefone
+ IDAgencia
+ Nome
+ Endereço
+ Telefone
+ IDCliente

Campos da Agência:

+ IDAgencia
+ Nome
+ Endereço
+ Telefone
+ IDCliente

Conta Corrente:

+ IDContaCorrente
+ ContaCorrenteAgencia
+ ContaCorrenteNumero
+ IDCliente

Transação:

+ ID
+ DataHora
+ Operação
+ IDConta Corrente

## Technologias usadas:

+ JAVA 17
+ Spring 4.18
+ MySql 8.0.25
+ Swagger

## Como execultar a aplicação:

+ Abrir o MySql e criar a tabela do sistema banco;
+ Abra a aplicação no Eclipse;
+ Clique com o botão direito e clique em "Run as" e selecione "Maven Build" para fazer o build;
+ Depois clique com o botão direito e clique em "Run as" e selecione "Java Application";
+ Logo depois verificar no Swagger, testar no localhost se a resposta dos métodos "POST, GET, PUT, DELETE" está vindo corretamente.


