# UC 5 - Atribuir candidaturas para decisão

##Formato breve
O utilizador incia no sistema o processo de atribuição de candidaturas para decisão.
O sistema pede os dados do FAE (nome e e-mail do FAE).
O ulitizador fornece os dados requeridos.
O sitema valida e pede confirmação.
O utilizador confirma.
O sistema regista a atribuição de candidaturas.

##SSD FORMATO BREVE
![uc 5 formato breve.png](https://bitbucket.org/repo/goXzaB/images/189764153-uc%205%20formato%20breve.png)

##Formato completo
###Ator principal
Organizador
    

###Partes interessadas e seus interesses
Organizador: Pretende atribuir candidaturas aos FAE para este decidir se são aceites ou recusadas
FAE: Pretende saber quais as candidaturas que deve avaliar

###Pré-condições
Utilizador registado no sistema como organizador
FAE registado no sistema   

###Pós-condições
Candidaturas atribuidas para decisão 
    

###Cenário de sucesso principal (ou fluxo básico)
1. O utilizador incia no sistema o processo de atribuição de candidaturas para decisão.
2. O sistema pede os dados do FAE (nome e e-mail do FAE).
3. O ulitizador fornece os dados requeridos.
4. O sitema valida e pede confirmação.
5. O utilizador confirma.
6. O sistema regista a atribuição de candidaturas.
    

###Extensões (ou fluxos alternativos)
*a. O utilizador cancela a atribuição de candidaturas.
	1. O caso de uso termina.
4a. Dados mínimos obrigatórios em falta.
	1. O sistema informa quais os dados em falta
	2. O utilizador fornece os dados (passo 3)
		2a. O ultizador não fornece os dados. O caso de uso termina
4b. Dados introduzidos inválidos	
	1. O sistema informa o utilizador para o facto.
	2. O ultiziador altera dos dados.
		2a. O utilizador não altera dos dados. O caso de uso termina.

##Requisitos especiais
-
##Lista de variações em tecnologias e dados
-
##Frequência de Ocorrência
-
##Questões em aberto
* Alguém deve ser notificado quando se atribui uma candidatura? 
* Qual a frequência desta ocorrencia?
* Pode-se alterar a atribuição da candidatura?
* Pode-se alterar candidaturas em qualquer altura?