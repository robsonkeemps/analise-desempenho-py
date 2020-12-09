# Analise-desempenho-py
O trabalho faz parte do PPG em Computação Aplicada da Unisinos para disciplina e Analise de Desempenho do Professor Cristiano Bonato Both. 
Aqui você encontrara uma abordagens de resolução do problema usando algotimo de Levenshtein frequentemente utilizado para calcular a distância entre duas strings.

## Indice
- Pré-requisitos
- Instruções ao usuario
- Cenario
- Analise de desempenho
  - Definição das métricas de desempenho
  - Carga para teste de algoritmo 
  - Performance de metricas
  - Análise de algoritmo
  - Conclusões
- Autores

## Pré-requisitos
   - Python 3
   - Fuzzywuzzy
   - Python-Levenshtein
   - Numpy
   - Matplotlib

## Instruções ao usuario
É possivel implementar a formula de Levensntein do zero usando uma função Python, posterior para usar basta chamar a função passando os parametros, exemplo: [Levensnteins.py] (https://github.com/elielalbuquerque/analise-desempenho-py/blob/main/Levensntein.py)

## Cenario
Com base numa string de dados informada pelo usuario numa aplicação Python, desejamos comparar a similaridade com informações armazenadas em uma base e trazer a informaões que melhor representa com maior nivel de acurácia.
  - Opção 1: Implementar algoritmo de Levenshtein na linguagem Puthon que frequentemente é utilizado para calcular a distância entre duas strings determinando a similaridade enter as palavras.
  - Opção 2: Importar biblioteca FuzzyWuzzy, assim como o pacote Levenshtein, uma função de razão que calcula a razão de similaridade de distância de Levenshtein padrão entre duas sequências.

### Objetivo
Comparar o desempenho de uma implementação do algoritmo de Levenshtein com uma biblioteca Fuzzywuzzy para resolver o problema de comparação de similaridade de duas string com maior nivel de acertividade.
  
# Analise de desempenho
Mediremos o número mínimo de edições que você precisa fazer para alterar uma sequência de uma string na outra. A tecnica utilizada para avaliação será a de simulação usando como criterio a precisão para comparação.
Também é possível calcular a razão de similaridade com base na distância de Levenshtein. Isso pode ser feito usando a seguinte fórmula:
     
     (|a|+|b|)−leva,b(i,j)/|a|+|b)
     
Onde | a | e | b | são os comprimentos da sequência uma e sequência b respectivamente.

## Definição das métricas de desempenho
1. Quantidade de edições por inserções, exclusões ou substituições.
2. Percentual de acuracia.

### Carga para teste de algoritmo
- Testaremos cargas de trabalho com string de 5, 10, 20 caracteres para busca numa base de 100 palavras. 
Os arquivos usados no arquivo estarão armazenados no formato json conforme arquivo [base_dados.json] (Base de dados)

### Performance de metricas
- Testaremos uma acuracia minima de 95%
- Análise dos dados

### Analise do algoritmos


### Conclusões
Neste documento foi exeplificado como a correspondência por aproximada de strings e determinar o quão semelhantes são. Os exemplos apresentados aqui podem ser simples, mas são suficientes para ilustrar como lidar com vários casos do que um computador pensa serem strings incompatíveis atraves da correspondência de string difusa para mapear correspondentes a pesquisa de um sistema de turismo para recomendação. No entanto, a utilidade desta técnica pode ser expandida, não há limites para usos da correspondência difusa.
