Aqui estão os passos para usar o *Git Bash*.

1) Para criar um novo repositório local, digite: "git init".

2) Para adicionar novos arquivos ao repositório e deixa-los em *staging* digite: "git add <*nome dos arquivos ou um *.* para adicionar todos os arquivos em *staging*>".

3) Para realizar um *commit* digite: "git commit -m "-" <*nome ou mensagem para este commit*> ".

4) Se quiser ou for necessário mudar o nome da *branch*, digite: "git branch -M "-" <*novo nome da *branch * em questão normalmente é renomeado para main*> ".

5) Agora já logado no site do *GitHub*, crie um repositório e configure segundo necessidades.

6) Para passar o repositório local (que está na máquina) para um repositório na plataforma do *GitHub*, será necessário fazer o passo *5* e copiar o link do repositório criado, e em seguida no *Git Bash* digite: "git remote add origin <*link do repositório*>. 
//*LEMBRANDO QUE PARA COLAR NO GIT BASH E NECESSÁRIO USAR O 'INSERT'*//

//*ORIGIN É O NOME USADO PARA REFERENCIAR O NOSSO REPOSITÓRIO*//

7) Para enviar nossos arquivos/pastas pela primeira vez para o *GitHub* digite: "git push -u origin <*nome da *Branch*>"
//*QUANDO FOR ENVIAR ALTERAÇÕES, DIGITAR O MESMO CÓDIGO ACIMA PORÉM SEM O -u*//

8) Para fazer *log-off* de uma *branch*, bastar digitar: "git checkout".
//*É POSSÍVEL CRIAR UMA BRANCH APARTIR DESTE CODIGO INCREMENTANDO O COMANDO <-b "-" < nome da branch>*//

//*É POSSÍVEL NAVEGAR ENTRE AS branch's, BASTA FAZER O PASSO 8 E NO FINAL DIGITAR O NOME DA branch DESEJADA*//

//*PARA COLOCAR A NOVA BRANCH EM stading E FAZER O commit, É SO REFAZER OS PASSOS ANTERIORES*//

9) Para *mesclar* uma *branch* com a *branch* principal precisamos estar na *branch* principal e em seguida, digite: git merge < *nome da branch que deseja mesclar com a principal*>.
//*DEPOIS DISSO AINDA E NECESSÁRIO FAZER O push PARA SUBIR TUDO PRO GitHub*//

10) Para clonar um repositório do *GitHub* e necessário ir em *code* copiar o link e em seguida ir no *Git Bash* e digitar: "git clone < *link do repositório copiado*>".

11) Se ocorrer alguma alteração no código do *GitHub* e quiser atualizar em sua máquina, entre na *branch* do referido código através do *Git Bash*, em seguida basta digitar: "git pull".

12) É possível mandar solicitações de *pull* para outras pessoas puxarem um código que você tenha alterado através da própria plataforma do *GitHub*, segue os passos: "Entre no repositório já atualizado com a alteração, clique em *comtribute > open pull request > create pull request*, em seguida escreva um título e uma prévia do que foi alterado no código com intuito de esclarecer para o destinatário o sentido da alteração, em seguida clique em *create pull request*.

13) Para aceitar *pull request* enviadas de outras pessoas para seus códigos, basta ir no repositório na plataforma do *GitHub*, clicar em *pull request*, clicar na solitação que deseja analizar/aceitar, se for aceitar a alteração em questão, basta clicar em *merge pull request*, se não for o caso, mais abaixo há uma caixa de escrita na qual pode se colocar um comentário para o solicitante explicando o motivo do porquê não aceitar a alteração, após a escrita, basta clicar em *close pull request*