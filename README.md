scrivi una applicazione web Spring Boot con le dipendenze neccessarie che:
gira sulla porta 5050
utilizza Rest Repositories HAL Explorer
si connette a una base dati MySQL locale
cancella lo schema alla fine della sessione
crea la tabella di linguaggi di programmazione, dove ogni ProgrammingLanguage ha:
primary key
name not null
l'anno della crezione firstAppearance che può essere null
inventor not null
ha un repository dedicato per linguaggi di programmazione, così puoi usare HAL Explorer e Postman:
il repository usa path specifico repo-prog-languages con la descrizione
utilizza Postman per:
aggiungere 4 linguaggi di programmazione:
Java
C++
JavaScript
Go
prendere la lista di tutti i linguaggi di programmazione nella base dati, con la paginazione con 2 risultati nella pagina
cambiare inventor di uno dei linguaggi esistenti, mettendo il tuo nome
