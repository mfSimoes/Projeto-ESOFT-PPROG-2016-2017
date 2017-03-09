# UC 3 - Criar Candidatura

##	Formato breve
O representante do participante inicia no sistema o processo criação da candidatura.
O sistema pede os dados necessários para fazer a candidatura da empresa para o evento.
O representante do participante fornece os dados requeridos.
O sistema valida os dados e pede confirmação.
O representante do participante confirma.
O sistema regista a candidatura no sistema e informa do sucesso da operação.

##	SSD de formato breve

![SD - UC3.jpg](https://bitbucket.org/repo/goXzaB/images/3110758728-SD%20-%20UC3.jpg)
 
##	Formato completo
###Ator principal
* Representante do participante


###Partes interessadas e seus interesses
* Representante do participante: Pretende criar a candidatura para o evento.
* Centro de eventos: Pretende ter registo das candidaturas para cada evento.

###Pré-condições
* Representante do participante terá que estar registado no sistema


###Pós-condições
* Candidatura criada para o evento


###Cenário de sucesso principal (ou fluxo básico)
1. O representante do participante inicia no sistema o processo criação da candidatura.
2. O sistema pede os dados necessários para fazer a candidatura da empresa para o evento.
3. O representante do participante fornece os dados requeridos.
4. O sistema valida os dados e pede confirmação.
5. O representante do participante confirma.
6. O sistema regista a candidatura no sistema e informa do sucesso da operação.


###Extensões (ou fluxos alternativos)
*a. O representante do participante cancela a criação da candidatura para o evento.

1. O caso de uso termina.

4a. Dados mínimos obrigatórios em falta.

1. O sistema informa quais os dados em falta

2. O representante do participante fornece os dados (passo 3)

	2a. O representante do participante não fornece os dados. O caso de uso termina

4b. Dados introduzidos inválidos	

1. O sistema informa o utilizador para o facto.

2. O representante do participante altera dos dados.

	2a. O representante do participante não altera dos dados. O caso de uso termina.

##Requisitos especiais
-

##Lista de variações em tecnologias e dados
-

##Frequência de Ocorrência
-

##Questões em aberto
* Alguém deve ser notificado quando se criar a candidatura? 
* Qual a frequência desta ocorrência?
* Quais os requisitos para ser criar a candidatura?