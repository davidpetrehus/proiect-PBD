# Diagrama ER - Sistem Preluare Comenzi


erDiagram
    CLIENTI ||--o{ COMENZI : plaseaza
    COMENZI ||--|{ DETALII_COMENZI : contine
    PRODUSE ||--o{ DETALII_COMENZI : include
    COMENZI ||--o| LIVRARI : are

    CLIENTI {
        int id_client PK
        string nume
        string prenume
        string email
        string telefon
        string adresa
    }

    PRODUSE {
        int id_produs PK
        string denumire
        string descriere
        decimal pret
        int stoc
        string categorie
    }

    COMENZI {
        int id_comanda PK
        int id_client FK
        date data_comanda
        decimal valoare_totala
        string status_comanda
    }

    DETALII_COMENZI {
        int id_detaliu PK
        int id_comanda FK
        int id_produs FK
        int cantitate
        decimal pret_unitar
    }

    LIVRARI {
        int id_livrare PK
        int id_comanda FK
        date data_expedierii
        date data_livrarii
        string metoda_livrare
        string status_livrare
    }

