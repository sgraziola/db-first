# Descrizione

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Database

# Table name: Lista Auto / Parco Auto

# Table Coloumns:

    -id | BIGINT PK AI NOTNULL UNIQUE
    -Modello | VARCHAR(50) | NOTNULL
    -Marca | VARCHAR(30) | NOTNULL
    -Data_prima_immatricolazione | TIMESTAMP(MM-YYYY) | NULL
    -Targa | VARCHAR(10) | NULL
    -Chilometraggio | MEDIUMINT | NULL
    -Scadenza_revisione | TIMESTAMP(MM-YYYY) | NULL
    -Prezzo vendita | MEDIUMINT| NULL
    -Cambio | VARCHAR(10) | NULL
    -Carburante | VARCHAR(7) | NULL
    -PotenzaCV | VARCHAr(15) | NULL
    -Cilindrata | SMALLINT | NULL
    -Numero_precedenti_proprietari | TINYINT | NULL
    -Incidentata | VARCHAR(3) | NULL
    -Immagine | VARCHAR(255) | NULL
    -Note | TEXT | NULL
    -?Classe | VARCHAR(11) | NULL
    -?Colore | VARCHAR(20) | NULL
    -?Tappezzeria | VARCHAR(50 | NULL
