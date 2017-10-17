# sob_projeto_2
Operational Systems B conclusion project

Pessoal, escreverei um pouco sobre git e colocarei um tutorial aqui.



Basicamente o git é um versionador de código fonte, sua função é garantir que várias
pessoas possam trabalhar em conjunto no mesmo código fonte só que com riscos menores de conflito
e recuperação em caso de confusão de código.

Na master devemos ter o produto que será entregue ao cliente, no caso o professor Edmar.
existem "Releases" que seriam versões estáveis, testadas e que condizem com o solicitado pelo
cliente, no caso do SCRUM ela geralmente não é o produto final mas o que foi acertado com o 
cliente dentro de um perido de tempo (sprints) mas isto é história para outro tutorial.

Na develop temos...o que está sendo desenvolvido (tadáááá!) dela criamos ramificações (branches)
e então desenvolvemos. É uma boa prática determinar uma tarefa curta e factível num espaço menor de tempo para fazer uma branch. Uma vez que a tarefa que foi concluída faz se uma união (merge) com a develop novamente. Neste "merge" conflitos podem ocorrer pois pessoas podem ter trabalhado no mesmo trecho de código, então o git mostrará quais foram as alterações feitas em cada "branch". Logo torna-se nosso trabalho saber o que deve constar no código final do merge, sendo necessária muita atenção para não estragar o código.

Git cheat sheet:

$git clone "repositório"
 clona o repo para sua máquina local

$git fetch origin
 busca alterações na origem do repositório

$git rebase
 atualiza forçadamente o que foi encontrado no repo

$git pull
 busca e atualiza por meio de merge o que temos no repo

$git checkout "branch"
 troca para a branch especificada

$git checkout -b "branch"
 cria uma nova e troca para a branch especificada

$ git add . ou algo específico
 add aquilo que deve ser comitado

$git commit
 prepara um commit para ser enviado para o repo

$git push origin "branc"
 envia o commit para o repo

$git merge "branch"
 faz o merge com da branch especificada com a atual

$git status
 mostra quais arquivos foram modificados em relação a origem
