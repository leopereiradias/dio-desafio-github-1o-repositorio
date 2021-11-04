# Anotações curso Git ou GitHub

## Comandos de Terminal

### Windows:
cd - Entrar no diretório
cd .. - Voltar um diretório
dir - Listar arquivos e diretórios
mkdir - Criar arquivo/diretório
del / rmdir - Deletar arquivo/diretório
cls - Limpar terminal

### Unix:
cd - Entrar no diretório
cd ../ - Voltar um diretório
ls - Listar arquivos e diretórios
mkdir - Criar arquivo/diretório
rm -rf - Deletar arquivo/diretório
clear / ctrl+l - Limpar terminal

## Comandos de Configurações
git config —list - Lista todas as suas configurações atuais;
git config —global user.name "seu-nome" - Altera seu nome (coloque o mesmo do github);
git config —global user.email "seu-email" - Altera seu email (coloque o mesmo do github);

## Comandos do dia-a-dia
git clone https://link_do_repositorio - Clona um repositório do github para a sua máquina;
git init - Inicia um repositório no projeto em que está trabalhando localmente;
git status - Mostra o status atual dos arquivos do projeto;
git add . - Adiciona todos os arquivos para ser commitado;
git reset - Desfaz todos os arquivos adicionados que enviou para ser commitado;
git commit -m "Texto do commit" - Realiza o commit dos arquivos adicionados;
git commit —amend -m "Novo texto do commit" - Edita a mensagem do último commit;
git reset ~HEAD - Desfaz seu último commit;
git revert HEAD - Adiciona um novo commit que reverterá o último commit realizado;
git remote -v - Lista as configurações de repositório do projeto;
git remote add origin https://link_do_repositorio - Adiciona o repositório do github relacionado ao projeto em que você está trabalhando;
git pull origin master - puxa as informações do repositório no github para a sua máquina;
git push origin master - Envia seus últimos commits para o repositório no github;

## Comandos para lidar com stash e branchs
git stash save "descricao" - Adiciona seus arquivos em um stash;
git stash list - Lista o array do stash;
git stash pop "indice_array" - Move os itens do stash para sua branch atual;
git stash clear - Limpa o stash;
git branch - Lista todas as branchs do projeto;
git branch -m "nome_branch" - Cria uma nova branch;
git branch -m "nome_antigo" "novo_nome" - Renomeia a branch;
git checkout nome_da_branch - Transitar entre as branchs;
git checkout -b nome_da_branch - Cria e muda para a branch nova;
git branch -d nome_da_branch - Deleta uma branch;
git merge nome_da_branch - Faz a união da branch que você está com a informada
git rm —cached -r nome_do_diretorio - Remover diretório somente do git

## Comandos para lidar com arquivos e diretórios
git rm nome_do_arquivo - Remover arquivo do repositório;
git rm —cached nome_do_arquivo - Remover arquivo somente do git;
git rm -r nome_do_diretorio - Remover diretório do repositório;
git rm —cached -r nome_do_diretorio - Remover diretório somente do git

## Comandos para trabalhar com o log
git log - Mostra todo o histórico de alterações realizadas;
git log —graph - Mostra o histórico de alterações de forma gráfica;
gitk - Ferramenta para trabalhar com histórico de alterações de forma gráfica;
git log —oneline - Mostra o histórico de alterações de forma resumida em uma linha;
git log nome_arquivo - Mostra o histórico de alterações de um arquivo específico;
git log nome_diretorio - Mostra o histórico de alterações de um diretório específico;

## Links úteis:
https://git-scm.com/doc - Documentação git
https://git-scm.com/downloads/guis/ - Download de ferramenta gráfica específica para cada sistema operacional.

