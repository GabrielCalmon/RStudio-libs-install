# Instalçao do RStudio e de bibliotecas
Este repositório foi criado para apresentar o processo de instalação das bibliotecas da linguagem R usadas pelo método Bili, em especial quando são encontrados erros ao longo do processo de instalação

## RStudio
O tutorial abaixo apresenta em detalhes o processo de instalação do RStudio
https://linuxconfig.org/how-to-install-rstudio-on-ubuntu-20-04-focal-fossa-linux



## Revtools
Primeiramente, abra um terminal e rode este comando ou pode ser utilizado o terminal do próprio RStudio:

```
$ sudo apt-get install gsl-bin libgsl0-dev
```

Em seguida, abrir o RStudio rodar os seguintes comandos no console:

```
install.packages("remotes")
remotes::install_github("mjwestgate/revtools")
library(revtools)
```

## litsearch
Primeiro, abra o RStudio e no console do programa digite:

```
install.packages("remotes")
library(remotes)
install_github("elizagrames/litsearchr", ref="main")
```

## Bibliometrix
Primeiro, abra o RStudio e no console do programa digite:

```
library(revtools)
install.packages("bibliometrix")
```
