# Back-End Challenge - Contas Correntes

## Desafio: Run The Bank!

Faça o cadastro de clientes na instituição, o cadastro pode ser de PF (Pessoa Física) ou de PJ (Pessoa Jurídica). 

Após o cadastro do cliente ser efetuado, será permitido que sejam abertas uma ou mais contas para aquele cadastro. 

As contas devem possuir um saldo onde poderão realizar movimentações de pagamentos entre as contas, gerando um débito(saída) para um conta e crédito(entrada) para a outra!


### Requisitos Funcionais:

-   Ambos os tipos de **Clientes**, devem possuir Nome, CPF/CNPJ, Endereço e Senha. **CPF/CNPJ devem ser únicos no sistema**.

-   As **Contas**, devem possuir Id, Agência, Saldo, Status (Ativa/Inativa). **Id e Agência devem ser únicos no sistema**.

-   Validar o status da Conta e se ela possui saldo suficiente para realizar a transferência.

-   O pagamento é uma operação transacional que pode ser anulada ou revertida, nesse cenário o dinheiro deverá voltar para as contas.

-   Após efetuar o pagamento, ambos os clientes devem receber uma notificação, **o serviço é externo e considere que esse pode falhar ou estar indisponível**. Use esse endpoint para o envio (https://run.mocky.io/v3/e542e773-c6a7-465f-a8e6-3a8377fe8260).

-   Construa uma aplicação RESTFul.


### Requisitos Técnicos:

-   Java 11 (Ou Superior).
-   Spring Boot.
-   Spring Data JPA.
-   Banco de Dados da sua escolha (H2 é uma ótima escolha para esse cenário 😄).

### O que será um Diferencial:

-   Apache Camel.
-   Testes unitários.
-   Design Patterns.
-   Documentação.
-   Exemplo de seus payloads.
-   Proposta de melhoria na arquitetura.

## Payloads

Exponha os Payloads conforme achar melhor de acordo com os requisitos (Queremos conhecer seu estilo ninja 🥷).

Caso prefira, aqui está um exemplo:

### Cadastro de Clientes

POST /customer
```json
{
    "name": "Ash Ketchum",
    "document": 12365478902,
    "address": "Cidade de Pallet",
    "password": "StrongPassword951!#@"
}
```

  
## Avisos antes de começar

-   Em seu próprio GitHub, faça a criação de um repositório.
-   Os commits devem ser realizados em seus próprios repositórios (Desejamos que escreva os comentários dos commits com muito carinho 😆).
-   Envie o link do seu repositório para seu recrutador.


## O que será avaliado:

-   Código limpo e organizado (nomenclatura, etc)
-   Conhecimento de padrões (PSRs, design patterns, SOLID)
-   Utilização de anotações e recursos do Spring Boot
-   Estruturação de Pacotes
-   Modelagem de Dados
-   Tratamento de erros e exceções
-   Desacoplamento de camadas e componentes
-   Documentação
-   Caso esteja se aplicando para uma vaga sênior, um desenho de arquitetura é muito bem-vindo. (Você Junior ou Pleno também pode :heart:)
-   Você candidato que não esteja conseguindo concluir o desafio, nos envie mesmo assim, você será avaliado de acordo com o nível da vaga (Continue a nadar 🐟)


## O que NÃO será avaliado :warning:
-   Frontend (só será avaliada a (API Restful)


**Fique tranquilo(a) e respire, desejamos uma boa sorte!**
