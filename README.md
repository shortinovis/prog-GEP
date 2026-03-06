#  FantaVolley

##  Descrizione

**FantaVolley** è una piattaforma (web/app) pensata per tutti gli amanti della pallavolo, dove è possibile creare la propria **squadra virtuale**, partecipare a **leghe e tornei a premi** e vivere l’esperienza del **fantasy sport applicato alla pallavolo**.

Gli utenti possono selezionare i migliori giocatori della **Superlega** e delle principali competizioni, monitorare le loro performance in tempo reale e guadagnare punti per scalare la classifica.

###  Modello di monetizzazione

La piattaforma genera ricavi attraverso:

- **Tornei premium a pagamento** con montepremi reali
- **Abbonamenti mensili** per funzionalità avanzate
- **Sponsorizzazioni e partnership** con brand sportivi

Gli abbonamenti permettono di sbloccare:

- Analisi statistiche avanzate
- Suggerimenti per la formazione
- Modifiche illimitate alla squadra
- Report personalizzati sulle prestazioni

---

#  Problema

Attualmente esiste **una forte mancanza di piattaforme dedicate alla pallavolo** nel mondo dei fantasy sport.

Mentre sport come calcio e basket hanno numerose applicazioni e community attive, la pallavolo non dispone ancora di una **piattaforma strutturata, aggiornata e competitiva** dove gli appassionati possano:

- confrontarsi tra loro
- creare squadre fantasy
- partecipare a competizioni e tornei

**FantaVolley nasce per colmare questa lacuna.**

---

#  Target

### Fascia d'età
**14 – 45 anni**

### Utenti principali

-  **Appassionati di pallavolo** (giocatori, tifosi, allenatori)
-  **Studenti e praticanti sportivi**
-  **Casual players** che vogliono giocare con amici
-  **Competitors** interessati a classifiche e tornei ufficiali

### Partner potenziali

- Società sportive
- Organizzatori di tornei locali
- Brand sportivi

---

#  Competitors

Il panorama attuale offre diverse piattaforme di **fantasy sport**, ma nessuna è focalizzata esclusivamente sulla **pallavolo con analisi statistiche avanzate e tornei dedicati**, come proposto da **FantaVolley**.

Principali piattaforme concorrenti:

- Fantacalcio
- Dunkest
- Sorare
- Volleyball Fantasy League

---

##  Analisi Comparativa

|  Caratteristica |  Importanza |  FantaVolley (P.) |  Fantacalcio |  Dunkest |  Sorare |  Volleyball Fantasy League |
|------------------|--------------|--------------------|---------------|------------|-----------|------------------------------|
| Fantasy sport dedicato alla pallavolo | 🔥 High | 🟢 Interamente dedicato alla pallavolo | 🔴 Solo calcio | 🔴 Solo basket | 🔴 Solo calcio | 🟠 Parzialmente |
| Creazione squadre fantasy | 🔥 High | 🟢 Squadre personalizzate | 🟢 Disponibile | 🟢 Disponibile | 🟢 Disponibile | 🟢 Disponibile |
| Leghe private tra amici | 🔥 High | 🟢 Supportate | 🟢 Supportate | 🟢 Supportate | 🟠 Limitate | 🟠 Limitate |
| Tornei ufficiali con premi | 🔥 High | 🟢 Tornei dedicati alla pallavolo | 🟠 Alcuni tornei | 🟢 Presente | 🟢 Presente | 🔴 Assente |
| Analisi statistiche avanzate | 🔥 High | 🟢 Analisi dettagliate e predittive | 🟠 Statistiche base | 🟢 Statistiche avanzate | 🟠 Limitate | 🔴 Molto limitate |
| Suggerimenti automatici formazione | 🔥 High | 🟢 Basati su dati e performance | 🔴 Assenti | 🟠 Limitati | 🔴 Assenti | 🔴 Assenti |
| Aggiornamento punteggi in tempo reale | 🔥 High | 🟢 Aggiornamento automatico | 🟢 Presente | 🟢 Presente | 🟢 Presente | 🟠 Non sempre puntuale |
| Abbonamenti premium | 🔥 High | 🟢 Funzionalità avanzate e analisi | 🔴 Non previsti | 🟠 Limitati | 🟢 Carte premium | 🔴 Assenti |
| Sistema equo senza vantaggi competitivi | 🔥 High | 🟢 Premium solo informativo | 🟢 Equilibrato | 🟠 Alcuni vantaggi | 🔴 Carte rare influenzano | 🟢 Sistema semplice |
| Disponibilità multipiattaforma | 🔥 High | 🟢 Web e mobile | 🟢 Web e mobile | 🟢 Mobile | 🟢 Web e mobile | 🟠 Limitato |
| Community e interazione utenti | 🟡 Moderate | 🟢 Leghe, chat e competizioni | 🟢 Community ampia | 🟠 Limitata | 🟠 Limitata | 🔴 Quasi assente |

