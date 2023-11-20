# Manager-de-Organizatii-si-Fondatori-Integrat-cu-Crunchbase
Project: 

Obiectiv General

• Dezvoltarea unei aplicații cu back-end RESTful și front-end SPA.

• Accesarea datelor într-o bază relațională prin intermediul unui API de persistență.

• Utilizarea datelor expuse de serviciul extern Crunchbase pentru informații suplimentare.

Componente Cheie

Entități în Bază de Date

• Două entități: "Organizație" (părinte) și "Fondator" (copil).

• Stocate într-o bază relațională.

• Accesate printr-un ORM.

Operații REST

• Operații CRUD expuse pentru entități prin intermediul unei interfețe REST.

• Exemplu: GET /organizations, POST /founders.

Front-end SPA

• Interfață utilizator atractivă și intuitivă.

• Dezvoltată cu un framework bazat pe componente (React.js sau Angular 2.0).

Structură de Proiect

Back-end

• models/: Modele pentru entitățile Organizație și Fondator.

• controllers/: Controlori pentru operațiile legate de Organizații și Fondatori.

• routes/: Rute pentru operațiile legate de Organizații și Fondatori.

• services/: Servicii pentru interacțiunea cu baza de date și, opțional, Crunchbase.

• app.js: Punct de intrare pentru back-end.

Front-end

• src/

• components/: Componente pentru interfața utilizator.

• services/: Servicii pentru comunicarea cu back-end-ul și, opțional, Crunchbase.

• views/: Vizualizări principale.

• App.js: Punct de intrare pentru front-end.

