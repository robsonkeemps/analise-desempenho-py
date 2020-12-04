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
   - Analise do numero de etapas
   - Análise de nivel de acertividade
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
Com base numa string de dados informada numa aplicação Python, desejamos compara-la com informações armazenadas em uma base e trazer a informaões que melhor representa.
  - Opção 1: Implementar algoritmo de Levenshtein na linguagem Puthon que frequentemente é utilizado para calcular a distância entre duas strings.
  - Opção 2: Importar biblioteca FuzzyWuzzy, assim como o pacote Levenshtein, uma função de razão que calcula a razão de similaridade de distância de Levenshtein padrão entre duas sequências.
  
# Analise de desempenho
Mediremos o número mínimo de edições que você precisa fazer para alterar uma sequência de uma string na outra. A tecnica utilizada para avaliação será a de simulação usando como criterio a precisão para comparação.

## Definição das métricas de desempenho
1. Essas edições podem ser inserções, exclusões ou substituições.
2. Também é possível calcular a razão de similaridade de Levenshtein com base na distância de Levenshtein. 
Isso pode ser feito usando a seguinte fórmula:

     (|a|+|b|)−leva,b(i,j)/|a|+|b)
     
Onde | a | e | b | são os comprimentos da sequência uma e sequência b respectivamente.

### Carga para teste de algoritmo

