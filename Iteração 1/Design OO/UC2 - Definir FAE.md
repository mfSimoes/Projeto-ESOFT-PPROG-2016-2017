Fluxo Principal | Questão: Que Classe... | Resposta | Justificação
--------------- | ---------------------- | -------- | ------------
1. O organizador inicia no sistema o processo de seleção dos FAE. ||| 
2. O sistema fornece os eventos em que o organizador está inscrito. | Sabe em que eventos o organizador está inscrito | CentroEventos | IE: possui informações sobre os utlizadores e os eventos
3. O organizador seleciona o evento. |||
4. O sistema fornece os utilizadores que podem ser FAE. | Sabe quais os utilizadores que podem ser FAE | CentroEventos |IE: Possui o registo de todos os utilizadores
5. O organizador seleciona o FAE. | Onde sao guardados os utilizadores selecionados | FAE | Guarda os dados do utilizador
6. O sistema fornece a informação acerca do FAE e pede confirmação. | Possui a informaçao dos FAE? | CentroEventos |  |IE: Possui o registo de todos os utilizadores
7. O organizador confirma.
8. O sistema regista o FAE no sistema e informa do sucesso da operação. | Regista os FAE de cada evento? | Evento | IE: O evento possui informações sobre os seus FAE
 | | CentroEventos | IE: possui informações sobre todos os utilizadores que podem ser FAE.


## Sistematização: ##

Do racional resulta que as classes conceptuais promovidas a classes de software são:

* Evento
* CentroEventos
* FAE


Outras classes de software (i.e. Pure Fabrication) identificadas:  

* DefinirFaeUI
* DefinirFaeController


## Diagrama de Sequência ##
![UC 2 SSD completo.jpg](https://bitbucket.org/repo/goXzaB/images/4174370930-UC%202%20SSD%20completo.jpg)

## Diagrama de Classes ##