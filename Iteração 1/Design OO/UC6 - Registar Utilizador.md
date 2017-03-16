# Realização do UC6 - Registar Utilizador #

## Racional ##

Fluxo Principal | Questão: Que Classe... | Resposta | Justificação
--------------- | ---------------------- | -------- | ------------
1. O utilizador inicia no sistema o seu registo | Cria o novo utilizador? | CentroEventos | Creator: Regra 1
2. O sistema solicita os dados do utilizador (nome, e-mail, credenciais de acesso) | n/a ||
3. O utilizador introduz os dados solicitados | Onde se guardam os dados? | Utilizador | Tem os atributos que suportam os dados a guardar
4. O sistema valida os dados e pede confirmaçao | Quem valida os dados | Centro de Eventos | Validaçao global (ex: duplicados
 | | Utilizador | Validaçao local: tem os seus dados
5. O utilizador confirma os dados inseridos | n/a ||
6. O sistema regista o perfil do utilizador e informa do sucesso da operaçao | Quem regista o perfil?| CentroEventos | IE: no MD o centro de eventos tem registo do utilizador
## Sistematização: ##

Do racional resulta que as classes conceptuais promovidas a classes de software são:

* Utilizador
* CentroEventos



Outras classes de software (i.e. Pure Fabrication) identificadas:  

* RegistarUtilizadorUI
* RegistarUtilizadorController


## Diagrama de Sequência ##
![UC6 - SD.jpg](https://bitbucket.org/repo/goXzaB/images/3653198012-UC6%20-%20SD.jpg)

## Diagrama de Classes ##