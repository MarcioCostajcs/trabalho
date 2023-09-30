                        Trabalho de Implementação do tipo de dado abstrato Set.

Explicação da Classe ConjuntoAbstrato:
__init__(self): O construtor da classe ConjuntoAbstrato inicializa o conjunto vazio usando a estrutura de dados set do Python.

inserir(self, elemento): Este método permite inserir um elemento no conjunto usando o método add() da estrutura de dados set.

remover(self, elemento): Este método permite remover um elemento do conjunto, desde que o elemento esteja presente no conjunto.

consultar(self, elemento): Este método verifica se um elemento está presente no conjunto, retornando True se estiver e False caso contrário.

uniao(self, outro_conjunto): Este método calcula a união entre o conjunto atual e outro conjunto fornecido como argumento, criando um novo conjunto e preenchendo-o com os elementos únicos de ambos os conjuntos.

intersecao(self, outro_conjunto): Este método calcula a interseção entre o conjunto atual e outro conjunto fornecido como argumento, criando um novo conjunto e preenchendo-o com os elementos que são comuns a ambos os conjuntos.

diferenca(self, outro_conjunto): Este método calcula a diferença entre o conjunto atual e outro conjunto fornecido como argumento, criando um novo conjunto e preenchendo-o com os elementos que estão no conjunto atual, mas não no outro conjunto.

elementos(self): Este método retorna os elementos presentes no conjunto. 

Criamos dois conjuntos conjunto_A e conjunto_B usando a classe ConjuntoAbstrato e inserimos elementos neles.

Removemos o elemento 2 do conjunto_A usando o método remover.

Calculamos a união, interseção e diferença entre conjunto_A e conjunto_B usando os métodos uniao, intersecao e diferenca da classe ConjuntoAbstrato.

Finalmente, imprimimos os elementos dos conjuntos e os resultados das operações.
