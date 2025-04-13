O ciclo BDE define o comportamento da [[UC]], a partir do momento que o computador é ligado, a UC da CPU começa a realizar o ciclo BDE.
Mas do que se trata o ciclo BDE?
Juntamente com a memória, é o que torna o modelo de Von Neumann de propósito geral, pois desempenha a execução de diferentes programas no computador. O ciclo BDE é o ciclo de busca, decodificação e execução da instrução.
## Visão simplificada
No primeiro passo, o passo de busca, a UC envia para a memória o endereço da próxima instrução e solicita a leitura do mesmo, em resposta, a memória retorna para a UC a instrução lida.
No passo de decodificação, a UC interpreta a instrução para encontrar o endereço dos operandos e qual é a próxima operação necessária, assim configurando a ULA para essa operação. Logo após, a UC envia para a memória o endereço dos operandos necessários e a memória retorna os mesmos lidos direto para a ULA, sendo repetido quantas vezes necessárias por operando conforme a operação a ser feita.
Após a execução do programa na ULA, a UC envia para a memória uma solicitação de escrita do resultado, enviando um endereço de destino.
Para concluir, a ULA envia o resultado direto para a memória e assim se repete o ciclo de BDE.
Vale ressaltar que para o ciclo BDE funcionar, a UC conta com registradores de uso dedicado, sendo eles o [[PC]] e o [[IR]].
## Visão detalhada
No primeiro passo, a busca da instrução, a UC envia o endereço de instrução armazenado no PC para a memória, solicitando a leitura do conteúdo. Em resposta, a memória retorna a próxima instrução a ser executada, que é armazenada no IR.
No segundo passo, a decodificação da instrução, a UC quebra o conteúdo armazenado no IR em partes, sendo elas geralmente:
- Os endereços dos operandos armazenados no banco de registradores;
- O endereço de escrita do resultado na memória.
- O código de função a ser executado pela ULA.
Após isso, no terceiro passo, a UC solicita ao banco de registradores a leitura dos operandos, então os operandos armazenados no banco de registradores são enviados para as entradas de dados da ULA, junto da função a ser desempenhada pela ULA, enviada pelo IR dentro da UC.
Finalizando, a UC envia para a memória uma solicitação de escrita na posição endereçada no IR, ao mesmo tempo, a ULA envia o resultado calculado para a memória.