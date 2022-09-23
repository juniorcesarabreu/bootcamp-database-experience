# Desafio de Projeto - Refinando um Projeto Conceitual de Banco de Dados - E-Commerce

> Bootcamp Database Experience



Escopo: Venda de Produtos



Produto

Estoque

Cliente

Pedido

Fornecedor



### Levantamento de requisitos - Narrativa

#### Produto

- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)
- Cada produto possui um fornecedor.
- Um ou mais produtos podem compor um pedido.



#### Cliente

- O cliente pode se cadastrar no site com seu CPF ou CNPJ.
- O endereço do cliente irá determinar o valor do frete.
- Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.
- Cliente PJ e PF - Uma conta pode ser PJ ou PF. mas não pode ter as duas informações
- O cliente pode ter mais de um cartão de crédito cadastrado.



#### Pedido

- Os pedidos são criados por clientes e possuem informações de compra, endereço, status da entrega e código de rastreio da entrega.
- Um produto ou mais compõem o pedido.
- O pedido pode ser cancelado.
- O pedido pode ser pago usando Boleto, Pix ou Cartão de crédito.



