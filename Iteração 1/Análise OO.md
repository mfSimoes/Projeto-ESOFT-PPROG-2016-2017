#	Análise OO

##	Racional para identificação de classes de domínio

Categoria: Conceitos

+	**Transações  (do negócio): ** Evento; candidatura; decisão 
+	**Linhas de transações: **
+	**Produtos ou serviços relacionados com transações: ** Evento
+	**Registos (de transações): ** Registo de utilizadores
+	**Papéis das pessoas:** Utilizador, Organizador, FAE, Representante do participante, Gestor de eventos
+	**Lugares: ** Centro de eventos do norte do país
+	**Eventos: ** Evento
+	**Objetos físicos:** 
+	**Especificações e descrições: **
+	**Catálogos: **
+	**Conjuntos:** Centro de eventos
+	**Elementos de conjuntos: ** Organizador, FAE
+	**(Outras) Organizações: ** Empresas participantes
+	**Outros sistemas (externos): **
+	**Registos (financeiros), de trabalho, contractos, documentos legais: ** Candidatura
+	**Instrumentos financeiros: **
+	**Documentos referidos/para executar as tarefas:** Candidatura

##	Racional sobre identificação de associações entre classes
###Candidatura
* A um: Evento
* Feita por: Representante do participantes
* Atribuída por: Organizador
* Decidida por: FAE 

###Centro de eventos
* Organiza: Evento
* Tem Registo: Utilizadores

###Decisão
* De: candidatura
* Feita por: FAE
* Faz parte: evento

###Evento
* Decorre: Centro de Eventos
* É criada: Gestor de Eventos
* É organizada por: Organizadores
* Ocorre em: Stands
* Tem: Organizadores, FAE, Representantes de participantes

###FAE
* Faz: decisão
* Decide: candidatura
* É um: utilizador
* Pertence: ao evento
* É definido por: organizador

###Gestor de eventos
* Cria: evento
* É um: Utilizador
* Define: Organizador
* Confirma: registo de utilizador

###Organizador
* Define: FAE
* Atribui: Candidatura
* É um: Utilizador
* É definido por: Gestor de exposição

###Representante
* Elabora: Candidatura
* É um: Utilizador
* Representa: Participante (empresa)

###Utilizador
* Pode ser: Organizador
* Pode ser: Gestor de Exposições
* Pode ser: FAE
* Pode ser: Representante
* Pertence a: Centro de eventos
* Confirmado por: gestor de exposições




##	Diagrama de MD