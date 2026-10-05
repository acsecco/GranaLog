# Requisitos

## Status

| Arquivo | Situação |
|---|---|
| `arquitetura` | Não iniciado |
| `design-system` | Não iniciado |
| `historias-de-usuario` | Não iniciado |
| `requisitos` | Não iniciado |


## Problema e Público

**Problema**: Universitários com rotina corrida entre trabalho e estudo abandonam planilhas e anotações de gastos, porque mantê-las atualizadas toma tempo demais.

**Usuário principal**: Estudantes universitários que administram o próprio dinheiro, seja mesada, bolsa, salário de estágio ou de emprego em tempo integral.

## Requisitos funcionais

1. O sistema deve permitir cadastrar categorias de lançamento (ex.: alimentação, transporte);
2. O sistema deve permitir registrar um lançamento informando tipo (entrada ou saída), valor, data e categoria, que são obrigatórios, e uma descrição, que é opcional;
3. O sistema deve preencher o campo de data com o dia atual ao abrir o formulário de lançamento, permitindo que o usuário altere;
4. O sistema deve exibir a lista de lançamentos do mês selecionado;
5. O sistema deve permitir excluir um lançamento registrado;
6. O sistema deve exibir, em um gráfico, a porcentagem que cada categoria representa no total de saídas do mês selecionado.

## Requisitos não funcionais

1. As telas devem ser exibidas sem rolagem horizontal em telas a partir de 360 px de largura, pois o estudante tende a registrar o gasto pelo celular, no momento da compra;
2. Os valores devem ser exibidos em reais (R$);
3. Deve ser possível registrar um lançamento em até 30 segundos, contados a partir da abertura do formulário, pois o tempo gasto para manter o registro atualizado é o principal motivo de abandono.