# microsocraten
Laboratorio di sperimentazione sui microservizi

## Principi
Questo laboratorio si basa su alcuni principi del design del software: KISS (Keep It Simple Stupid) e YAGNI (You Aren't Gonna Need It) e deve essere visto come un corso introduttivo all'argomento e non esaustivo.


## Obbiettivi
Gli obbiettivi di questo laboratorio di sperimentazione sui microservizi sono:

 - esperienza diretta di architettura e design di microservizi
 - confronto tra diverse implementazioni di microservizi, slegando il discorso dalla tecnologia
 - implementazione nel proprio linguaggio di microservizi basati su contratti comuni

## Prerequisiti
TO BE COMPLETED


## Metodologia
Ogni partecipante del corso troverà nel branch master questa guida assieme a delle risorse comuni per iniziare le varie lezioni del corso e dovrà per partecipare:

 1. effettuare un fork di questo progetto
 2. committare in locale / effettuare il push sul proprio repository
 3. effettuare delle merge request a questo corso, per pubblicare il proprio contributo ai vari esercizi


# Lezioni
Il corso è organizzato per semplicità in lezioni, ognuna è necessaria per costruire il passo seguente, quindi si consiglia di procedere secondo l'ordine prestabilito.


## Lezione 1 - REQUISITI
TO BE COMPLETED: il focus di questa lezione vuole essere l'analisi dei requisiti ed il design dei servizi che si andranno a sviluppare. L'esempio scelto è quello di un sistema di gestione delle issue (o ticket), avente come esempio quello di github.

I requisiti sono (non ordinati) sono volutamente vaghi in questa prima fase:

 - come utente ho bisogno di vedere la lista delle issue da risolvere e sapere quelle assegnate a me, ordinate dalla più recente
 - come utente ho bisogno di vedere la lista delle issue che sono state risolte recentemente, anche da me, ordinate dalla più recente
 - come utente voglio poter creare le issue assegnando titolo, desscrizione, entro quando la voglio risolta e la gravità del problema
 - come utente voglio poter prendermi carico di una issue per risolverla
 - come utente voglio poter dire che un problema è risolto
 - come utente voglio poter gestire (aggiunta, modifica, cancellazione) dei tag a delle issue per poterle raggruppare in gruppi
 - come amministratore voglio poter nascondere e cancellare le issue
 - come utente voglio poter visualizzare le issue che devono essere risolte entro una certa data

A seguito di questa definizione di requisiti, la lezione richiede quindi di comprendere i requisiti ed effettuare il design dei servizi (senza entrare nel merito tecnologico) che risolvono i problemi, assieme ad una modellazione logica del dominio applicativo.

NOTA: la modellazione logica viene fornita per raffronto assieme alla lezione, come diagramma ER


## Lezione 2 - DESIGN DEI SERVIZI
TO BE COMPLETED: analizzati i requisiti ed i servizi da realizzare, essi vanno modellati nel formato comune. Si é scelto come protocollo REST ed ognuno dei microservizi andrà ad implementare l'interfaccia.

NOTA: contavo di definire le interfacce dei servizi REST con OpenAPI / Swagger, così ogni partecipante alla lezione ha la definizione esatta di cosa vuole ogni servizio


## Lezione 3 - IMPLEMENTAZIONE SERVIZI
TO BE COMPLETED: ...

