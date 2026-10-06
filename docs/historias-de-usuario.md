# Histórias de Usuário

## História 1: cadastrar categoria

- **Requisito de partida:** O sistema deve permitir cadastrar categorias de lançamento (ex.: alimentação, transporte).
- **Quem é o usuário:** Um universitário que concilia trabalho e estudo e tem uma saída para lançar.
- **O que ele quer fazer:** Cadastrar uma categoria nova.
- **Por que isso importa para ele:** Para agrupar os lançamentos por tipo de gasto e visualizar quanto vai para cada um.

**História:** Como universitário que concilia trabalho e estudo, quero cadastrar minhas próprias categorias de lançamento, para saber quanto do meu dinheiro vai para cada tipo de gasto.

**Critério de aceitação:** Ao registrar um lançamento, a categoria criada deve aparecer na lista de opções do campo de categoria.

## História 2: excluir lançamento

- **Requisito de partida:** O sistema deve permitir excluir um lançamento registrado.
- **Quem é o usuário:** Um universitário que concilia trabalho e estudo e tem na lista um lançamento que não deveria estar lá, porque a compra foi estornada ou porque ele registrou por engano.
- **O que ele quer fazer:** Excluir esse lançamento.
- **Por que isso importa para ele:** Para que um gasto que não aconteceu não distorça a visão de para onde o dinheiro foi.

**História:** Como universitário que concilia trabalho e estudo, quero excluir um lançamento estornado ou registrado por engano, para que meu gráfico de gastos mostre apenas o que eu realmente gastei.

**Critério de aceitação:** Ao excluir um lançamento, ele deve sumir da lista do mês e as porcentagens do gráfico devem ser recalculadas sem o valor dele.

## História 3: visualizar gráfico

- **Requisito de partida:** O sistema deve exibir, em um gráfico, a porcentagem que cada categoria representa no total de saídas do mês selecionado.
- **Quem é o usuário:** Um universitário que concilia trabalho e estudo e chegou ao fim do mês com menos dinheiro do que esperava.
-  **O que ele quer fazer:** Selecionar um mês e ver quanto cada categoria representa no total de gastos.
- **Por que isso importa para ele:** Para descobrir quais tipos de gasto mais pesam e decidir onde ajustar.

**História:** Como universitário que concilia trabalho e estudo, quero ver quanto cada categoria representa no total dos meus gastos do mês, para identificar onde posso reduzir.

**Critério de aceitação:** 

- Ao selecionar um mês com saídas registradas, o gráfico deve mostrar a porcentagem de cada categoria, e a soma das porcentagens deve ser 100%;
- Ao selecionar um mês sem saídas registradas, o sistema deve exibir uma mensagem informando que não há gastos no período, no lugar do gráfico.