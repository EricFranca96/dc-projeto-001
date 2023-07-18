# dc-projeto-001

01 - Verificar que existe duas branch fixas, main( produção), homologacao (ambiente parecido com o de produção, mais é o de teste).
![image](https://github.com/EricFranca96/dc-projeto-001/assets/72056638/a7b14f95-dc59-4e6a-87b4-d11fe9ccc6ac)

02 - O Fluxo é sempre Clonar de homologação, ai depois mandamos pra main.
    - O passo aqui é dar um git clone de homologacao ou dar um git pull origin homologacao.
    - É importante que as branch criadas sejam criadas apartir de homologacao.

03 - Depois de clonar a homologacao 
   - Criar uma nova branch, git checkout 001-criando_branch
   - fazer qualquer alteraação e enviar pra essa branch, so que remoto.
   - Abrir o pe da branch que vc criou, pra branch de homologacao. 


------------------------------------------------------------------------------------

CRIANDO NOVAS BRANCH 

01 - (EX: git checkout 003-branch).
02 - Melhorar algo no codigo para poder validar no git bash.
03 - git status
04 - git add .
05 - git commit -m "Descrição do commit"
06 - git push --set-upstream origin 002-branch
07 - No site do GitHub ir no projeto, e mandar compare & pull request
08 - (EX: Dar um PR para homologacao. )