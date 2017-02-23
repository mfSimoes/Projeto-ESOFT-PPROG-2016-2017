# UC 7 - Confirmar registo de Utilizador

##	Formato breve
Um gestor de eventos solicita ao sistema o conjunto de utilizadores que efetuaram o registo e que ainda não foram confirmados no sistema.
O sistema apresenta os dados solicitados ao gestor de eventos.
O gestor de eventos seleciona os utilizadores pretendidos e submete-os ao sistema que, lhe solicita a confirma dessa sua seleção.
O utilizador confirma os dados e o sistema regista os utilizadores selecionados como confirmados e informa o Gestor de eventos do sucesso da operação.

##	SSD de formato breve
![FormatoBreve - UC7- Confirma Registo user.jpg](https://bitbucket.org/repo/goXzaB/images/3236295657-FormatoBreve%20-%20UC7-%20Confirma%20Registo%20user.jpg)
 
##	Formato completo

###Ator principal
Gestor de eventos

###Partes interessadas e seus interesses

    * Utilizador não registado: Pretende obter credenciais para poder aceder a funcionalidades específicas de utilizador registado.
    * Centro de Eventos: Pretende criar e manter registo dos utilizadores de determinadas funcionalidades da aplicação.
* Gestor de eventos: pretende confirmar o registo de utilizadores no sistema

###Pré-condições
* Utilizador autenticado
* Gestor de eventos registado no sistema como utilizador

###Pós-condições
* O registo do utilizador fica armazenado no sistema

###Cenário de sucesso principal (ou fluxo básico)
1.	Um gestor de eventos solicita ao sistema o conjunto de utilizadores que efetuaram o registo e que ainda não foram confirmados no sistema.
2.	O sistema apresenta os dados solicitados ao gestor de eventos.
3.	O gestor de eventos seleciona os utilizadores pretendidos e submete-os ao sistema .
4.	O sistema solicita a confirmação
5.	O utilizador confirma os dados 
6.	O sistema regista os utilizadores selecionados como confirmados e informa o Gestor de eventos do sucesso da operação.


###Extensões (ou fluxos alternativos)
*a. O gestor de eventos solicita o cancelamento da operação.

   * O caso de uso termina.

4a. Dados mínimos obrigatórios em falta.

1. O sistema informa quais os dados em falta.

2. O sistema permite a introdução dos dados em falta (passo 3)

    2.a O gestor de eventos não altera os dados. O caso de uso termina.

4b. O sistema detecta que os dados introduzidos (ou algum subconjunto dos dados) são inválidos.

1. O sistema alerta o gestor de eventos para o facto.

2. O sistema permite a sua alteração (passo 3)

    2a. O gestor de eventos não altera os dados. O caso de uso termina.


##Requisitos especiais
- 

##Lista de variações em tecnologias e dados
-

##Frequência de Ocorrência
-

##Questões em aberto
* A confirmação do registo deve estar sempre disponivel, mesmo que todos os utilizadores já tenham sido confirmados»?
* Quais são os dados obrigatórios para a confirmação do registo de utilizadores?
* Alguém deve ser notificado da confirmação do registo de utilizador no sistema ?
* Qual a frequência de ocorrência deste caso de uso?
* Quem confirma o registo do gestor de eventos?