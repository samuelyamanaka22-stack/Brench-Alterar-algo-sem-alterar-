print('Versão 1 do projeto')
print('Versão 2, feita na branch!')
-------------------------------------------------------------------------------
Comandos
Crie um arquivo chamado app.py clicando no ícone de "Novo Arquivo" no VS Code e digite: print('Versão 1 do projeto'). Salve o arquivo.

No terminal do VS Code, inicie o Git e salve essa primeira versão:

Bash
git init
git add app.py
git commit -m "Primeiro commit: projeto base"
3. Criar a branch e fazer a alteração

No terminal, crie e mude para a nova branch com este comando (o -b é um atalho que faz as duas coisas ao mesmo tempo):

Bash
git checkout -b feature/novo-codigo
Volte no arquivo app.py no VS Code, adicione uma segunda linha: print('Versão 2, feita na branch!') e salve.

No terminal, registre essa novidade na sua branch:

Bash
git add app.py
git commit -m "Segundo commit: alteracao na branch"
Dica extra do VS Code: Em vez de digitar comandos para trocar de branch, olhe para o canto inferior esquerdo da tela do VS Code. Você verá o nome da branch atual (feature/novo-codigo). Se você clicar lá, abrirá um menu no topo da tela permitindo que você troque para a master com apenas um clique!
----------------------------------------------------------------------------
trocar de brench
Para voltar para a sua branch original:

Bash
--------------------
git checkout master
--------------------
Para ir novamente para a branch que você acabou de criar:

Bash
--------------------------------
git checkout feature/novo-codigo
---------------------------------



