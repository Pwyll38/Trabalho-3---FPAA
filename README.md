## Implementação  do  Algoritmo  para  Caminho  Hamiltoniano em Python

### Como executar o projeto

    Instalar o python na máquina

    Navegar, pelo terminal, até a pasta do projeto

    Inserir o grafo desejado na lista na linha 54

    Executar o arquivo com "python3 main.py"

### Descrição do projeto 

Um caminho hamiltoniano em grafos é um caminho em que todos vértices são visitados exatamente uma vez. Assim, um ciclo hamiltoniano é um caminho hamiltoniano em que o ultimo e o primeiro vértice são conectados, formando um ciclo. 

#### Função __init__:

Inicializa a classe Graph, montanto um grafo com os vertices entrados como parametro.

#### Função is_safe_to_add: 

Verifica se o vértice V dado como parâmetro pode ser adicionado ao ciclo hamiltoniano. 

#### Função hamiltonian_cycle_util: 

O objetivo dessa função recursiva é caminhar por todos os vértices possíveis, retornando a recursividade se todos vértices forem visitados ou não há mais vértices que podem ser adicionados ao caminho. 

#### Função find_hamiltonian_cycle:

Inicia a recursividade da função hamiltonian_cycle_uti. Também é responsável por determinar se o grafo é hamiltoniano ou não.

#### Função print_solution: 

Imprime os resultados do código. 

### Relatório técnico 

#### Complexidade computacional

O problema de encontrar um caminho hamiltoniano é considerado NP-Completo. Ou seja, esse problema pode ser verificado em tempo polimonial, podendo ser reduzivel em tempo polimonial. 

#### 

fontes: https://www.geeksforgeeks.org/hamiltonian-path-cycle-in-python/

https://www.geeksforgeeks.org/introduction-to-np-completeness/