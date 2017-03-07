# Realização do UC1 - registar evento #

## Racional ##

Fluxo Principal | Questão: Que Classe... | Resposta | Justificação
--------------- | ---------------------- | -------- | ------------
1. O gestor de eventos inicia no sistema o processo de registo de eventos.	|Regista o novo evento	|CentroEventos	|Creator: Regra 1
2. O sistema pede os dados do evento ( título, texto descritivo, periodo e local de realização, e organizadores)	|	|	|
3. O gestor fornece os dados requeridos.	|Guarda os dados fornecidos?	|Evento	|Objecto criado no passo 1
4. O sistema valida e pede confirmação.	|Valida os dados?	|Evento	|IE: Validação local (ex: Dados do evento preenchidos)
	|	|CentroEventos	|IE: Validação global (ex: Organizador registado no sistema)
5. O gestor confirma.	|	|	|
6. O sistema regista a criação do evento.	|Onde é registada a nova exposição?	|CentroEventos	| IE: O Centro de Eventos organiza eventos



## Sistematização: ##

Do racional resulta que as classes conceptuais promovidas a classes de software são:

* Evento
* CentroEventos


Outras classes de software (i.e. Pure Fabrication) identificadas:  

* RegistarEventoUI
* RegistarEventoController


## Diagrama de Sequência ##

## Diagrama de Classes ##