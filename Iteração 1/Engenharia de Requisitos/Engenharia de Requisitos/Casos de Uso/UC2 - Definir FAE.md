# UC 2 - Definir FAE

##	Formato breve
O organizador inicia no sistema o processo de seleção dos FAE.
O sistema fornece os eventos.
O organizador seleciona o evento.
O sistema fornece os utilizadores que podem ser FAE.
O organizador seleciona o FAE.
O sistema fornece a informação acerca do FAE e pede confirmação.
O organizador confirma.
O sistema regista o FAE no sistema.

##	SSD de formato breve

 
##	Formato completo
###Ator principal
* Organizador


###Partes interessadas e seus interesses
* Organizador: Pretende atribuir FAE ao evento.
* FAE: Pretende saber a que eventos foi atribuido.
* Centro de eventos: Pretende ter registo dos FAE para cada evento.

###Pré-condições
* Organizador responsável pelo evento


###Pós-condições
* FAE's atribuídos ao evento


###Cenário de sucesso principal (ou fluxo básico)
1. O organizador inicia no sistema o processo de seleção dos FAE.
2. O sistema fornece os eventos em que o organizador está inscrito.
3. O organizador seleciona o evento.
4. O sistema fornece os utilizadores que podem ser FAE.
5. O organizador seleciona o FAE.
6. O sistema fornece a informação acerca do FAE e pede confirmação.
7. O organizador confirma.
8. O sistema regista o FAE no sistema..


###Extensões (ou fluxos alternativos)
*a. O utilizador cancela a atribuição de FAE ao evento

   1. O caso de uso termina.

2a. Não existem eventos em que o organizador está inscrito.

   1. O sistema informa do problema.

   2. O caso de uso termina.

4a. Não existem utilizadores que podem ser FAE.

   1. O sistema informa do problema.

   2. O caso de uso termina.

##Requisitos especiais
-

##Lista de variações em tecnologias e dados
-

##Frequência de Ocorrência
-

##Questões em aberto
* Alguém deve ser notificado quando se atribui um FAE a um evento? 
* Qual a frequência desta ocorrência?
* Quais os requisitos para ser FAE?
* Quantos eventos pode o organizador estar inscrito?