---

#  Tagline

> **“La passione per la pallavolo diventa strategia. Gioca, analizza, vinci.”**

oppure

> **“FantaVolley: il fantasy game dedicato alla vera pallavolo.”**

---

#  Tecnologie

Per supportare una piattaforma fantasy sport scalabile e basata su dati statistici è stato selezionato uno stack moderno.

## Frontend
- **Next.js (React)**
- **Tailwind CSS**

Interfaccia moderna, veloce e completamente responsive.

## Backend
- **Node.js**
- **NestJS / Express**

Gestione API, logica di gioco e calcolo dei punteggi.

## Database
- **PostgreSQL** → dati utenti, squadre fantasy, leghe e partite  
- **Redis** → cache per statistiche e classifiche in tempo reale

## Autenticazione
- OAuth 2.0
- JWT
- Auth0 / Firebase Auth

## Pagamenti
- **Stripe**

Gestione abbonamenti premium e rinnovi automatici.

## Raccolta dati sportivi
- API sportive
- integrazione con dati federazioni
- scraping di risultati ufficiali

## Storage e distribuzione
- **Amazon S3**
- **Cloudflare CDN**

Distribuzione veloce degli asset.

## Hosting e Cloud
- **AWS**
- **Google Cloud**

Scalabilità e alta affidabilità.

## Sicurezza

- HTTPS
- bcrypt per hashing password
- autenticazione a due fattori (2FA)

## Monitoraggio

- **Sentry** → monitoraggio errori
- **Google Analytics / Mixpanel** → analisi utilizzo piattaforma

## CI/CD

- **GitHub**
- **GitHub Actions**

Deployment automatico e versioning del codice.

---

#  Analisi dei Requisiti

## Descrizione

FantaVolley è una piattaforma online che consente agli utenti di partecipare a un **fantasy game dedicato alla pallavolo**, creando squadre virtuali composte da giocatori reali.

Gli utenti possono:

- registrarsi alla piattaforma
- effettuare il login
- recuperare la password

Una volta autenticati possono gestire il proprio profilo e utilizzare le funzionalità principali del gioco.

Gli utenti possono inoltre:

- creare o partecipare a **leghe fantasy**
- competere con altri utenti
- selezionare giocatori tramite **budget o draft**

Le prestazioni dei giocatori reali vengono convertite in **punteggi fantasy**, aggiornando automaticamente le classifiche delle leghe.

La piattaforma offre anche **analisi statistiche avanzate**, tra cui:

- performance dei giocatori
- andamento delle squadre
- suggerimenti per la formazione

Il modello economico prevede **abbonamenti premium** che offrono funzionalità avanzate senza alterare l’equilibrio del gioco.

Gli amministratori gestiscono il sistema tramite un **pannello di controllo dedicato**, dove possono:

- aggiornare i dati delle partite
- controllare il sistema
- monitorare l’attività della piattaforma

---

#  Requisiti Funzionali

- Registrazione, login e recupero password
- Gestione del profilo utente
- Creazione e gestione della squadra fantasy
- Partecipazione a leghe pubbliche o private
- Aggiornamento automatico dei punteggi
- Visualizzazione classifiche e risultati
- Consultazione statistiche giocatori
- Suggerimenti per la formazione
- Gestione abbonamenti premium
- Accesso ad analisi avanzate
- Accesso amministratore per gestione sistema

---

#  User Story

| Attore (Come...) | Requisito / Azione (Voglio...) | Beneficio (In modo da...) |
|------------------|--------------------------------|----------------------------|
| Utente | registrarmi alla piattaforma | creare un account e partecipare alle leghe |
| Utente | effettuare il login | accedere al mio profilo e alla mia squadra |
| Utente | recuperare la password | ripristinare l’accesso in caso di smarrimento |
| Utente | creare una squadra fantasy | partecipare al gioco |
| Utente | partecipare a una lega | competere con altri utenti |
| Utente | visualizzare statistiche dei giocatori | prendere decisioni migliori |
| Utente | modificare la formazione | ottimizzare i punteggi della squadra |
| Utente | consultare la classifica | monitorare le prestazioni nella lega |
| Utente | acquistare un abbonamento premium | ottenere analisi statistiche avanzate |
| Utente | ricevere suggerimenti sulla formazione | migliorare le strategie di gioco |
| Amministratore | accedere al pannello di controllo | gestire dati e sistema |
| Amministratore | aggiornare dati delle partite | mantenere le statistiche aggiornate |

---

#  Requisiti Non Funzionali

