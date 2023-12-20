# Calculadora de Investimentos

Uma calculadora simples para simular investimentos financeiros e visualizar resultados mensais.

## Funcionalidades

- Calcula o resultado final de um investimento com base em parâmetros fornecidos.
- Gera uma tabela de resultados mensais.

# Como Funciona

1. Validação e Criação da Tabela:
   O código começa com a definição de uma função isNonEmptyArray que verifica se um array é não vazio. Em seguida, há a definição da função createTable, que cria uma tabela HTML a partir de arrays de colunas e dados.

2. Criação do Cabeçalho da Tabela:
   A função createTableHeader é responsável por criar o cabeçalho da tabela. Ela recebe uma referência à tabela e um array de colunas, criando elementos <th> para cada coluna.

3. Criação do Corpo da Tabela:
   A função createTableBody é encarregada de criar o corpo da tabela. Similar à criação do cabeçalho, ela percorre o array de dados, criando uma linha <tr> para cada item e preenchendo as células <td> com os dados correspondentes.

4. Integração com Gráficos

5. Manipulação do Formulário e Interface Gráfica:
   A segunda parte do código lida com a manipulação do formulário HTML, validação de entrada, e a interação com gráficos (que está comentada). Além disso, há funções para limpar o formulário e redefinir gráficos.

6. HTML e CSS:
   O HTML define a estrutura da página, incluindo um formulário e seções para tabelas e gráficos (comentados). O CSS fornece estilos para a interface.

7. Uso de Módulos:
   O código é dividido em módulos usando o import. O módulo principal é main.js, e há importações de funções de outros módulos.
