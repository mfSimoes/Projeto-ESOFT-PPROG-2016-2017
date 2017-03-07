#	Análise OO

##	Racional para identificação de classes de domínio

Categoria: Conceitos

+	**Transações  (do negócio): ** Evento; candidatura; decisão 
+	**Linhas de transações: **
+	**Produtos ou serviços relacionados com transações: ** Evento
+	**Registos (de transações): ** Registo de utilizadores
+	**Papéis das pessoas:** Utilizador, Organizador, FAE, Representante do participante, Gestor de eventos
+	**Lugares: ** Centro de eventos do norte do país, Local, Stands
+	**Eventos: ** Evento
+	**Objetos físicos:** 
+	**Especificações e descrições: **
+	**Catálogos: **
+	**Conjuntos:** Organizador, FAE
+	**Elementos de conjuntos: ** 
+	**(Outras) Organizações: ** Empresas participantes
+	**Outros sistemas (externos): **
+	**Registos (financeiros), de trabalho, contractos, documentos legais: ** Candidatura
+	**Instrumentos financeiros: **
+	**Documentos referidos/para executar as tarefas:** Candidatura

##	Racional sobre identificação de associações entre classes
###Candidatura
* A um: Evento

###Centro de eventos
* Organiza: Evento
* Tem Registo: Utilizadores

###Decisão
* De: Candidatura
* Faz parte de: Evento

###Evento
* Ocorre em: Local


###FAE
* Faz: decisão
* Decide: candidatura
* É um: utilizador
* Pertence: ao evento


###Gestor de eventos
* Cria: evento
* É um: Utilizador
* Define: Organizador
* Confirma: registo de utilizador

###Organizador
* Define: FAE
* Atribui: Candidatura
* É um: Utilizador
* Organiza: Evento

###Representante
* Elabora: Candidatura
* É um: Utilizador
* Representa: Participante (empresa)

###Utilizador
* Pertence a: Centro de eventos





##	Diagrama de MD