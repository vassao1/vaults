A memória é um dos principais componentes do computador. Ela serve para armazenar os códigos dos programas a serem executados, bem como dos dados manipulados por eles.
Uma memória é nada mais que um conjunto de *palavras*. Cada palavra pode conter um dado a ser manipulado ou uma instrução a ser executada. Cada palavra tem seu *endereço único*, do qual é referenciado para escritas e leituras da palavra, pois quando deseja-se fazer a leitura de uma palavra da memória, é expressamente necessário indicar o seu endereço.
	Pense na memória como um GRANDE vetor, onde as palavras são os dados e o endereço o índice do vetor.
O *tamanho* de uma memória diz respeito ao número total de palavras que pode ser armazenado, enquanto a *largura* diz respeito ao número de bits que cada palavra possui (geralmente a largura é o mesmo tamanho da arquitetura, 16 bits, 32 bits, etc...). Diferentes memórias terão diferentes tamanhos e larguras, influenciando na capacidade total e custo.
As memórias podem ser classificadas em 3 critérios:
- Volatilidade - Mantém o conteúdo caso a alimentação de energia seja desligada?
	- Memória volátil: Não mantém o conteúdo quando a alimentação é desligada (RAM)
	- Memória não-volátil: Mantém o conteúdo quando a alimentação é desligada (ROM)
- Operação - Pode escrever também?
	- Somente leitura: permite somente a leitura dos dados (ROM)
	- Permite a escrita: permite ambas as operações (RAM)
- Armazenamento - Mantém o conteúdo mesmo com a alimentação de energia?
	- Armazenamento dinâmico: Dados se apagam com o tempo, é necessário um refresh (basicamente reescrita dos dados) para não os perder.
	- Armazenamento estático: Dados se mantém indefinidamente.
Atualmente, até mesmo memórias ROM tem capacidade de escrita, porém, a diferença entre a RAM e a ROM mora no fato que na RAM, operações de leitura e escrita tem velocidades similares, enquanto na ROM, as leituras são rápidas, porém a escrita é mais lenta.