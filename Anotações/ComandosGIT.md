# GIT

**SHA1** - algoritimo de incriptação
	saida -> conjunto de caracteres de 40 digitos
	comando: openssl sha1 nome_do_arquivo.txt

#### Objetos de versionamento de código no GIT:

**BLOBS** ("arquivos") - guarda sha dos objetos / contem metadados do objeto - 'blob 9\0conteudo' (tipo, tamanho, conteúdo)
**TREES** ("pastas")- armazena as BLOBS, aponta para outras TREES, caminho dos arquivos, possui sha1 do arquivo.
**COMMITS** - aponta para: TREE, parente (outras commits), autor, mensagem



#### Comandos GIT

Criar Repositório (pasta oculta):
​comando: git init
​comando: ls -a -> mostra a pasta oculta

	Configurar GIT: 
	comado: git config --global user.email "endereço_de_email"
	comado: git config --global user.name NOME



**git commit -m "mensagem"** - informa ao git as modificações feitas

**git add** (nome_do_arquivo/*/.)- muda o status dos arquivos de untracked para staged.

**Git init** - cria um repositório 

**git status** - mostra a situação dos arquivos que estão na pasta

**git config --list** - lista as configuração do git (git config --global -- unset user.email ou .name...)

**git remote origin**- adiciona a origem do local para onde se vai enviar o repositorio. | *EX-* git remote origin https://github.com/EduardoSegantin/livro-receitas.git

**git remote -v**- lista as listas de repositórios cadastradas

**git push origin master** - envia os repositórios para o github

**git pull origin master**- puxa os arquivos do git para a maquina

**git  clone** - copia um repositório do github para sua maquina | *EX* : git clone http//:endereco_do_repositorio  



#### Links Uteis

[Video instalação e configuração Ubuntu](https://www.youtube.com/watch?v=ZMgLZUYd8Cw&t=7s&ab_channel=ProgrammingKnowledge)

