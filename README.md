# PHP MySQL Web Application

## Descrizione
Applicazione web multipagina sviluppata in PHP e MySQL, progettata per gestire utenti e servizi tramite un sistema di autenticazione e un pannello amministrativo.

Il progetto implementa funzionalità di backend e interazione con database, simulando una struttura tipica di applicazioni web reali.

---

## Funzionalità principali
- Registrazione utenti
- Login e logout con gestione sessioni
- Cambio password
- Area amministrativa protetta
- Gestione servizi (CRUD: creazione, modifica, visualizzazione)
- Ricerca servizi
- Navigazione multipagina

---

## Tecnologie utilizzate
- HTML, CSS
- PHP
- MySQL (XAMPP)
- Sessioni PHP per autenticazione

---

## Struttura del progetto
- `/` pagine pubbliche (homepage, contenuti)
- `/admin` gestione amministrativa
- file PHP per gestione utenti e servizi
- `Config.php` configurazione database

---

## Installazione
1. Clonare il repository
2. Avviare XAMPP (Apache + MySQL)
3. Importare il database tramite file `.sql`
4. Configurare i parametri di connessione in `Config.php`
5. Aprire il progetto su `http://localhost/`

---

## Possibili miglioramenti
- Implementazione hashing password (password_hash / password_verify)
- Miglioramento validazione input
- Ottimizzazione UI/UX
- Strutturazione MVC

---

## Autore
Niccolò Rivera
