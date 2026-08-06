https://drive.google.com/file/d/1KG9QRQhPqUSKHG0BXCsuQopamk2GlH7r/view?usp=sharing

Utilizei <<include>> nas 3 elipses que necessitavam do caso Identificar Leitor, dessa forma evitando ter que repeti-lo para todas elas. É importante utilizar <<include>> para otimizar o projeto, por exemplo, se for necessário alterar um caso incluído só é preciso mudá-lo em 1 único ponto e não em todos os casos que necessitam dele.

Utilizei <<extend>> na elipse Reservar livro ligada ao caso Consultar acervo, pois é opcional que ao consultar o acervo o usuário reserve um livro.

Criei o ator Usuário ligando-o aos atores Leitor e Bibliotecário, e a partir do ator Usuário criei um novo relacionamento para o caso Consultar Acervo, porque tanto o Leitor quanto o Bibliotecário podem querer consultar o acervo, e como herdam os casos do ator Usuário isso otimiza o diagrama e o projeto como um todo.
