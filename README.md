# Gerenciamento-de-Biblioteca

Explicação do Código:

# Classe Livro:

Esta classe representa um livro na biblioteca.

Atributos:
#
- titulo: Título do livro.
- autor: Autor do livro.
- ano: Ano de publicação do livro.
- disponivel: Indica se o livro está disponível para empréstimo.
- 
Métodos:

- emprestar(): Marca o livro como emprestado, se estiver disponível.
- devolver(): Marca o livro como devolvido.
 
# Classe Usuario:

Esta classe representa um usuário da biblioteca.

Atributos:
#
nome: Nome do usuário.
emprestimos: Dicionário para manter o registro de livros emprestados pelo usuário.
Métodos:
emprestar_livro(livro, data_emprestimo): Permite ao usuário emprestar um livro, registrando a data de empréstimo.
devolver_livro(livro, data_devolucao): Permite ao usuário devolver um livro, registrando a data de devolução e calculando multa, se houver atraso.
Classe Biblioteca:

Esta classe representa a biblioteca.
Atributos:
nome: Nome da biblioteca.
catalogo: Dicionário para armazenar os livros disponíveis na biblioteca.
Métodos:
adicionar_livro(livro): Adiciona um livro ao catálogo da biblioteca.
remover_livro(titulo): Remove um livro do catálogo da biblioteca.
pesquisar_livro(titulo): Pesquisa um livro no catálogo e exibe suas informações.
listar_livros(): Lista todos os livros disponíveis na biblioteca.
Exemplo de Uso:

Cria uma instância da Biblioteca.
Adiciona livros ao catálogo da biblioteca.
Cria instâncias de Usuario.
Realiza empréstimos e devoluções de livros pelos usuários.
Link para o Projeto no Google Colab:

Você pode acessar e executar o projeto diretamente no Google Colab através deste [Link.](https://colab.research.google.com/drive/1mgkBiuMjcCpdiAlsy0ifShwkrhjx0EtG?usp=sharing)

##

Com esse código, os usuários podem interagir com a biblioteca, emprestando e devolvendo livros, enquanto o sistema controla o status dos livros e calcula multas por atraso na devolução. O código está estruturado de forma modular e organizada, facilitando a compreensão e a manutenção.
