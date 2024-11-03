# Projeto Conceitual de Banco de Dados E-COMMERCE


## Descrição do Desafio
O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.

## Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

  1. Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
       Foi incluido apenas uma coluna (atributo) dentro da tabela (entidade) Cliente.
  2. Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
       Inserido uma nova tabela (entidade) Pagamento que contém as colunas (atributos) { idPgamento, dinheiro, cartão e pix } com formas de pagamento. O relacionamento entre as entidades Cliente e Pagamento é de um para muitos. Isso significa que um cliente pode ter vários pagamentos, mas um pagamento só pode ser associado a um único cliente.
  3. Entrega – Possui status e código de rastreio;
       Inserido uma nova tabela (entidade) Enrega que contém as colunas (atributos) { idPgamento, Status, cod_rastreio }. O relacionamento entre as entidades Pedido e Entrega é do tipo 1:1. Isso significa que cada pedido tem exatamente uma entrega associada a ele, e cada entrega está associada a exatamente um pedido.


     ![image](https://github.com/user-attachments/assets/9d29fabf-1a4d-4006-a471-11eed42dd199)

