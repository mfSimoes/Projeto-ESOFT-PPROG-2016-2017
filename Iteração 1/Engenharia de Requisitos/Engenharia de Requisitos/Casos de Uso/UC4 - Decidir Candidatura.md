# UC5 - Atribuir candidaturas para decisão

##Formato breve
O FAE inicia no sistema o processo de decisão de candidaturas.
O sistema lista as candidaturas para decisão.
O FAE seleciona uma candidadura.
O sistema apresenta a candidatura, e pede uma decisão e um breve texto justificativo.
O FAE aceita ou recusa a candidatura, e escreve um texto justificativo.
O sistema valida e pede confirmação.
O FAE confirma.
O sistema regista a decisão.

##SSD FORMATO BREVE
![decidir candidatura ssd breve.jpg](https://bitbucket.org/repo/goXzaB/images/2247477593-decidir%20candidatura%20ssd%20breve.jpg)

##Formato completo
###Ator principal
* FAE
    

###Partes interessadas e seus interesses
* FAE: Pretende decidir as candidaturas
* Organizador: Pretende saber quais as candidaturas aceites
* Gestor de eventos: Pretende saber quais as candidaturas aceites
* Representante do participante: Pretende saber se a sua candidatura foi aceite ou recusada, e a justificação

###Pré-condições
* Utilizador registado no sistema como FAE

###Pós-condições
* Candidaturas atribuidas para decisão 
    

###Cenário de sucesso principal (ou fluxo básico)
1. O FAE inicia no sistema o processo de decisão de candidaturas.
2. O sistema lista as candidaturas para decisão.
3. O FAE seleciona uma candidadura.
4. O sistema apresenta a candidatura, e pede uma decisão e um breve texto justificativo.
5. O FAE aceita ou recusa a candidatura, e escreve um texto justificativo.
6. O sistema valida e pede confirmação.
7. O FAE confirma.
8. O sistema regista a decisão.
    

###Extensões (ou fluxos alternativos)
*a. O utilizador cancela a decisão de candidaturas.

1. O caso de uso termina.

2a. Não há candidaturas para decisão

1. O sistema alerta para o facto. O caso de uso termina.

6a. Dados minimos obrigatórios em falta.

1. O sistema informa quais os dados em falta

2. O utilizador fornece os dados (passo 3)

    2a. O utilizador não fornece os dados. O caso de uso termina

6b. Dados introduzidos inválidos

1. O sistema informa o utilizador para o facto.

2. O utilizador altera dos dados.

    2a. O utilizador não altera dos dados. O caso de uso termina.

##Requisitos especiais
-
##Lista de variações em tecnologias e dados
-
##Frequência de Ocorrência
-
##Questões em aberto
* Alguém deve ser notificado quando se decide uma candidatura? 
* Qual a frequência desta ocorrencia?
* Pode-se alterar a decisão da candidatura?
* Pode-se alterar candidaturas em qualquer altura?
* Quais os dados minimos obrigatórios?