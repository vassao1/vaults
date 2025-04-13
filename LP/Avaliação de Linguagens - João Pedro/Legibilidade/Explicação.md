- **Structs** podem ser retornadas diretamente por uma função, permitindo a cópia completa e segura de um conjunto de dados.
    
- **Arrays** não podem ser retornados por valor de forma direta devido à forma como são tratados na linguagem C/C++ e à falta de uma semântica de cópia para arrays.
    
- **Contornar a limitação dos arrays:** Ao encapsular um array dentro de uma struct, você efetivamente possibilita o retorno do array "indiretamente" por meio da struct, aproveitando a capacidade de retorno por valor das structs.