# Cálculo de Métricas de Avaliação de Aprendizado

## Descrição/Problematica
Neste projeto, vamos calcular as principais métricas para avaliação de modelos de classificação de dados, como acurácia, sensibilidade (recall), especificidade, precisão e F-score. Para que seja possível implementar estas funções, você deve utilizar os métodos e suas fórmulas correspondentes (Tabela 1).

Para a leitura dos valores de VP, VN, FP e FN, será necessário escolher uma matriz de confusão para a base dos cálculos. Essa matriz você pode escolher de forma arbitraria, pois nosso objetivo é entender como funciona cada métrica.

## Objetivo

Este projeto tem como objetivo calcular e apresentar diferentes métricas de avaliação para modelos de aprendizado de máquina. O foco principal é o uso da biblioteca `scikit-learn` para calcular métricas como acurácia, precisão, sensibilidade (recall), especificidade e F1-score.


## Funcionalidades

O projeto oferece as seguintes funcionalidades:

* Calcula a acurácia do modelo.
* Calcula a precisão do modelo para cada classe e a precisão média.
* Calcula a sensibilidade (recall) do modelo para cada classe e a sensibilidade média.
* Calcula a especificidade do modelo para cada classe e a especificidade média.
* Calcula o F1-score do modelo para cada classe e o F1-score médio.
* Apresenta os resultados de forma clara e organizada.


## Como usar

1. **Instale as bibliotecas necessárias:**
2. **Importe as funções:**
3. **Calcule as métricas:**
## Exemplo

Veja um exemplo de como usar o projeto no arquivo [Matrix_confusion.ipynb]

## Observações

* Certifique-se de ter as etiquetas verdadeiras (`y_true`) e as etiquetas previstas (`y_pred`) antes de calcular as métricas.
* Escolha o tipo de média (`macro` ou `weighted`) que for mais apropriado para o seu caso de uso.
* Para calcular a especificidade, foi criada uma função auxiliar, pois não há uma função direta na biblioteca `scikit-learn`. Veja a implementação no código.


## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request com suas sugestões de melhorias ou novas funcionalidades.


## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
