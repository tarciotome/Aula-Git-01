Git = é o software para acompanhar diferentes versões do meu trabalho.

GitHub = a plataforma que serve como repositório para os trabalhos que desenvolvi no Git. 

Commit = é importante para mover os arquivos da staging area (purgatório) para o repositório local, a partir do qual será construída a minha linha do tempo. 

branch = o que é? (é uma linha do tempo de trabalho paralela/ramificada à minha linha master/principal). Serve para que eu possa fazer modificações no meu doc master em um plano paralelo, ou seja, na ramificação o doc master é alterado, mas na linha master/principal o doc master não é. Isso garante que eu nunca perca aquele doc master funcional, bem como possa investigar o resultado de alterações efetuadas neste em um universo paralelo. O comando é o "git branch + nome que quero dar ao branch". Para ver a lista de branchs uso "git branch --list".

Checkout = serve para se mover entre os branchs e visulizar/trabalhar em um branch de interesse. Entrar e sair das múltiplas linhas do tempo. Seu comando é: "git checkout <nome> ou <id> do branch desejado" 

resolução de conflitos: push (vai me dar um textão) - pull (vai avisar do conflito) - depois abre o arquivo - seleciona o texto que quer - salva como substituindo - git add- commit - push. 

efeito espelho do git na pasta do proj. = como criar uma colaboração - enviar o convite github - aceitar o convite - fazer um clone do repositório ( git clone <ssh>) 

Rotina de colaboração = pull - trabalhar - add + commit + push

# Áreas conceituais

Área de desenvolvimento = é a pasta na qual os meus arquivos são desenvolvidos e salvos. 

Repositório local = local onde ficam salvos todas as versões dos arquivos da minha linha do tempo. 

Staging area = área intermediária entre as duas primeiras trazidas acima. Nela posso decidir se salvo ou excluo o arquivo em análise. Onde os arquivos vão depois do git add.

Área 04 - repositório remoto - é o github, local onde, nas nuvens, ficam salvos os projetos dos meus repositórios. 

git fork = cria uma cópia para mim independente do doc que busquei. O que eu fizer não altera o outro. 





link para material = https://material.bits.vib.be/topics/git-introduction/)
