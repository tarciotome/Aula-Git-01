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



git remote <nome do repositório> <ssh> = para criar um repositório remoto. Na verdade, este serve para criar a ponte entre o pc e o github. O ssh é fornecido pelo github.

git push = é o comando que  é utilizado para enviar todo o arquivo do repositório local (pasto do pc)  para o github.

Git pull = pull significa puxar. Sua função é trazer arquivos do github para a minha área local. 
