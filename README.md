# Analise-desempenho-py
O trabalho faz parte do PPG em Computação Aplicada da Unisinos para disciplina e Analise de Desempenho. 
Aqui você encontrara uma abordagens de resolução usando algotimo de Levenshtein frequentemente utilizado para calcular a distância entre duas strings.

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
É possivel implementar a formula de Levensntein o zero usando uma função Python, para usar basta chamar a função passando os parametros, exemplo: [Levensnteins.py] (https://github.com/elielalbuquerque/analise-desempenho-py/blob/main/Levensntein.py)

## Cenario
Com base numa string de dados informada pelo usuario numa aplicação Python, desejamos compara-la com informações armazenadas em uma base e trazer a informaões que melhor representa.
  - Opção 1: Implementar algoritmo de Levenshtein na linguagem Puthon que frequentemente é utilizado para calcular a distância entre duas strings.
  - Opção 2: Importar biblioteca FuzzyWuzzy, assim como o pacote Levenshtein, uma função de razão que calcula a razão de similaridade de distância de Levenshtein padrão entre duas sequências.

### Objetivo
Comparar uma implementação do algoritmo de Levenshtein com uma biblioteca Fuzzywuzzy para resolver o problema de comparação de duas string.
  
# Analise de desempenho
Mediremos o número mínimo de edições que você precisa fazer para alterar uma sequência de uma string na outra. A tecnica utilizada para avaliação será a de simulação usando como criterio a precisão para comparação.

## Definição das métricas de desempenho
1. Essas edições podem ser inserções, exclusões ou substituições.
2. Também é possível calcular a razão de similaridade de Levenshtein com base na distância de Levenshtein. 
Isso pode ser feito usando a seguinte fórmula:

     (|a|+|b|)−leva,b(i,j)/|a|+|b)
     
Onde | a | e | b | são os comprimentos da sequência uma e sequência b respectivamente.
- Como parametro usaremos uma string com XXX caracteres para busca numa base com YYYY.

### Carga para teste de algoritmo
- Testaremos cargas de trabalho com string de 5, 10, 20 caracteres para busca numa base de 100 palavras. 

### Performance de metricas
- Testaremos uma acuracia minima de 95%
- Análise dos dados

### Analise do algoritmos


### Conclusões
Neste documento foi exeplificado como a correspondência por aproximada de strings e determinar o quão semelhantes são. Os exemplos apresentados aqui podem ser simples, mas são suficientes para ilustrar como lidar com vários casos do que um computador pensa serem strings incompatíveis atraves da correspondência de string difusa para mapear correspondentes a pesquisa de um sistema de turismo para recomendação. No entanto, a utilidade desta técnica pode ser expandida, não há limites para usos da correspondência difusa.
