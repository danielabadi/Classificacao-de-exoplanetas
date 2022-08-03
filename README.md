# Trabalho Prático 1: Classificação de Exoplanetas
## Objetivo
O objetivo deste trabalho prático é de praticar os conceitos aprendidos na disciplina e de adquirir experiência no uso de alguns dos principais métodos de classificação, na avaliação de modelos e na interpretação e apresentação de resultados de experimentos. Para isso você irá utilizar e comparar métodos de classificação baseados em princípios diferentes em um problema de classificação binária de candidatos a exoplanetas.

## Tarefa

Neste trabalho você deverá realizar uma comparação entre seis métodos de classificação: Naive Bayes, Decision Tree, k-Nearest Neighbors, Support Vector Machines, Random Forest e Gradient Tree Boosting. Além disto você deverá realizar os experimentos listados abaixo específicos para cada método. Pode ser necessário normalizar os dados e testar diferentes valores para os hiperparâmetros dos métodos para se obter bons resultados (não é necessário entregar todas as combinações testadas, apenas a de melhor resultado, exceto os casos que foram pedidos abaixo). A avaliação dos métodos deverá ser feito usando a acurácia e validação cruzada k-fold com k igual a 5.

- Naive Bayes: Apenas um experimento para servir de baseline
- Decision Tree: Variar a altura máxima da árvore (incluindo permitir altura ilimitada) e mostrar os resultados graficamente
- SVM: Avaliar os kernels linear, sigmoid, polinomial e RBF
- k-NN: Variar o número k de vizinhos e mostrar os resultados graficamente
- Random Forest: Variar o número de árvores e mostrar os resultados graficamente.
- Gradient Tree Boosting: Variar o número de iterações e mostrar os resultados graficamente.

Você não precisa implementar os métodos listados acima. Todos os métodos listados acima estão disponíveis na biblioteca scikit-learn da linguagem Python. Você também pode utilizar bibliotecas auxiliares, para gerar gráficos e de operações matemáticas por exemplo, desde que elas não implementem o experimento em si.

Para cada um dos experimentos realizados você deverá explicar qual o objetivo do experimento (qual o significado do hiperparâmetro que está sendo variado por exemplo) e incluir uma interpretação dos resultados com base nos conceitos teóricos estudados na disciplina. Ao final deverá ser feita uma comparação entre a performance dos métodos, incluindo curva ROC e as métricas de precisão e revocação (precision e recall).
