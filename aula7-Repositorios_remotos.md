# Repositórios remotos

<!-- Exemplo -->
### salvando alterações no Git
* comando git push
* comando git pull
* comando git fetch
<!-- Fim do Exemplo -->

## o que fazer após o commit
- Digamos que voce esteja sastifeito com as alterações feitas e deseja salvar o que fez até agora para que possa retornar a esse mesmo estado posteriormente

- utilizando o comando git 'git remote' você vê o que tem em relação aos arquivos remotos

## git push
- Este comando vai salvar as alterações feitas no seu repositório

## git pull
- Se foi feita alguma alteração no arquivo diretamente no github, você pode utilizar este comando para puxar a alteração para sua máquina local e o comando automaticamente vai dar um 'merge' (vai adicionar a alteração na mesma linha em que foi alterado no github) 

## git fetch
- Ese comando vai no repositório remoto e vai baixar o todas as alterções feitas que não tem no seu arquivo local
- se quiser ver as alterações antes de dar um merge, basta utilizar o comando 'git diff origin main'
- após verificar as alterações baixadas, você pode dar um 'git pull' para atualizar seu arquivo local
- WARNING: é sempre bom verificar o que foi baixado antes de dar um git pull e acabar provocando erros no seu arquivo ao dar o merge