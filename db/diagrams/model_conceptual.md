# Diagrama ER - Sistem Preluare Comenzi


```mermaid

flowchart TB
    CLIENT["CLIENT"]
    ANGAJAT["ANGAJAT"]
    COMANDA["COMANDA"]
    PRODUS["PRODUS"]
    CATEGORIE["CATEGORIE"]
    DETALIU["DETALIU_COMANDA"]
    TRANSPORT["TRANSPORT"]
    SOFER["SOFER"]

    R1{"PLASEAZA"}
    R2{"PREIA"}
    R3{"CONTINE"}
    R4{"APARE IN"}
    R5{"APARTINE"}
    R6{"ARE"}
    R7{"EFECTUEAZA"}

    CLIENT ---|"1"| R1
    R1 ---|"N"| COMANDA

    ANGAJAT ---|"1"| R2
    R2 ---|"N"| COMANDA

    COMANDA ---|"1"| R3
    R3 ---|"N"| DETALIU

    PRODUS ---|"1"| R4
    R4 ---|"N"| DETALIU

    CATEGORIE ---|"1"| R5
    R5 ---|"N"| PRODUS

    COMANDA ---|"1"| R6
    R6 ---|"0..1"| TRANSPORT

    SOFER ---|"1"| R7
    R7 ---|"N"| TRANSPORT

    classDef entity fill:#dbeafe,stroke:#2563eb,color:#111827,stroke-width:2px
    classDef relation fill:#fef3c7,stroke:#d97706,color:#111827,stroke-width:2px

    class CLIENT,ANGAJAT,COMANDA,PRODUS,CATEGORIE,DETALIU,TRANSPORT,SOFER entity
    class R1,R2,R3,R4,R5,R6,R7 relation

```
