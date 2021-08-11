# senai-versoes-colaboracoes
Repositório versões e colaborações

Readme de exemplo. Teste.

================================================================
Foram utilizados os seguintes comandos para cada etapa:

Desafio 1

Após instalação do Git foi realizada a configuração do com user name e email do usuário. 
Comando : git config --global user.name "Nome" e git config --global user.email "email@email.com"

Foi criada a pasta senai-versoes-colaboracoes no computador e posteriormente a criação do repositório local no Git bash (a tela prompt onde foram digitados todos os comandos).

Desafio 2

Git init = inicializou o repositório dentro da pasta senai-versoes-colaboracoes;
(Dentro da pasta senai... foi criado um arquivo de texto chamado versoes.txt.)

Git status = utilizado para verificar as alterações realizadas na pasta;

Git add versoes.txt = utilizado para adicionar essas alterações na área staging (área que possibilita a verificação das alterações antes de salvá-las);

Git Status = aplicado novamente para verificação das alterações antes salvar.

Git commit = realizado para salvar/confirmar as alterações. Foi realizado como git commit -m "meu primeiro commit", para deixar registrado como comentário o nome dessa ação salva.

Git log = utlizado para visualizar as alterações realizadas/salvas no repositório, com nome, email, data e hora que foi realizado.

Foi realizado o cadastro no GitHub e criado um repositório remoto com o mesmo nome criado na pasta do repositório local: senai-versoes-colaboracoes.

Git remote add origin git@github.com:username/senai-versoes-colaboracoes.git = utilizado no Git bash para informar o repositório remoto;

Git remote -v = utilizado para visualizar o rpositório remoto;

Git push -u origin master = para publicar alterações no repositório remoto;

Autorização do usuário no meu caso foi realizada manualmente, buscando pastas, gerando chave, copiando e colando no GitHub.

Após autorizado, as informações do repositório local foram publicadas no repositório remoto.

Foi realizado o git pull para puxar infromações do remoto para o local e realizado um .gitignore para impedir que uma alteração seja monitorada e salvando essa alteração com git commit comentado.

Foi criado um README.md no repositório remoto para simulação de alterações feita por outro programador.

Desafio 3

Foi realizado clone de um repositório usando git clone junto com o code do repositório remoto, no Git Bash.

Foram criadas branchs: 

Uma com o: git checkout -b tarefa/minha-primeira-branch e realizada alteração dentro dela (no README.md), verificando em git status, depois git add . e git commit comentado para salvar a ação. Após alteração concluída verificado no GitHub as alterações feitas concluídas com sucesso.
E uma outra branch mostrando como voltar a pasta master usando o git checkout master e criando branch com git checkout -b exemplo-branch. Nessa também foi realizada alteração no conteúdo (no README.md), salvo com git commit comentado e atualizado no remoto.

Para unificar os ramos foi utilizado git merge tarefa/minha-primeira-branch porém isso gerou um conflito que foi resolvido com:

Aceitando as alterações realizadas nas 2 branchs, Abrindo o README.md e verificando que nele havia descrito os conflitos. Os conflitos foram removidos deixando somente os conteúdos de cada branch a ser unificado e realizado o git add ., git commit e git push na pasta exemplo-branch. Após isso, a unificação foi realizada com sucesso podendo ser visualidade no remoto normalmente.

Criação de Tag com git tag -a v1.0 -m "minha primeira tag" e para verificação de tag usando git tag. Para saber informações de uma tag específica usa-se git show nome da tag (no caso, git show v1.0)
Para empurrar tags ao remoto usa-se git push origin --tags.

E por fim, acessando o GitHub consegue-se ver a tag criada e todas as alterações realizadas para este repositório remoto.
Esse breve relatório de etapas salvo aqui também foi salvo na pasta local também usando o git pull no Git Bash.
