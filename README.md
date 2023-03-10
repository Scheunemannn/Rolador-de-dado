Um rolador de dados criado com HTML, CSS e JavaScript.

O algoritmo, basicamente gera um numero aleatório de 1 até 6, utilizando as funções Math.random e Math.round e com base neste número gerado, ele troca a propriedade SRC da tag img inclusa no arquivo HTML dependendo do resultado do número aleatório gerado.
A função Math.random gera um número aleatório de 0 a 1, por conta disso, o algoritmo multiplica este número por 5, gerando agora números de 0 a 5. E por fim, define que este número gerado deve ser somado a 1, o que transforma o resultado minimo em 1 e o máximo em 6.
