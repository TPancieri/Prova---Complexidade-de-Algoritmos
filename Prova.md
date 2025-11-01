# Prova → Complexidade de Algoritmos



## Versão Fácil

* O que significa a palavra complexidade quando falamos de um algoritmo? 

`Dentro do contexto de análise de assintótica de algoritmos, a palavra complexidade é utilizada para descrever o tempo e espaço/memória que um algoritmo precisa para ser executado conforme o tamanho da entrada aumenta`

* Qual é a diferença entre tempo de execução e uso de memória em um algoritmo?

`O tempo de execução é definido como a quantidade de tempo que o algortimo leva desde o inicío da sua execução até a entrega do seu output, ou seja, quanto tempo o algoritmo demora para rodar. Já o uso de memória diz respeito ao espaço que esse algoritmo ocupa dentro da memória durante seu processamento/execução`

* Para que serve a notação Big O (O-grande)?

`A Notação Big O avalia o comportamento de uma função em relação ao tamanho dos argumentos utilizados, basicamente, ela classifica algoritmos conforme ou seu tempo de execução ou requisitos de espaço considerando a variação nos dados de entrada`

* O que representa o termo n dentro da notação O(n)?

`Na notação Big O o termo n represena o tamanho da entrada/tamanho dos argumentos utilizados`

* Cite um exemplo de algoritmo com complexidade O(1).

`Um exemplo de algoritmo O(1) seria acesso a elementos de um array (vetor), como array[i]`

* Cite um exemplo de algoritmo com complexidade O(n).

`Um exemplo de algoritmo 0(n) seria uma busca sequencial em array (vetor)`

* Qual a complexidade de tempo do algoritmo de Bubble Sort?

`O algoritmo de Bubble Sort tem complexidade de O(n²)`

* Qual a complexidade de tempo do algoritmo de Busca Linear?

`Algoritmos de busca linear tem complexidade de O(n)`

* O que significa dizer que um algoritmo tem complexidade O(log n)?

`Algortimos com complexidade O(log n) indicam algoritmos que tem tempo de execução que de forma mais lenta, costumam ser algortimos similares a busca binária, que dividem problemas pela metade.`

* Qual a diferença entre melhor caso e pior caso de um algoritmo?

`O Melhor caso de um algoritmo é considerado como a execução mais rápida possível, quando se encontra o que precisa na primeira iteração.`
`O pior caso de um algortimo é considerado como a execução mais lenta possível, quando se encontra o que precisa na última iteração.`

* Em qual tipo de problema geralmente encontramos complexidades exponenciais (O(2ⁿ))?

`Problemas que tem complexidades exponenciais costumam ser problemas resolvidos com força bruta ou problemas combinatórios`

* O que é complexidade polinomial?

`As complexidades polinomiais são complexidades que crescem como uma potência de n, como  n², n³.`

* Qual a complexidade do Merge Sort no pior caso?

`Considerando o pior caso possível, um algoritmo de Merge Sort terá complexidade  de O (n log n)`

* Em um algoritmo que possui dois loops for aninhados, qual costuma ser sua complexidade?

`Um algoritmo de dois loops (for) aninhados terá complexidade de O(n²)`

* Por que os programadores buscam algoritmos com menor complexidade?

`Programadores buscam algortimos com menor complexidade pois eles são mais eficientes, economizando ambos tempo e recursos, o que é essencial em situações onde a entrada é grande`

* Um algoritmo que analisa cada elemento de uma lista apenas uma vez é O(n). Isso é considerado eficiente?

`Um algoritmo de complexidade O(n) é sim, considerado eficiente, pois esse tipo de algoritmo cresce linearmente`

* A notação Θ (teta) indica o quê em relação ao crescimento da função?

`A Notação Teta mostra o limite superior e o limite inferior de uma função, indicando o seu crescimento exato`

* Qual é a complexidade de tempo de um algoritmo que executa três loops aninhados sobre n elementos?

`A complexidade de um algoritmo que executa três loops aninhados sobre n, tem complexidade O(n³)`

* O que significa dizer que um algoritmo é in-place?

`Um algoritmo in-place seria algo como uma ordenação que é feita no próprio vetor, algo que não uso memória extra significativa`

* Cite um exemplo de estrutura de dados que pode melhorar a eficiência de um algoritmo.

` Uma estrutura de dados que ajuda a melhorar a eficiência de um algoritmo são as tabelas hash, estruturas como ela, as heaps e as árvores balanceadas aumenta a eficiência de busca e da ordenação `






 

## Versão Difícil

* Explique por que analisamos a complexidade de tempo em função do tamanho da entrada (n).

  
* Dê um exemplo de algoritmo cuja complexidade muda dependendo da escolha da estrutura de dados.

  
* Mostre como se calcula a complexidade assintótica da função f(n) = 4n² + 3n + 10.

  
* Prove que O(n² + n) = O(n²).

  
* Qual é a diferença entre as notações O(n) e Ω(n) em termos de limites de crescimento?

  
* Escreva a relação de recorrência do algoritmo Merge Sort e resolva-a usando o Teorema Mestre.

  
* Mostre um exemplo de algoritmo cuja complexidade é O(n log n) e explique por que esse comportamento ocorre.

  
* Explique o que significa o custo amortizado em operações de uma tabela hash.

  
* Dado um algoritmo com complexidade T(n) = 2T(n/2) + n, determine sua ordem de crescimento.

  
* Compare o desempenho de algoritmos com complexidade O(n log n) e O(n²) para valores grandes de n.

  
* Um algoritmo recursivo é definido por T(n) = T(n-1) + n. Qual é sua complexidade aproximada?

  
* Qual o impacto da escolha de pivô na complexidade média do Quick Sort?

  
* Explique o conceito de limite inferior (lower bound) para algoritmos de ordenação.

  
* Dê um exemplo de problema NP-difícil e explique o que isso significa em termos de complexidade.

  
* Por que não é possível encontrar algoritmos polinomiais conhecidos para resolver todos os problemas NP-completos?

  
* Mostre um exemplo prático em que a análise de complexidade pode orientar o design de software.

  
* Explique a diferença entre complexidade no caso médio e complexidade no pior caso.

  
* Um algoritmo que compara todos os pares de elementos em uma lista de tamanho n possui qual complexidade?

  
* Mostre por que f(n) = n! cresce mais rapidamente do que f(n) = 2ⁿ.

  
* Se um algoritmo tem tempo de execução T(n) = n² log n + 5n, qual é sua complexidade em notação O?
