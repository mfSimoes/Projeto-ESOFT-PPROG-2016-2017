# Realização do UC1 - registar evento #

## Racional ##

Fluxo Principal | Questão: Que Classe... | Resposta | Justificação
--------------- | ---------------------- | -------- | ------------
1. O gestor de eventos inicia no sistema o processo de registo de eventos. |Regista o novo evento	|CentroEventos	|Creator: Regra 1
2. O sistema pede os dados do evento (título, texto descritivo, periodo e local de realização). |||
3. O gestor fornece os dados requeridos. |Guarda os dados fornecidos?	|Evento	|Objecto criado no passo 1
 | | Local | Guarda os nome do local do evento
4. O sistema apresenta uma lista de utilizadores que podem ser organizadores. |Onde se vai buscar a lista de utilizadores? | CentroEventos | IE: O centro de eventos possui o registo de todos os utilizadores
5. O gestor de eventos seleciona os organizadores.| Guarda os utilizadores selecionados | Organizador | Guarda os dados de utilizador
 |  | Evento | Guarda os dados dos organizadores 
6. O sistema pede confirmação dos organizadores|||
7. O gestor de eventos confirma.|||
8. O sistema valida os organizadores e o evento e pede confirmação do evento. |Valida os dados?	|Evento	|IE: Validação local (ex: Dados do evento preenchidos)
	|	|CentroEventos	|IE: Validação global
9. O gestor confirma.|||
10. O sistema regista a criação do evento. |Onde é registado o novo evento?	|CentroEventos	| IE: O Centro de Eventos organiza eventos



## Sistematização: ##

Do racional resulta que as classes conceptuais promovidas a classes de software são:

* Evento
* CentroEventos
* Organizador
* Local


Outras classes de software (i.e. Pure Fabrication) identificadas:  

* RegistarEventoUI
* RegistarEventoController


## Diagrama de Sequência ##
![UC1 - SD.png](https://bitbucket.org/repo/goXzaB/images/1274011349-UC1%20-%20SD.png)

## Diagrama de Classes ##
![UC1 - CD.png](https://bitbucket.org/repo/goXzaB/images/898975547-UC1%20-%20CD.png)