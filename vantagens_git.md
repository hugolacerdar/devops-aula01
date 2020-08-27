### 1 - O git é mais eficiente para comparar dois arquivos diferentes
Quando clonamos um repositório para a nossa máquina, os arquivos e diretórios que vemos no editor são somente um espelho do que está dentro do diretório .git/object. Os bancos de dados que compõem o conteúdo são, de fato, o que está dentro desses objetos, que podem ser utilizados para reproduzirmos todos os diretórios e arquivos. 
Rastreando primeiro o conteúdo e depois os metadados, o git evita conflitos provocados, por exemplo, pela exclusão de um arquivo por uma branch e a atualização do nome desse mesmo arquivo por outra. 

### 2 - Estrutura de dados do git é aberta e razoavelmente simples de trabalhar
O que possibilita a existência provedores de git, como Github e Bitbucket, facilitando o trabalho de desenvolvedores.

### 3 - Algoritmo de merge 3-way
Com esse modo de mergear branches, o git evita diversos problemas, pois compara o que está sendo commitado com o estado do commit do qual a branch deriva diretamente e com o estado mais atual na master. 

### 4 - Possibilidade de fazer vários commits no repositório local
O que permite que armazenemos o trabalho realizado enquanto offline e enviemos ao repositório remoto quando acessarmos a internet. O fato de ser distribuído, sem depender de um servidor, permite esta possibilidade. 

### 5 - Versionamento
Temos a possibilidade de acessar nossos projetos em diversos pontos do seu desenvolvimento, não perdendo o histórico a cada nova versão. 
