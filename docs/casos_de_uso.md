## diagrama de casos de usos 

Usuário:
fazer login
devolucao de livros
reservar livros
verificar prazos

Bibliotecário:
controle de prazos e multas
emprestimo de livros
gerenciar acervo
renovar emprestimo
cadastrar usuario
verificar historico de emprestimo

## diagrama de classes 

**Classe: bibliotecario**
-idBibliotecario: int
-nome: string
 -telefone: string
 -email: string
 +addNovoLivro()
 +removerLivro()
 +atualizarInfosLivros()
 +processarEmprestimo()
+processarDevolucao()
* *Relacionamento com usuario: possui*

**Classe: livro**
 -titulo: string
 -codigo: string
 -autor: string
 -genero: string
 -anoPublicacao: int
 +emprestar(): void
 +devolver(): void
 +reservar(): void

**Classe: usuario**
 -idUsuario: string
 -nome: string
 -telefone: string
 -email: string
 -endereco: string
 +registrar()
 +atualizarInfos()
 +solicitarEmprestimo()
 +devolverLivro()
*Relacionamento com Emprestimo: possuir*

**Classe: Emprestimo**
 -dataEmprestimo: date
 -dataDevolucao: date
 -status: string
 +calcularMulta(): double
 +renovarEmprestimo(): void
 +finalizarEmprestimo(): void

**Relacionamentos:**
* `bibliotecario` **possui** `usuario`
* `livro` **está relacionado com** `Emprestimo` (implícito, geralmente por associação, mas o desenho mostra uma linha de associação simples)
* `usuario` **possui** `Emprestimo`