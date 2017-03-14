# UC 1 - Registar evento

##Formato breve
O gestor de eventos inicia no sistema o processo de registo de eventos.
O sistema pede os dados do evento (título, texto descritivo, periodo e local de realização).
O gestor fornece os dados requeridos.
O sistema apresenta uma lista de utilizadores que podem ser organizadores.
O gestor de eventos seleciona os organizadores.
O sistema pede confirmação dos organizadores
O gestor de eventos confirma. 
O sistema valida os organizadores e o evento e pede confirmação do evento.
O gestor confirma.
O sistema regista a criação do evento.

##SSD FORMATO BREVE
![UC1 formato breve - criar evento.png](https://bitbucket.org/repo/goXzaB/images/2163320165-UC1%20formato%20breve%20-%20criar%20evento.png)


##Formato completo
###Ator principal
* Gestor de eventos
    

###Partes interessadas e seus interesses
* Organizador: Pretende saber quais os eventos que organiza
* Gestor de eventos: Pretende criar eventos
* Centro de eventos Pretende ter registo dos eventos criados

###Pré-condições
* Utilizador registado no sistema 

###Pós-condições
* Evento registado
    

###Cenário de sucesso principal (ou fluxo básico)
1. O gestor de eventos inicia no sistema o processo de registo de eventos.
2. O sistema pede os dados do evento (título, texto descritivo, periodo e local de realização).
3. O gestor fornece os dados requeridos.
4. O sistema apresenta uma lista de utilizadores que podem ser organizadores.
5. O gestor de eventos seleciona os organizadores.
6. O sistema pede confirmação dos organizadores
7. O gestor de eventos confirma. 
8. O sistema valida os organizadores e o evento e pede confirmação do evento.
9. O gestor confirma.
10. O sistema regista a criação do evento.
    

###Extensões (ou fluxos alternativos)
*a. O utilizador cancela o registo de eventos

1. O caso de uso termina 

8a. Dados mínimos obrigatórios em falta.

1. O sistema informa quais os dados em falta

2. O gestor de eventos fornece os dados (passo 3)

	2a. O utilizador não fornece os dados. O caso de uso termina




##Requisitos especiais
*
##Lista de variações em tecnologias e dados
*
##Frequência de Ocorrência
*
##Questões em aberto
* Alguém deve ser notificado quando se regista um evento? 
* Qual a frequência desta ocorrência?
* Pode-se alterar a os dados do evento?
* Pode-se registar eventos a qualquer altura?
* O sistema pode fornecer ao gestor de eventos, os utilizadores que podem ser Organizadores? Se sim, quais os requisitos necessários para se ser organizador? Se não, qual a informação mínima para definir um Organizador (por exemplo: e-mail)?
* Há algum atributo que deve ser único? Qual?
* Podem ocorrer eventos em simultâneo no mesmo local?