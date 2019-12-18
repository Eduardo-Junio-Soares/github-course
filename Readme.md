AULA GITHUB	

Lista de comandos:

Git status = mostra o status que o arquivo se encontra (untracked,
unmodified, modified, stagged)

Git add = adiciona o arquivo ao git

git commit -m "" = adiciona um comentários especifico daquela versão

git commit -am "" = adiciona comentário sem precisar do comando "git add" antes (valido somente para arquivos que já foram adicionados)

git log = mostra a identificação do arquivo, autor da modificaçãom, a data e uma mensagem pro commit

git log --decorate = mostra mais algumas informações

git log --author="Edu" = mostra todas as modificações feitas pelo autor que contenha o nome "Edu"

git shortlog = mostra em ordem alfabetica quais foram os autores, quantos commit eles fizeram e os commits

git shortlog -sn = mostra somente os nomes dos autores

git log --graph**

rash = identificador do arquivo

git show = ao adicionar a rash nesse comando é possivel ver as modificações feitas no arquivo

comando que ve as modificações antes de enviar e fazer o commit;

git diff  

git diff --name-only = mostra somente o nome do arquivo que foi modificado

git checkout nomeDoArquivo = permite desfazer as modificações feitas

git reset HEAD nomeDoArquivo - tira o arquivo do status stagged e coloca como modified

gir reset --soft rash = exclui o commit feito e retorna o arquivo para stagged

gir reset --mixed rash = exclui o commit e retorna o arquivo para modified

gir reset --hard rash = Ignora a existencia do commit e tudo que foi feito nele

colocar sempre em uma rash antes da que vc quer excluir.

como subir modificações para o repositorio remoto:

git push origin master

Criando um Branch

git checkout -b 'NomeDobranch'

git branch - mostra os branchs existentes no arquivo

git checkout "Nome do branch" - alterna entre as branchs

git branch -D nome da branch - deletar a branch