- Interfaccia chiara e intuitiva
- Tempi di risposta rapidi
- Alta disponibilità del servizio
- Compatibilità multipiattaforma (web e mobile)
- Scalabilità per gestire molti utenti
- Codice modulare e facilmente manutenibile
- Protezione dei dati personali

---

#  Requisiti di Dominio

- Utilizzo di dati ufficiali delle partite di pallavolo
- Calcolo dei punteggi basato su prestazioni reali dei giocatori
- Sistema economico basato su abbonamenti premium non competitivi
- Conformità al **GDPR**
- Protezione dei dati e sicurezza delle transazioni


---


#  use case UML

<img width="962" height="950" alt="image" src="https://github.com/user-attachments/assets/3d66fbda-b0cd-4fba-98d3-df028829bcb2" />


---


# WBS (Work Breakdown Structure)
Pianificazione dettagliata delle fasi di sviluppo e relativi costi:

<img width="910" height="679" alt="image" src="https://github.com/user-attachments/assets/8105943f-1d86-4e4e-bdce-f03fce3ef9cd" />


---

## Cronoprogramma del progetto


| Fase | Periodo | Attività principali |
|-----|-----|-----|
| 1. Analisi requisiti | Settimana 1 | Raccolta requisiti, definizione user stories, analisi funzionale |
| 2. Progettazione | Settimana 2-3 | Architettura sistema, progettazione database, wireframe UI |
| 3. Setup ambiente | Settimana 3 | Configurazione repository GitHub, setup backend e frontend |
| 4. Sviluppo autenticazione | Settimana 4 | Registrazione utenti, login, recupero password |
| 5. Gestione squadre | Settimana 5-6 | Creazione squadra fantasy, gestione rosa giocatori |
| 6. Sistema leghe | Settimana 7 | Creazione e partecipazione alle leghe |
| 7. Statistiche giocatori | Settimana 8 | Visualizzazione statistiche e dati partite |
| 8. Formazione squadra | Settimana 9 | Modifica formazione e calcolo punteggi |
| 9. Classifiche | Settimana 10 | Visualizzazione ranking delle leghe |
| 10. Funzionalità premium | Settimana 11 | Abbonamento premium e analisi avanzate |
| 11. Testing | Settimana 12 | Test funzionali, bug fixing |
| 12. Deploy | Settimana 13 | Pubblicazione applicazione e documentazione finale |


---

## Prototipo applicazione

https://fantavolley-champions.lovable.app


---

# Elevator Pitch – FantaVolley

**Cos'è FantaVolley?**  
FantaVolley è la prima piattaforma di fantasy sport dedicata esclusivamente alla pallavolo, pensata per appassionati, giocatori e tifosi. Gli utenti possono creare squadre virtuali con giocatori reali della Superlega e delle principali competizioni, partecipare a leghe pubbliche o private, e confrontarsi in tempo reale attraverso classifiche aggiornate, statistiche e analisi avanzate.

**Business Model e Monetizzazione**  
La piattaforma genera ricavi attraverso tre canali principali:  
1. **Tornei premium a pagamento**: eventi speciali con montepremi reali per incentivare la competizione e l’engagement.  
2. **Abbonamenti mensili premium**: accesso a funzionalità avanzate come analisi statistiche, suggerimenti per la formazione, report personalizzati e modifiche illimitate della squadra. Questi strumenti forniscono vantaggi informativi senza alterare l’equilibrio competitivo.  
3. **Sponsorizzazioni e partnership con brand sportivi**: inserimento di contenuti e promozioni in linea con l’esperienza di gioco.

**Vantaggio Competitivo**  
FantaVolley si distingue dai competitor perché è interamente dedicata alla pallavolo, offrendo:  
- Aggiornamenti in tempo reale dei punteggi basati sulle prestazioni reali dei giocatori.  
- Analisi predittive e statistiche dettagliate per migliorare le strategie di gioco.  
- Possibilità di partecipare a leghe personalizzate tra amici o con utenti di tutto il mondo.  
- Esperienza multipiattaforma, sicura e priva di pubblicità invasive.

**Richiesta di Investimento e Pianificazione**  
Per avviare il progetto, stimiamo un investimento iniziale di circa **€30.000**, destinato a: sviluppo backend e frontend, integrazione API sportive, infrastruttura cloud, sicurezza e campagne di marketing iniziali.  
Il piano prevede un lancio beta entro 4 mesi, con monitoraggio dell’engagement e scaling progressivo della piattaforma.

**Perché scegliere FantaVolley**  
Scegliere FantaVolley significa investire nella **prima piattaforma di fantasy sport per la pallavolo**, con un modello economico chiaro, scalabile e trasparente, e con un pubblico target altamente motivato. È un progetto con forte potenziale di crescita, sia per il mercato italiano che internazionale, grazie a un’esperienza utente innovativa e coinvolgente.
