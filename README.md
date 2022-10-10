**In Portuguese**
# Projeto de Banco de Dados de E-commerce

	- Contexto: Levantamento de requisitos
	- Projeto Conceitual: Modelo Entidade Relacionamento
	- Projeto Lógico: Modelo Relacional

# Modelando E-COMMERCE:
### Produto:
	- Os produtos são vendidos por uma unica plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)
	- Cada produto possui um fornecedor
	- Um ou mais produtos podem compor o pedido

### Cliente:
	- O cliente pode se cadastrar no site com seu CPF ou CNPJ
	- O endereço do cliente irá determinar o valor do frete
	- Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto

### Pedido:
	- O pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
	- Um produto ou mais compoem o pedido
	- O pedido pode ser cancelado


## Entidades: 
- Cliente, Pedido, Produto e Fornecedor & estoque

# Refinamento:
	- Cliente PJ e PF - Uma conta pode ser PJ ou PF, mas não pode ter as duas informações
	- Pagamento - Pode ter cadastrado mais de uma forma de pagamento
	- Entrega - possui status e código de restreio

## Software usado para modelagem
**MySQL Workbench**


**In English**
# E-commerce Database Project

	- Context: Requirements gathering
	- Conceptual Project: Entity Relationship Model
	- Logical Design: Relational Model

# Modeling E-COMMERCE:
### Product:
	- Products are sold through a single online platform. However, these may have different sellers (third parties)
	- Each product has a supplier
	- One or more products can compose the order

### Client:
	- Customers can register on the site with their CPF or CNPJ
	- The customer's address will determine the shipping cost
	- A customer can buy more than one order. This has a grace period for returning the product.

### Request:
	- Orders are created by customers and have purchase information, address and delivery status
	- One or more products make up the order
	- The order can be canceled


## Entities:
	- Customer, Order, Product and Supplier & stock

# Refinement:
	- PJ and PF client - An account can be PJ or PF, but cannot have both information
	- Payment - You may have registered more than one payment method
	- Delivery - has status and restriction code

## Software used for modeling
**MySQL Workbench**
