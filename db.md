<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

# AutoUsateConcessionario Database

## Auto usate in vendita

# colonna della tabella

ID | PRIMARY KEY, BIGINT, AUTO_INCREMENT, UNIQUE , NOT NULL
Marca | VARCHAR(255), NOT NULL,
Modello | VARCHAR(50), NOT NULL,
Immagine | VARCHAR(255)
Anno | YEAR
Data_immatricolazione | DATE
Chilometraggio | INT, NOT NULL
Prezzo | DECIMAL(10, 2) NOT NULL,
Cilindrata | TINYINT, NULL 
Descrizione | TEXT,NULL
Concessionario | VARCHAR(255) NOT NULL,
Contatto | VARCHAR(255) NOT NULL,
Data_inserimento | DATETIME 
Voto | FLOAT(2, 1) , DEFAULT(0)
Ultima_modifica | TIME
Disponibilità | VARCHAR(15) NOT NULL









<!-- Note:
TINYINT: Utilizza 1 byte (8 bit) di spazio e può rappresentare 2^8 = 256 valori distinti. Nel caso di TINYINT, questi valori vanno da 0 a 255.

SMALLINT: Utilizza 2 byte (16 bit) di spazio e può rappresentare 2^16 = 65,536 valori distinti. Nel caso di SMALLINT, questi valori vanno da -32,768 a 32,767.

MEDIUMINT: Utilizza 3 byte (24 bit) di spazio e può rappresentare 2^24 = 16,777,216 valori distinti. Nel caso di MEDIUMINT, questi valori vanno da -8,388,608 a 8,388,607.

INT: Utilizza 4 byte (32 bit) di spazio e può rappresentare 2^32 = 4,294,967,296 valori distinti. Nel caso di INT, questi valori vanno da -2,147,483,648 a 2,147,483,647.

BIGINT: Utilizza 8 byte (64 bit) di spazio e può rappresentare 2^64 = 18,446,744,073,709,551,616 valori distinti. Nel caso di BIGINT, questi valori vanno da -9,223,372,036,854,775,808 a 9,223,372,036,854,775,807. -->