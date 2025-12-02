Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## TABLE: CARS ENTITY: CAR

COLONNE

- id ---> auto_increment, unique
- immagini ---> null, text(se l'utente imposta più immagini con tanti url di ambia grandezza)
- n.targa ---> notnull, unique, char(7)
- brand ---> varchar(20), notnull
- modello ---> varchar(30), notnull
- km percorsi ---> notnull, varchar(6)
- carburante ---> varchar(40), notnull
- classe ---> notnull, varchar(7)
- cambio ---> notnull, varchar(15)
- incidentata ---> notnull, tinyint, default(no)
- descrizione ---> null, text
- prezzo ---> null, varchar(8)
- immatricolazione ---> notnull, year
- assicurazione del venditore ---> null, tinyint, default(true)
- colore ---> null, varchar(40)
- cavalli ---> notnull, smallint
- cilindrata ---> notnull, smallint
- accessori ---> null, varchar(255)
- carrozzeria ---> null, varchar(20)
- n.porte ---> notnull, tinyint
- n.posti ---> notnull, tinyint
- consumo medio ---> notnull, decimal(4,2)
- n.proprietari ---> notnull, tinyint
- documenti ---> notnull, varchar(50)
