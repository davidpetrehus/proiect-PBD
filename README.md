# Aplicație pentru Preluarea și Prelucrarea Comenzilor
**Proiect Baze de Date**

## Scop
Scopul acestui proiect este realizarea unei baze de date pentru gestionarea activităților unui magazin sau ale unui furnizor. 
Baza de date va permite stocarea și organizarea informațiilor despre clienți, produse, comenzi și livrări într-un singur loc, astfel încât acestea să poată fi accesate rapid și ușor.
Prin utilizarea acestei baze de date se dorește evidența clară a produselor disponibile, a clienților care plasează comenzi și a livrărilor efectuate. 
De asemenea, sistemul va ajuta la urmărirea comenzilor de la momentul înregistrării până la livrarea acestora către client.
Implementarea unei astfel de soluții contribuie la o organizare mai bună a informațiilor, la reducerea greșelilor care pot apărea în gestionarea manuală a datelor și la economisirea timpului necesar pentru căutarea și actualizarea informațiilor. În acest mod, activitățile zilnice ale magazinului pot fi desfășurate mai eficient și mai ușor de administrat.

## Obiective
1. Realizarea unei baze de date pentru gestionarea informațiilor – Crearea unei baze de date bine structurate, care să permită stocarea, organizarea și administrarea eficientă a informațiilor referitoare la clienți, produse, comenzi și livrări. Aceasta va reprezenta elementul central al sistemului de gestionare a activității magazinului sau furnizorului.

2. Implementarea operațiilor CRUD – Dezvoltarea funcționalităților necesare pentru Crearea, Citirea, Actualizarea și Ștergerea (CRUD) înregistrărilor din baza de date. Aceste operații vor permite administrarea simplă și rapidă a tuturor informațiilor, asigurând menținerea datelor la zi.

3. Înregistrarea și gestionarea informațiilor despre clienți – Crearea unei secțiuni dedicate evidenței clienților, în care să fie stocate informații precum numele, prenumele, adresa, numărul de telefon și adresa de e-mail. Sistemul va permite adăugarea de clienți noi, modificarea datelor existente și consultarea rapidă a informațiilor acestora.

4. Gestionarea informațiilor despre produse – Realizarea unei structuri care să permită înregistrarea și administrarea produselor comercializate de magazin sau oferite de furnizor. Pentru fiecare produs vor putea fi păstrate informații precum denumirea, descrierea, prețul, cantitatea disponibilă în stoc și categoria din care face parte.

5. Înregistrarea și administrarea comenzilor – Implementarea unui mecanism prin care să fie înregistrate comenzile plasate de clienți. Fiecare comandă va fi asociată unui anumit client și va conține informații despre produsele solicitate, cantitățile comandate, data plasării și valoarea totală a comenzii.

6. Asocierea comenzilor cu produsele comandate – Crearea unei legături între comenzile înregistrate și produsele disponibile în baza de date, astfel încât o comandă să poată conține unul sau mai multe produse. Această funcționalitate va permite evidențierea exactă a produselor comandate și a cantităților aferente fiecărei comenzi.

7. Urmărirea și actualizarea statusului comenzilor – Implementarea unui sistem de monitorizare a comenzilor, care să permită urmărirea etapelor prin care acestea trec, de la înregistrare până la finalizare. Statusurile pot include: comandă plasată, în curs de procesare, pregătită pentru livrare, expediată, livrată sau anulată.

8. Gestionarea informațiilor despre livrări – Crearea unei secțiuni dedicate administrării livrărilor, în care să fie înregistrate informații precum data expedierii, data estimată a livrării, metoda de transport, adresa de livrare și statusul livrării. Astfel, se va putea urmări mai ușor procesul de expediere a comenzilor către clienți.

9. Asigurarea relațiilor corecte între tabelele bazei de date – Stabilirea unor legături logice între tabelele dedicate clienților, produselor, comenzilor și livrărilor, prin utilizarea cheilor primare și a cheilor externe. Acest lucru va contribui la menținerea integrității datelor și la evitarea înregistrărilor incorecte sau incomplete.

10. Facilitarea căutării și filtrării informațiilor – Implementarea unor funcționalități de căutare și filtrare care să permită identificarea rapidă a informațiilor dorite, precum datele unui client, un anumit produs, o comandă sau o livrare. Căutările vor putea fi realizate pe baza unor criterii specifice, reducând timpul necesar accesării datelor.

11. Reducerea erorilor în administrarea datelor – Automatizarea și centralizarea proceselor de gestionare a informațiilor, cu scopul de a diminua greșelile care pot apărea în urma introducerii sau prelucrării manuale a datelor. Utilizarea unor reguli de validare și a relațiilor dintre tabele va contribui la creșterea corectitudinii informațiilor.

12. Organizarea eficientă a informațiilor – Structurarea bazei de date într-un mod logic și intuitiv, astfel încât informațiile să fie ușor de identificat, accesat și administrat. Organizarea eficientă va permite evitarea duplicării datelor și va facilita extinderea sistemului în funcție de necesitățile viitoare.

13. Asigurarea accesului rapid la informațiile necesare – Dezvoltarea unui sistem care să ofere utilizatorilor posibilitatea de a obține rapid datele necesare desfășurării activităților zilnice. Consultarea informațiilor despre clienți, produse, comenzi și livrări va contribui la eficientizarea procesului de lucru.

14. Îmbunătățirea procesului de gestionare a activității magazinului sau furnizorului – Integrarea tuturor informațiilor într-o singură bază de date va permite o administrare mai eficientă a activităților comerciale. Sistemul va facilita evidența comenzilor, monitorizarea produselor, gestionarea clienților și urmărirea livrărilor, contribuind la economisirea timpului și la îmbunătățirea organizării generale.

15. Asigurarea securității și a integrității datelor – Implementarea unor măsuri de protecție pentru prevenirea accesului neautorizat și a modificării accidentale a informațiilor. De asemenea, se urmărește păstrarea corectitudinii datelor și prevenirea pierderii acestora prin realizarea unor copii de siguranță.

## Structura Proiectului
- `docs/`: Documentația proiectului
- `db/`: Scripturi SQL și diagrame
- `app/`: Aplicația practică conectată la BD
- `teste/`: Scripturi pentru testarea constrângerilor
