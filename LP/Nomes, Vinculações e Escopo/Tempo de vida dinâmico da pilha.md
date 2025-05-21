Categoria dinâmicas da pilha – O espaço de memória é
criado quando ocorrer (posição) a declaração da variável. (Código associado a declaração é executado) Se escalar (simples), todos os atributos, com exceção ao endereço, são estaticamente delimitados Exemplo: Variáveis locais em subprogramas (funções) em C e métodos Java
Vantagem: 
- Permite recursão; conserva armazenamento
Desvantagens:
- Elevada alocação e desalocação
- Subprogramas não podem ser sensíveis ao passado (static)
- Referências ineficientes (endereçamento indireto)