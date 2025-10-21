
| ID | Descrição |
|---|---|
| **US01F** | 1. Validar que o e-mail informado corresponde a um usuário cadastrado no sistema |
| | 2. Validar se a senha informada corresponde à senha cadastrada para aquele e-mail. |
| | 3. Caso o e-mail ou a senha sejam inválidos, exibir uma mensagem de erro clara: "E-mail ou senha incorretos. Tente novamente." |
| **US02F** | 1. Validar que o e-mail informado corresponde a um usuário cadastrado no sistema. |
| | 2. Validar se a senha informada corresponde à senha cadastrada para aquele e-mail. |
| | 3. Caso o e-mail ou a senha sejam inválidos, exibir mensagem de erro clara: "E-mail ou senha incorretos. Tente novamente." |
| **US03F** | 1. Validar que título, autor e ano são obrigatórios no cadastro de livros. |
| | 2. Validar que o ISBN não esteja duplicado. |
| | 3. Permitir edição e exclusão de livros cadastrados. |
| **US04F** | 1. Validar que a busca retorna livros por título, autor ou ISBN. |
| | 2. Exibir mensagem clara caso nenhum livro seja encontrado. |
| **US05F** | 1. Validar que o usuário esteja ativo no sistema. |
| | 2. Validar se o livro esteja disponível para empréstimo. |
| | 3. Exibir mensagem de sucesso ao concluir empréstimo. |
| **US06F** | 1. Validar que o livro esteja vinculado a um empréstimo ativo. |
| | 2. Atualizar status do livro para "disponível" após devolução. |
| | 3. Exibir mensagem de confirmação da devolução. |
| **US07F** | 1. Validar que o usuário consiga visualizar todos os empréstimos passados e ativos. |
| | 2. Exibir data de empréstimo e data de devolução. |
| **US08F** | 1. Validar que a renovação só seja permitida antes da data de vencimento. |
| | 2. Atualizar a nova data de devolução automaticamente. |
| | 3. Exibir mensagem confirmando a renovação. |
| **US09F** | 1. Validar que o usuário consiga reservar apenas livros que estejam indisponíveis. |
| | 2. Notificar o usuário quando o livro reservado estiver disponível. |
| | 3. Exibir mensagem de confirmação da reserva. |
| **US10F** | 1. Validar que o sistema registre prazos de devolução para cada empréstimo. |
| | 2. Exibir alertas de proximidade de vencimento. |
| | 3. Calcular multas automaticamente para devoluções em atraso. |
| **US01FN** | 1. Validar que o sistema seja acessível em navegadores de desktop. |
| | 2. Validar que o sistema seja acessível em navegadores de dispositivos móveis (Android/iOS). |
| | 3. Validar que as telas mantenham responsividade e usabilidade em diferentes tamanhos de tela. |
| **US02FN** | 1. Validar que os menus principais sejam acessíveis em no máximo 2 cliques. |
| | 2. Validar que ícones e botões possuam identificação clara (texto ou ícone explicativo). |
| | 3. Realizar teste de usabilidade para verificar se o usuário consegue executar as funções sem treinamento. |
| **US03FN** | 1. Validar que as senhas estejam armazenadas de forma criptografada. |
| | 2. Validar que apenas usuários autorizados acessem informações restritas. |
| | 3. Validar que a comunicação de dados ocorra em ambiente seguro (HTTPS). |
| **US04FN** | 1. Validar que o tempo de resposta da busca seja inferior a 3 segundos em 90% das tentativas. |
| | 2. Validar que cadastro de novos usuários ou livros seja concluído em até 5 segundos. |
| **US05FN** | 1. Validar que o sistema realize backup automático diário do banco de dados. |
| | 2. Validar que os backups possam ser restaurados em caso de falhas. |
| | 3. Validar que o backup seja armazenado em local seguro e protegido contra perda de dados. |