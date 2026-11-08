# Aplicație pentru Preluarea și Prelucrarea Comenzilor
**Proiect Baze de Date**

## Scop
Scopul acestui proiect este realizarea unei baze de date pentru gestionarea activităților unui magazin sau ale unui furnizor. 
Baza de date va permite stocarea și organizarea informațiilor despre clienți, produse, comenzi și livrări într-un singur loc, astfel încât acestea să poată fi accesate rapid și ușor.
Prin utilizarea acestei baze de date se dorește evidența clară a produselor disponibile, a clienților care plasează comenzi și a livrărilor efectuate. 
De asemenea, sistemul va ajuta la urmărirea comenzilor de la momentul înregistrării până la livrarea acestora către client.
Implementarea unei astfel de soluții contribuie la o organizare mai bună a informațiilor, la reducerea greșelilor care pot apărea în gestionarea manuală a datelor și la economisirea timpului necesar pentru căutarea și actualizarea informațiilor. În acest mod, activitățile zilnice ale magazinului pot fi desfășurate mai eficient și mai ușor de administrat.

## Obiective
1. **Realizarea unei baze de date bine structurate**\. Crearea unei baze de date care să permită stocarea și organizarea informațiilor despre clienți, produse, categorii, angajați, comenzi și livrări\.
2. **Implementarea operațiilor CRUD**\. Dezvoltarea funcționalităților de adăugare, vizualizare, modificare și ștergere a înregistrărilor din baza de date\.
3. **Gestionarea clienților**\. Înregistrarea și administrarea informațiilor despre clienți, precum numele, prenumele, adresa, numărul de telefon și adresa de e\-mail\.
4. **Gestionarea produselor**\. Adăugarea și modificarea produselor comercializate de magazin, împreună cu informațiile despre denumire, descriere, preț, stoc și categorie\.
5. **Gestionarea comenzilor**\. Înregistrarea comenzilor primite de la clienți, cu păstrarea datei, a valorii totale și a angajatului care a preluat comanda\.
6. **Asocierea produselor cu comenzile**\. Permiterea introducerii mai multor produse într\-o singură comandă, cu specificarea cantității și a prețului fiecărui produs\.
7. **Calcularea valorii comenzilor**\. Calcularea automată a valorii totale pe baza produselor și cantităților introduse\.
8. **Verificarea și actualizarea stocurilor**\. Verificarea cantităților disponibile înainte de confirmarea unei comenzi și actualizarea stocului după înregistrarea acesteia\.
9. **Urmărirea statusului comenzilor**\. Actualizarea comenzilor în funcție de etapa în care se află, de la înregistrare până la finalizare sau anulare\.
10. **Gestionarea livrărilor și a transportului**\. Înregistrarea informațiilor despre livrări, inclusiv adresa de destinație, data expedierii, data estimată a livrării, costul transportului și statusul livrării\.
11. **Gestionarea șoferilor**\. Evidența șoferilor și repartizarea acestora pentru efectuarea livrărilor\.
12. **Facilitarea căutării și filtrării informațiilor**\. Identificarea rapidă a clienților, produselor, comenzilor și livrărilor pe baza unor criterii specifice\.
13. **Asigurarea integrității datelor**\. Utilizarea cheilor primare, a cheilor externe și a regulilor de validare pentru menținerea corectitudinii informațiilor\.
14. **Asigurarea securității datelor**\. Limitarea accesului la operațiile disponibile în funcție de utilizator și protejarea informațiilor stocate în baza de date\.

## Structura Proiectului
- `docs/`: Documentația proiectului
- `db/`: Scripturi SQL și diagrame
- `app/`: Aplicația practică conectată la BD
- `teste/`: Scripturi pentru testarea constrângerilor
