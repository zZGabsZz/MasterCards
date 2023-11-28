MasterCards
Descrição do Projeto:
O Projeto é basicamente a criação de um site simples de se utilizar e de fácil acesso, para que qualquer pessoas com interese em vender alguma de suas cartas posso utilizar o site para essa funcionalidade, onde nosso site possui capacidade para atender a 4 tipos de card games existentes ( Pokémon, Yu-Gi-OH, Magic e One Piece).

Passos para utilização do site:
!IMPORTANTE!- Quando for utilizar o site não esqueça de colocar o nome do banco de dados como "registro". Para que assim o site  possa funcionar corretamente. 
1- Baixe o arquivo .rar e coloque ele dentro da pasta xampp, e extraia os arquivos ali.
2- Abra o xampp e inicie o apache e o mysql.
3- Em seu navegador pesquise Localhost/xampp/Mastercard.html (o xampp pode ser alterado pelo nome que a pasta tiver)
4- Agora em dentro do site basta clicar no título do card game desejado e proseguir para proxima pagina, clicar em adicionar produto e cadastrar seu produto.
5- Depois basta voltar até a pagina de produtos e ali estara os dados do produto registrado (id, nome, preço).
6- Dentro da tabela também existira duas opções, onde o botão amarelo serve para fazer uma alteração no registro do produto e o vermelho serve para excluir o registro do produto.
7- Pronto, agora você já sabe utilizar o site do MasterCards.

O Banco de Dados:
O banco de dados é algo bem simples, ele conta com 4 tabelas, uma para cada tipo de card game, onde cada tabela possui 3 colunas (nome, preco e id) que são os dados mostrados no site, e ele está divido em 4 tabelas para que não haja confusão na hora do php buscar as informações expecificas de cada card game e mandar para tabela correta, tornando assim a organização melhor.
