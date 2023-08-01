cheat sheet = colinha de comandos

git init = comando para inicializar um repositório git. Só uma vez por projeto!!!!!!!!!! obs.ter certeza de que estou iniciando na pasta onde vou desenvolver o meu projeto, o git não consegue bisbilhotar pastas acima da sua posição hierárquica, cuidar para não iniciar 2x o git no mesmo projeto (considerando que ele enxerga subpastas abaixo do seu nível hierárquico) 

git add:.... adiciona os arquivos na staging area (purgatório), a qual é importante para que eu decida e organize os arquivos antes de enviá-los para o repositório local, que constrói a linha do tempo. 

Git commit -m "mensagem significativa":....    = servge para enviar os arquivos para o repositório local, de onde florescerá a linha do tempo. 

O que considerar na minha msg?   

por quê

Como

efeitos 

limitações

git status = comando que mostra a situação do repositório que contém os trabalhos que estou realizando, isto é, ele mostra o status. 

O que acontece se eu esquecer o -m no comando commit? O git abre o editor VI que me permite escrever mensagens bem longas e elas ficam formatas em texto. 
<<<<<<< HEAD
=======

git remote <nome do repositório> <ssh> = para criar um repositório remoto. Na verdade, este serve para criar a ponte entre o pc e o github. O ssh é fornecido pelo github.

git push = é o comando que  é utilizado para enviar todo o arquivo do repositório local (pasto do pc)  para o github.

Git pull = pull significa puxar. Sua função é trazer arquivos do github para a minha área local. 

## Colaboração:

Inicia-se com o convite para compartilhamento do GitHub, após a confirmação, segue para o uso da ferramenta _clone_. 

***Vale ressaltar a necessidade de criar o clone desse projeto em uma pasta sem um git local, para não ocorrer erros com a comunicação com o Git com o GitHub***;

* git clone SSH (Do repositório do seu colaborador);

git remote <nome do repositório> <ssh> = para criar um repositório remoto. Na verdade, este serve para criar a ponte entre o pc e o github. O ssh é fornecido pelo github.

git push = é o comando que  é utilizado para enviar todo o arquivo do repositório local (pasto do pc)  para o github.
=======

Git pull = pull significa puxar. Sua função é trazer arquivos do github para a minha área local. 

## Colaboração no github

Inicia-se com o convite para compartilhamento do GitHub, após a confirmação, segue para o uso da ferramenta _clone_. 

***Vale ressaltar a necessidade de criar o clone desse projeto em uma pasta sem um git local, para não ocorrer erros com a comunicação com o Git com o GitHub***;

Inicialmente, deve-se entrar no seu login do GitHub, depois ir em "settings", depois "collaborations", depois "enviar um convite de colaboração", depois o colaborador aceita. Para conseguir ter os arquivos no PC, o colaborador deve criar um repositório/pasta, em seguida no GitBash deve selecionar essa pasta, depois copia o "ssh" do repositório no GitHub, depois no GitBash executa o comando "git clone ". Com isso, os arquivos da pasta do rementente (que estavam no GitHub) estarão disponíveis no PC do colaborador.
=======

git checkout ID: cuidado para não mexer no passado, é melhor criar um branch. 
