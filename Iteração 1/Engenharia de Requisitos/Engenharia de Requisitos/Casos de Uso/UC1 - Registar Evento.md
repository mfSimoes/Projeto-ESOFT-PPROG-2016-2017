# UC 1 - Registar evento

##Formato breve
O utilizador inicia no sistema o processo de registo de eventos
O sistema pede os dados do evento ( título, texto descritivo, periodo e local de realização, e organizadores)
O utilizador fornece os dados requeridos.
O sistema valida e pede confirmação.
O utilizador confirma.
O sistema regista a atribuição de candidaturas.

##SSD FORMATO BREVE
![UC1 formato breve - criar evento.png](https://bitbucket.org/repo/goXzaB/images/2163320165-UC1%20formato%20breve%20-%20criar%20evento.png)


##Formato completo
###Ator principal
*Gestor de eventos
    

###Partes interessadas e seus interesses
*Organizador: Pretende saber quais os eventos que organiza
*Gestor de eventos: Pretende criar eventos
*Centro de eventos Pretende ter registo dos eventos criados

###Pré-condições
*Utilizador registado no sistema 

###Pós-condições
*Evento registado
    

###Cenário de sucesso principal (ou fluxo básico)
1. O utilizador inicia no sistema o processo de atribuição de candidaturas para decisão.
2. O sistema pede os dados do evento ( título, texto descritivo, periodo e local de realização, e organizadores)
3. O utilizador fornece os dados requeridos.
4. O sistema valida e pede confirmação.
5. O utilizador confirma.
6. O sistema regista a atribuição de candidaturas.
    

###Extensões (ou fluxos alternativos)
*a. O utilizador cancela o registo de eventos

1. O caso de uso termina.

4a. Dados mínimos obrigatórios em falta.

1. O sistema informa quais os dados em falta

2. O utilizador fornece os dados (passo 3)

	2a. O utilizador não fornece os dados. O caso de uso termina

4b. Dados introduzidos inválidos	

1. O sistema informa o utilizador para o facto.

2. O utilizador altera dos dados.

	2a. O utilizador não altera dos dados. O caso de uso termina.

##Requisitos especiais
*
##Lista de variações em tecnologias e dados
*
##Frequência de Ocorrência
*
##Questões em aberto
* Alguém deve ser notificado quando se regista um evento? 
* Qual a frequência desta ocorrencia?
* Pode-se alterar a os dados do evento?
* Pode-se registar eventos a qualquer altura?