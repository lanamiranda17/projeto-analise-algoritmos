# Algorithmic Problem Solving

Coleção de soluções em C++ para problemas clássicos de algoritmos e
estruturas de dados. O repositório demonstra a aplicação prática de
estratégias de projeto de algoritmos, análise de problemas e otimização de
complexidade.

## Conteúdos abordados

### [`fundamentos-algoritmicos/`](./fundamentos-algoritmicos/)

Fundamentos de algoritmos eficientes, com foco em ordenação, busca e divisão
e conquista:

- **Divisão e conquista**
  - Merge Sort e contagem de inversões;
  - busca binária;
  - subarray de soma máxima.
- **Ordenação**
  - Radix Sort;
  - Counting Sort;
  - ordenação por intercâmbio.
- **Técnicas complementares**
  - algoritmo de Kadane;
  - tratamento de empates e critérios de seleção;
  - contagem de frequências após a ordenação.

Problemas implementados:

| Problema | Principais conceitos |
| --- | --- |
| [`flip-sort`](./fundamentos-algoritmicos/flip-sort/) | Merge Sort, inversões e divisão e conquista |
| [`gnomos`](./fundamentos-algoritmicos/gnomos/) | Busca binária e classificação por faixas |
| [`jride`](./fundamentos-algoritmicos/jride/) | Subarray máximo, Kadane e divisão e conquista |
| [`sbank`](./fundamentos-algoritmicos/sbank/) | Radix Sort, Counting Sort e agrupamento |

### [`algoritmos-avancados/`](./algoritmos-avancados/)

Estratégias avançadas de otimização combinatória e resolução de problemas em
grafos:

- **Programação dinâmica**
  - mochila 0/1;
  - programação dinâmica em intervalos;
  - otimização de custo e valor.
- **Algoritmos gulosos**
  - construção e reconstrução de árvores de Huffman;
  - seleção de menores pesos com min-heap.
- **Grafos**
  - Dijkstra;
  - modelagem de estados;
  - restrições de paridade em caminhos mínimos.

Problemas implementados:

| Problema | Principais conceitos |
| --- | --- |
| [`barras`](./algoritmos-avancados/barras/) | Programação dinâmica em intervalos |
| [`invertendo-huffman`](./algoritmos-avancados/invertendo-huffman/) | Algoritmo guloso, Huffman e min-heap |
| [`mania-de-par`](./algoritmos-avancados/mania-de-par/) | Grafos, Dijkstra e estados de paridade |
| [`supersale`](./algoritmos-avancados/supersale/) | Programação dinâmica e mochila 0/1 |

## Organização dos problemas

Cada diretório de problema contém, quando aplicável:

- implementação em C++;
- enunciado original em HTML;
- casos de entrada (`.in`);
- saídas esperadas (`.out`);
- imagens utilizadas na documentação do problema.

Os enunciados documentam as restrições, o formato de entrada e saída e os
critérios de desempate considerados nas soluções.

## Competências demonstradas

- decomposição de problemas e escolha de estratégias algorítmicas;
- análise de custo de tempo e espaço;
- implementação de soluções eficientes em C++;
- uso de recursão, estruturas lineares, filas de prioridade e tabelas de DP;
- modelagem de problemas como intervalos, estados e grafos;
- validação por casos de teste reproduzíveis.

## Como executar

As soluções são programas independentes. Para compilar e executar uma delas:

```bash
g++ caminho/para/solucao.cpp -o solucao
./solucao < caminho/para/01.in
```

Por exemplo:

```bash
g++ fundamentos-algoritmicos/flip-sort/flip_sort.cpp -o flip-sort
./flip-sort < fundamentos-algoritmicos/flip-sort/01.in
```

## Contexto

Este projeto reúne implementações desenvolvidas durante o estudo de projeto e
análise de algoritmos, organizadas como uma base de referência para problemas
clássicos de programação competitiva e desenvolvimento de soluções eficientes.
