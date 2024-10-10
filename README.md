# Algoritmos de Ordenação - AEDS I

Este repositório contém implementações de diversos algoritmos de ordenação, desenvolvidos para a disciplina de Algoritmos e Estruturas de Dados I (AEDS I).

## Algoritmos Implementados

1. **Bubble Sort**
   - O algoritmo de ordenação por bolha compara pares adjacentes de elementos e os troca se estiverem fora de ordem. Esse processo é repetido até que a lista esteja ordenada.

2. **Insertion Sort**
   - O algoritmo de inserção percorre a lista, ordenando os elementos à medida que os encontra, inserindo-os na posição correta em uma sublista já ordenada.

3. **Merge Sort**
   - O algoritmo de ordenação por mistura utiliza a estratégia "dividir para conquistar". Ele divide a lista em sublistas menores, ordena cada uma delas e depois as mescla para produzir a lista ordenada final.

4. **Quick Sort**
   - O algoritmo Quick Sort também segue o princípio "dividir para conquistar", selecionando um "pivô" e particionando a lista em duas partes: elementos menores que o pivô e maiores que o pivô, ordenando recursivamente essas partes.

5. **Selection Sort**
   - O algoritmo de seleção percorre a lista, selecionando o menor (ou maior) elemento e o movendo para a posição correta. Este processo é repetido até que a lista esteja completamente ordenada.

## Como Executar

Para executar qualquer um dos algoritmos, basta compilar e executar o arquivo correspondente. Os códigos estão organizados de forma simples, podendo ser facilmente adaptados e testados com diferentes conjuntos de dados.

```bash
# Exemplo de compilação e execução (dependendo do ambiente)
javac BubbleSort.java
java BubbleSort
