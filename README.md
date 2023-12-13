# Nubank Specialist Challenge

## Desafio

O desafio será criar uma Checkout 100% do 0

1 - Ao entrar na página deve ser possível selecionar o produto que deseja e adiciona-lo ao carrinho de compras
2 - No carrinho deve ser possível indicar quantidade e a opçõe de remover o produto.
3 - Será necessário mostrar os metodos de pagamento sendo ele, cartão (crédito ou débito), pix e boleto
4 - Após a finalização da compra, devemos mostrar ao cliente uma página demonstrando um mapa, onde se encontra a localização da encomenda e da caso do cliente, com uma estimativa de quantos dias a entrega pode demorar

### Implementação

#### Backend

- Deve ser feito em Rust, em uma arquitetura monolítica, porém delegando a workers tarefas assíncronas
- O Banco de dados deve ser o Postgres com versionamento de tabelas
- Deve ser realizado stress tests
- Tudo deve estar em Docker
- O Kubernetes será o responsável pelo gerênciamento e escalonamento das instancias.

#### Frontend

- O frontend deve ser feito em Vue 3
- Deve subir em um container docker junto com a API backend através de um docker compose
