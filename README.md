# Workshop de R: Levando a Ciência de Dados para Todos

 é o repositório para os arquivos do meu workshop de iniciação ao R.

> **Workshop de R: Levando a Ciência de Dados para Todos**
> 
> Assim como o inglês se tornou uma língua obrigatória para quem quer fazer ciência ou compreender melhor o mundo no qual está inserido, saber interpretar dados está se virando uma habilidade cada vez mais imprescindível nos dias atuais. Embora seja trivial utilizar uma planilha eletrônica para analisar dados simples, este tipo de ferramenta possui diversas limitações. Por exemplo, não é possível registrar todos os passos utilizados em uma análise feita utilizando o Excel, o que inviabiliza a sua reprodutibilidade. Além disso, também não é possível trabalhar com arquivos que possuam milhões de linhas de informações. Em oposição a clicar em menus, escrever comandos para o computador executar é uma forma do usuário se conectar em um nível mais profundo àquilo que está executando. Desta forma, aprender ciência de dados através de uma linguagem de programação é capaz de aumentar as habilidades dos analistas, fazendo com que eles consigam perguntar e responder perguntas mais sofisticadas. Tarefas de análise de dados são fáceis de serem realizadas com linguagens de programação como R e python. Neste curso optamos pelo R pelas suas capacidades gráficas avançadas, que permitem recompensas rápidas ao usuário. Ao ver na tela os gráficos que explicam seus dados, os usuários sentem-se realizados, ganhando incentivos que o fazem se aprofundar neste tipo de estudo.

Para poder acompanhar o workshop ou reproduzi-lo em casa, é necessário seguir alguns passos. São eles:

- Instale o `R`: [https://cran.r-project.org/](https://cran.r-project.org/)

- Instale o RStudio: [https://www.rstudio.com/products/rstudio/download/](https://www.rstudio.com/products/rstudio/download/)

- Com o RStudio aberto, instale o material do workshop:

    ```install.packages("devtools")```
    
    ```devtools::install_github("mnunes/workshopR", build_vignettes = TRUE)```
    
A fim de facilitar o entendimento dos participantes do workshop, decidi criar um pacote no R com todo o material necessário para seu acompanhamento.
    
Dependendo dos pacotes que seu computador já possua em disco, a instalação do pacote `workshopR ` pode acabar demorando um pouco. Se tudo correr bem, os comandos
    
    library(workshopR)
    vignette("workshopR")

vão abrir o material a ser utilizado durante o workshop. 

<!---
Há alguns exercícios ao final deste material. As respostas dos exercícios estão [neste link](https://github.com/mnunes/workshopR/blob/master/exercicios.R) (em breve).
-->

