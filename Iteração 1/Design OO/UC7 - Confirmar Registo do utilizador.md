# Realização do UC7 - Confirmar Registo Utilizador #

## Racional ##

Fluxo Principal | Questão: Que Classe... | Resposta | Justificação
--------------- | ---------------------- | -------- | ------------
1. Um gestor de eventos solicita ao sistema o conjunto de utilizadores que efetuaram o registo e que ainda não foram confirmados no sistema. | n/a| |
2. O sistema apresenta os dados solicitados ao gestor de eventos. | Possui informação sobre os utilizadores não registados? | CentroEventos | IE: O centro de eventos possui o registo dos utilizadores
3. O gestor de eventos seleciona os utilizadores pretendidos e submete-os ao sistema. | n/a| |
4. O sistema solicita a confirmação | n/a | |
5. O utilizador confirma os dados |n/a | |
6. O sistema regista os utilizadores selecionados como confirmados e informa o Gestor de eventos do sucesso da operação. | Onde são guardados os perfis dos utilizadores?| CentroEventos| IE: O Centro de eventos possui informação sobre os utilizadores 



## Sistematização: ##

Do racional resulta que as classes conceptuais promovidas a classes de software são:

* CentroEventos



Outras classes de software (i.e. Pure Fabrication) identificadas:  

* ConfirmarRegistoUtilizadorUI
* ConfirmarRegistoUtilizadorController


## Diagrama de Sequência ##
![UC7_SD.jpg](https://bitbucket.org/repo/goXzaB/images/2747840199-UC7_SD.jpg)

## Diagrama de Classes ##
![UC7_CD.jpg](https://bitbucket.org/repo/goXzaB/images/3295315765-UC7_CD.jpg)