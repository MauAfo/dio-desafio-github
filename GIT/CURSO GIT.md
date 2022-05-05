CRIANDO PASTAS:
MKDIR ex: mkdir filmes 	(mesma coisa no linux)

CRIANDO UM TXT DENTRO DA PASTA VIA CMD:
Echo hello > hello.txt
O comando DEL só deleta arquivos.
Para remover pastas (repositórios) usa-se o comando RM. 

EX:
Rmdir filmes
SE a pasta possuir arquivos, use:
Rmdir filmes /s /q				rm -rf filmes/ (linux)

MV = mover. EX: (mv carne assada.md ./receitas/)
Ls -a (lista arquivos ocultos)
GIT
SHA1 = sistema que criptografa um arquivo.

OBJETOS INTERNOS DO GIT: responsáveis pelo versionamento do seu código
Blops: armazena dados
Trees: armazena os BLOPS
Commits: Armazena todos os acima.

CHAVES SSH 

CRIANDO UM REPOSITÓRIO GIT:

Código GIT INIT (cria um repositório no git)
Configuração inicial para o Git:
Git config –global user.email “aqui”
DPS:
Git config –global user.name “aqui”

MARKDOWN: * antes de escrever (h´s do html)
Sua extensão é o MD

GIT STATUS : serve para monitorar os status dos arquivos
Git commit -m “comentário”
Git add * = adiciona todas as modificações para dentro do stage
Git push origin master: envia tudo para o github

PARA RESOLVER CONFLITOS: git pull origin master (puxa do github o repositório)

PRIMEIRO: Git add + git commit + git push origin master (ou apenas git push)

