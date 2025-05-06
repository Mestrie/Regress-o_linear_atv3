# Regressão Linear Multivariada: Análise Comparativa de Métodos de Otimização e Normalização de Features

Este projeto implementa e compara dois métodos de otimização para regressão linear multivariada - Gradiente Descendente (GD) e Equação Normal (NE) - e explora o impacto da normalização de *features* no desempenho do Gradiente Descendente.

## Descrição

O projeto aborda os seguintes tópicos principais:

* **Gradiente Descendente (GD):** Implementação do algoritmo iterativo para encontrar os parâmetros que minimizam a função de custo.
* **Equação Normal (NE):** Implementação da solução analítica direta para calcular os parâmetros ótimos.
* **Normalização de Features:** Utilização de técnicas para escalar as *features* e melhorar a convergência do Gradiente Descendente.
* **Comparação de Métodos:** Análise do desempenho, eficiência e robustez do GD e da NE.
* **Visualização da Função de Custo:** Representação gráfica da função de custo e da trajetória do Gradiente Descendente.

## Arquivos

* `regressao_linear_multivariada_Justino.ipynb`: Notebook Jupyter contendo a implementação dos algoritmos, a análise dos dados e a geração dos gráficos.
    * `features_normalize.py`: Funções para normalizar as *features* do conjunto de dados.
    * `compute_cost_multi.py`: Função para calcular a função de custo da regressão linear multivariada.
    * `gradient_descent_multi.py`: Funções para implementar o algoritmo do Gradiente Descendente.
    * `normal_eqn.py`: Função para calcular os parâmetros usando a Equação Normal.
* `ex1data2.txt`: Conjunto de dados utilizado para a regressão linear multivariada.

## Como usar

1.  Certifique-se de ter o Python e as bibliotecas necessárias instaladas (numpy, matplotlib).
2.  Execute o notebook `regressao_linear_multivariada_Justino.ipynb` em um ambiente Jupyter.
3.  Os resultados da análise e as visualizações serão gerados no próprio notebook.

## Resultados

O notebook gera os seguintes resultados:

* Gráficos de convergência do Gradiente Descendente.
* Comparação dos custos obtidos pelo Gradiente Descendente e pela Equação Normal.
* Visualizações 3D e gráficos de contorno da função de custo.
* Visualização do plano de regressão ajustado aos dados.

## Conclusões

Este projeto fornece uma análise abrangente da regressão linear multivariada, destacando a importância da normalização de *features* para o Gradiente Descendente e comparando a eficiência dos métodos de otimização. A modificação no código, onde os parâmetros do Gradiente Descendente são usados para calcular o custo no conjunto de dados normalizado, oferece *insights* adicionais sobre a interpretação dos resultados.

## Autor

Justino

