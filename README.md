Nosso site é dedicado à venda de astros celestes, e com isso surgiu a ideia do nome Celestia. Criamos uma logo com uma meia-lua e optamos por usar a cor azul escuro para estilizar o site e fizemos um esboço do layout no Figma para guiar nosso desenvolvimento.
Na parte superior do site, o header inclui a logo, uma barra de pesquisa, três ícones com imagens e um botão para adicionar produtos. Você pode navegar pelo site sem precisar de uma conta, porém, se quiser se cadastrar, há uma opção de registro onde são solicitadas informações como nome, e-mail e senha. Após isso, ao clicar em ‘cadastrar’, suas informações serão atualizadas e salvas no banco de dados.
No corpo do site, você encontrará os produtos à venda, com seus respectivos nomes, descrições, preços e um botão para adicioná-los ao carrinho. Ao clicar neste botão, uma mensagem confirmará que o produto foi adicionado ao carrinho. O ícone de carrinho no canto superior direito exibe todos os produtos adicionados, com a opção de removê-los. Neste mesmo modal, há um botão para finalizar a compra, que abrirá uma nova página onde você poderá inserir informações como nome completo, endereço, CEP, cidade e meio de pagamento para concluir a compra.
Para os administradores, há a opção de adicionar novos produtos ao catálogo. Ao clicar em ‘Adicionar Produto’ no canto superior direito, um modal é exibido solicitando o nome do produto, descrição e preço. Depois de preencher essas informações obrigatórias, ao clicar em ‘Adicionar ao Catálogo’, os dados do novo produto serão salvos no banco de dados.

Instruções para Configuração e Teste do Banco de Dados e APIs:
1. Acesse a pasta pelo Git Bash.
2. Execute `npm start`.
3. Para testar as APIs relacionadas ao cadastro de novos usuários:
Cadastrar Novo Usuário: POST para http://localhost:3009/cadastro/cadastrar
Listar Usuários: GET para http://localhost:3009/cadastro/listar
Editar Usuário: PUT para http://localhost:3009/cadastro/editar/:id
Deletar Usuário: DELETE para http://localhost:3009/cadastro/deletar/:id
4. Para o cadastro de novos produtos, substitua “cadastro” por “produtos” nos endpoints e ajuste as informações no "request body".
