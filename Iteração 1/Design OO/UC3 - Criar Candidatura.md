# Realização do UC3 - Criar Candidatura #

## Racional ##

Fluxo Principal | Questão: Que Classe... | Resposta | Justificação
--------------- | ---------------------- | -------- | ------------
1. O representante do participante inicia no sistema o processo criação da candidatura. |Regista o nova candidatura	|Evento|Creator: Regra 1
2. O sistema pede os dados necessários para fazer a candidatura da empresa para o evento. |||
3. O representante do participante fornece os dados requeridos. |Guarda os dados fornecidos?	|Candidatura	|Objecto criado no passo 1
4. O sistema valida os dados e pede confirmação. |Valida os dados? | Candidatura | IE: Validação local (ex: Dados da candidatura preenchidos)
||Evento|IE: Validação global
5.O representante do participante confirma.||||
6.O sistema regista a candidatura no sistema e informa do sucesso da operação.|Onde é registada a nova candidatura?|Evento|IE: Candidatura para o evento


## Sistematização: ##

Do racional resulta que as classes conceptuais promovidas a classes de software são:

* Candidatura
* Evento


Outras classes de software (i.e. Pure Fabrication) identificadas:  

* RegistarCandidaturaUI
* RegistarCandidaturaController


## Diagrama de Sequência ##


## Diagrama de Classes ##
v