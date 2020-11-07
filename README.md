![GoStack Bootcamp][logo]

### Level 03 - Desafio: Fundamentos React Native

[📑 Instruções do desafio][challenge]
&nbsp; | &nbsp;
[👨🏻‍🎨 Layout do Figma][layout]

---

### 📷 Screen captures

<div align="center">
  <img src="docs/listagem.png" width="360" alt="GoMarketplace - Listagem">
  <img src="docs/carrinho.png" width="360" alt="GoMarketplace - Carrinho">
</div>

---

### ⚙ Testes

- [x] - `should be able to list the products`: Para que esse teste passe, sua aplicação deve permitir que sejam listados na sua tela Dashboard, todos os produtos que são retornadas do Fake API. Essa listagem deve exibir o title e o price que deve ser formatado utilizando a função Intl.

- [x] - `should be able to add a product to the cart`: Para que esse teste passe, você deve permitir que seja possível adicionar produtos da sua Dashboard ao carrinho, utilizando o contexto de cart disponibilizado.

- [x] - `should be able to list the products on the cart`: Para que esse teste passe, você deve permitir que seja possível listar os produtos que estão salvos no contexto do seu carrinho na página Cart, nessa página exiba o nome do produto e o subtotal total de cada produto (price * quantity).

- [x] - `should be able to calculate the cart total`: Para que esse teste passe, tanto na página Dashboard, tanto na página Cart você deve exibir o valor total de todos os itens que estão no seu carrinho. Dica: Para calcular o total de todos os itens, você pode utilizar o reduce para somar todos os valores e retornar o valor total.

- [x] - `should be able to show the total quantity of itens in the cart`: Para que esse teste passe, tanto na página Dashboard, tanto na página Cart você deve exibir o número total de itens que estão no seu carrinho. Dica: Para calcular o total de todos os itens, você pode utilizar o reduce para somar todos os valores e retornar o valor total. Dica 2: Utilize o useMemo para armazenar o valor total do carrinho que você calculou.

- [x] - `should be able to increment product quantity on the cart`: Para que esse teste passe, você deve permitir que seja possível incrementar a quantidade de um produto do seu carrinho, utilizando o contexto de cart disponibilizado.

- [x] - `should be able to decrement product quantity on the cart`: Para que esse teste passe, você deve permitir que seja possível decrementar a quantidade de um produto do seu carrinho, utilizando o contexto de cart disponibilizado.

Dica: Ao decrementar a quantidade de um produto, não permita que ele seja decrementado para um valor negativo, sendo a quantidade mínima 1 para estar no carrinho.

- [x] - `should be able to navigate to the cart`: Para que esse teste passe, no seu componente FloatingCart na Dashboard, você deve permitir que ao clicar no botão de carrinho com o testID de navigate-to-cart-button, o usuário seja redirecionado para a página Cart.

- [x] - `should be able to add products to the cart`: Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho, você deve permitir que a função addToCart adicione um novo item ao carrinho.

- [x] - `should be able to increment quantity`: Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho, você deve permitir que a função increment incremente em 1 unidade a quantidade de um item que está armazenado no contexto.

- [x] - `should be able to decrement quantity`: Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho, você deve permitir que a função decrement decremente em 1 unidade a quantidade de um item que está armazenado no contexto.

- [x] - `should store products in AsyncStorage while adding, incrementing and decrementing`: Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho você deve permitir que todas as atualizações que você fizer no carrinho, sejam salvas no AsyncStorage. Por exemplo, ao adicionar um item ao carrinho, adicione-o também no AsyncStorage. Lembre de também atualizar o valor do AsyncStorage quando você incrementar ou decrementar a quantidade de um item.

- [x] - `should load products from AsyncStorage`: Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho, você deve permitir que todos os produtos que foram adicionados sejam buscados do AsyncStorage.

[logo]: https://github.com/leonardosposina/gostack13-lv01-d01/blob/master/docs/gostack-bootcamp.png?raw=true
[challenge]: https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-fundamentos-react-native
[layout]: https://www.figma.com/file/VgK3hsmyGbqiGu9FdqfUzF/GoMarketplace?node-id=0%3A1
