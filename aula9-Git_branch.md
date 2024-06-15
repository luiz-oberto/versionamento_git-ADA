# Git Branch
- imagine que você está no meio do desenvolvimento de um certo código que está seguindo um determinado fluxo, porém, para fins de otimização do código, um amigo seu vai seguir por outro fluxo enquanto você continua seu fluxo de trabalho, Ou seja, vai ocorrer uma ramificação do trabalho. Para isso existe o Git Branch

## git branch (nome da branch)
- Este comando vai criar uma nova branch

## git log --oneline --decorate
- este comando além de trazer os logs de commits ele traz também a HEAD (ou melhor, a branch) em que estamos trabalhando.

## git checkout (nome da branch)
- este comando vai alterar a HEAD pra branchem que queremos trabalhar
- caso queira confirmar se deu certo é só dar o comando 'git log --oneline --decorate' novamente

## .gitignore
- O git ignore é aonde vamos adicionar o nome dos arquivos ou padrões para que o git ignore o rastreamento desses arquivos