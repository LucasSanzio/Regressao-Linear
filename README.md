# Regressão Linear - Análise de Experiência vs. Salário

## Descrição da Base de Dados
A base de dados utilizada contém informações sobre a relação entre a experiência profissional (em meses) e o salário (em milhares de dólares). Para facilitar a análise, os dados foram convertidos para anos de experiência.

## Justificativa da Técnica de Machine Learning
A técnica escolhida foi a **Regressão Linear**, pois o objetivo é modelar a relação entre uma variável independente (**experiência**) e uma variável dependente (**salário**). Como essa relação tende a ser linear, a regressão linear simples é uma abordagem apropriada para prever salários com base na experiência.

## Objetivos da Análise
O principal objetivo desta análise é prever o salário de um profissional com base em sua experiência. Isso pode ajudar empregadores, profissionais e analistas de mercado a entender tendências salariais e tomar decisões informadas sobre remuneração.

## Aviso ao Professor
Como a base de dados já estava limpa, não foi necessário verificar valores nulos, selecionar ou descartar colunas, nem mesmo verificar os nomes das colunas. No entanto, entendo que essas etapas seriam importantes caso a base de dados apresentasse inconsistências. Caso fosse necessário realizar essas verificações, os seguintes comandos poderiam ser utilizados:

- Para verificar valores nulos:
  ```python
  Base_Dados.isnull().sum()
  ```
- Para remover valores nulos:
  ```python
  Base_Dados.dropna(inplace=True)
  ```
- Para listar os nomes das colunas:
  ```python
  Base_Dados.columns
  ```
- Para remover colunas desnecessárias:
  ```python
  Base_Dados.drop(['Coluna_Indesejada'], axis=1, inplace=True)
  ```
