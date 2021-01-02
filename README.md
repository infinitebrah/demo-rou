# Feature Branch é uma branch de testes que você modifica e depois funde(merge) com a master branch

# PR(Pull Request) Função semelhante ao comando Diff que retorna todas as modificações feitas na feature branch e às compara com a master branch e te permite comentar as modificações realizadas.

# Pull | Função semelhante ao push, mas serve para selar o merge. *Feature Branches são desnecessárias após merge(fundir as branches).*

# Comandos Git
git clone | Clonar repositório.
#
git add | Adiciona um arquivo para a Staging Area.
#
git commit | Enviar o arquivo para o sistema de controle de versão(Git).
#
git commit -m | Adiciona um comentário na timeline '-m' stands for message.
#
git push | Empurra as mudanças feitas para um repositório remoto
#
ls | grep - Pesquisa por keyword no repositório
#
ssh-keygen -t rsa -b 4096 -C <email> | gera uma key
#
git remote add origin <link repositório> | Adiciona rep local para rep remoto
#
git push origin master | Cria um novo repositório
#
git push -u | Mesma função do origin master, mas push origin master precisa vir primeiro.
#
git brench | retorna todos os branches do repositório
#
git check out <branch> | troca de branch
#
git check out -b <branch> | cria um novo branch
#
git status | retorna todos os arquivos modificados
