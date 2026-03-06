# prog-GEP


TITOLO
FantaVolley	



DESCRIZIONE
"Una piattaforma (sito/app) pensata per tutti gli amanti della pallavolo, dove puoi creare la tua squadra virtuale, partecipare a tornei a premi e vivere l’emozione del fantasy sport applicato al mondo della pallavolo.
Scegli i migliori giocatori della Superlega e delle principali competizioni, segui le loro performance in tempo reale e guadagna punti per scalare la classifica e vincere premi fantastici.

La piattaforma monetizza attraverso tornei premium a pagamento con montepremi reali, abbonamenti mensili per sbloccare funzionalità avanzate (come analisi, suggerimenti formazione e modifiche illimitate), e sponsorizzazioni da parte di brand sportivi partner."	



PROBLEMA
assenza di una piattaforma strutturata, aggiornata e ufficiale per la pallavolo in cui confrontarsi e affrontare altri appassionati.	"



TARGET
Fascia d’età: 14 – 45 anni
persone: appassionati di pallavolo (giocatori, tifosi, allenatori, studenti sportivi).
Casual player: utenti che partecipano a leghe tra amici per divertimento.
Competitor: utenti che puntano a classifiche ufficiali e premi.
Società sportive / tornei locali: partner per tornei sponsorizzati o a tema.




COMPETITORS
"	I principali competitors sono piattaforse/app che si occupano della stessa tipologia di idea, ma
riguardante altri sport come basket o calcio, quindi come FantaCalcio, Dunkest e Sorare."	



TAGLINE

“La passione per la pallavolo diventa strategia. Gioca, analizza, vinci.”
oppure
“Fantavolley: il fantasy game dedicato alla vera pallavolo.”

TECNOLOGIE
Per supportare una piattaforma fantasy sport scalabile e ricca di dati statistici, è stato selezionato uno stack tecnologico moderno:
Frontend
Next.js (React) + Tailwind CSS → interfaccia veloce, responsive e moderna
Backend
Node.js con NestJS o Express → gestione API, logica di gioco e calcolo punteggi
Database
PostgreSQL → dati utenti, squadre fantasy e partite
Redis → cache per statistiche e classifiche in tempo reale
Autenticazione
OAuth 2.0 / JWT con Auth0 o Firebase Auth → login sicuro
Pagamenti
Stripe → gestione abbonamenti premium e rinnovi
Raccolta dati sportivi
API sportive (Volley Data API o scraping federazioni) → risultati, statistiche e prestazioni giocatori
Storage e distribuzione
Amazon S3 + Cloudflare CDN → immagini, asset e distribuzione veloce
Hosting e cloud
AWS / Google Cloud → scalabilità e affidabilità
Sicurezza
HTTPS
bcrypt per password
2FA opzionale
Monitoraggio e analytics
Sentry → gestione errori
Google Analytics / Mixpanel → analisi comportamento utenti
CI/CD e versioning
GitHub + GitHub Actions → deployment automatico





Analisi dei Requisiti
Descrizione dei requisiti

Fantavolley è una piattaforma online che consente agli utenti di partecipare a un fantasy game dedicato alla pallavolo, creando squadre virtuali composte da giocatori reali.

Gli utenti possono registrarsi alla piattaforma, effettuare il login e recuperare la password in caso di smarrimento. Una volta autenticati, possono gestire il proprio profilo e accedere alle funzionalità del gioco.

Ogni utente può creare o partecipare a leghe fantasy, sia pubbliche sia private, dove competere con altri utenti. Durante la fase iniziale della lega viene effettuata la creazione della squadra, selezionando i giocatori disponibili secondo regole stabilite (budget o draft).

Le prestazioni dei giocatori reali nelle partite ufficiali vengono convertite in punteggi fantasy, che aggiornano automaticamente le classifiche delle leghe.

La piattaforma offre inoltre analisi statistiche avanzate, consultabili dagli utenti, che includono prestazioni dei giocatori, andamento delle squadre e suggerimenti per la formazione.

Il modello economico della piattaforma prevede abbonamenti premium, che offrono funzionalità aggiuntive come statistiche avanzate, analisi predittive e report personalizzati. Questi vantaggi non alterano il bilanciamento del gioco, ma forniscono solo strumenti informativi.

Gli amministratori possono gestire il sistema attraverso un pannello dedicato, dove controllano i dati dei giocatori, aggiornano i calendari delle partite e monitorano il corretto funzionamento della piattaforma.

Il sistema deve garantire prestazioni elevate, sicurezza dei dati, scalabilità e compatibilità multipiattaforma, offrendo un’esperienza semplice e intuitiva per tutti gli utenti.

Elenco Riassuntivo Requisiti
Funzionali

Registrazione, login e recupero password
Gestione del profilo utente
Creazione e gestione della squadra fantasy
Partecipazione a leghe pubbliche o private
Aggiornamento automatico dei punteggi in base alle partite reali
Visualizzazione classifiche e risultati
Consultazione statistiche dei giocatori
Suggerimenti per la formazione basati sui dati
Gestione abbonamenti premium
Accesso alle analisi avanzate per utenti premium
Accesso amministratore per gestione dati e sistema



## User Story

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


Non Funzionali

Interfaccia chiara e intuitiva
Tempi di risposta rapidi
Alta disponibilità del servizio
Compatibilità multipiattaforma (web e mobile)
Scalabilità per gestire molti utenti
Codice modulare e manutenibile
Protezione dei dati personali

Di Dominio

Utilizzo di dati ufficiali delle partite di pallavolo
Calcolo dei punteggi basato su prestazioni reali dei giocatori
Sistema economico basato su abbonamenti premium non competitivi
Rispetto delle normative sulla privacy (GDPR)
Protezione dei dati e sicurezza delle transazioni
