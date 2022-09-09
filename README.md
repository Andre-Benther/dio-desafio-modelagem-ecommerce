# dio-desafio-modelagem-ecommerce
Modelagem Diagrama ER - Workbench - para um E-commerce
#### Neste arquivo, realizei a primeira modelagem Diagrama ER para E-commerce.
##### Com certeza será necessario refinar esta estrutura principal.

Narrativa – Pedido
• O pedidos são criados por clientes e possuem informações de 
compra, endereço e status da entrega
• Um produto ou mais compoem o pedido
• O pedido pode ser cancelado


Narrativa - Produto
• Os produtos são vendidos por uma única plataforma online. 
Contudo, estes podem ter vendedores distintos (terceiros)
• Cada produto possui um fornecedor
• Um ou mais produtos podem compor um pedido


Narrativa - Cliente
• O cliente pode se cadastrar no site com seu CPF ou CNPJ
• O Endereço do cliente irá determinar o valor do frete
• Um cliente pode comprar mais de um pedido. Este tem um período
de carência para devolução do produto

Refinando
• Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não
pode ter as duas informações
• Pagamento – Pode ter cadastrado mais de uma forma de 
pagamento
• Entrega – Possuistatus e código de rastreio
