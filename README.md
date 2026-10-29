
# Progetto individuale StartUp — EquiNex

*Where Every Rider Finds Their Perfect Equine Connection.*

EquiNex è un'applicazione progettata per mettere in contatto cavalieri (*Rider*), maneggi e istruttori, aiutando gli utenti a trovare il cavallo, il centro equestre o la lezione più adatti alle proprie esigenze, al proprio livello di esperienza e ai propri obiettivi.

Il nome **EquiNex** richiama l'espressione *Equus Nexus*: *Equus* significa «cavallo», mentre *Nexus* richiama il concetto di «legame» o «connessione». L'unione dei due termini rappresenta la missione della piattaforma: creare un punto d'incontro tra il mondo equestre e le persone che ne fanno parte.

L'obiettivo è offrire un unico spazio in cui i Rider possano cercare e confrontare le opportunità disponibili, mentre i maneggi possano presentare le proprie strutture, pubblicare cavalli e lezioni, gestire le disponibilità e ricevere richieste dagli utenti.

## Indice

- [1. Obiettivi del progetto](#1-obiettivi-del-progetto)
- [2. Problema e soluzione proposta](#2-problema-e-soluzione-proposta)
- [3. Nicchia di mercato e utenti target](#3-nicchia-di-mercato-e-utenti-target)
- [4. Funzionalità dell'applicazione](#4-funzionalità-dellapplicazione)
- [5. Casi d'uso UML](#5-casi-duso-uml)
- [6. Stato di sviluppo delle funzionalità](#6-stato-di-sviluppo-delle-funzionalità)
- [7. Requisiti non funzionali e di dominio](#7-requisiti-non-funzionali-e-di-dominio)
- [8. Analisi dei competitor](#8-analisi-dei-competitor)
- [9. Struttura del repository](#9-struttura-del-repository)
- [10. Documentazione di riferimento](#10-documentazione-di-riferimento)

## 1. Obiettivi del progetto

EquiNex nasce con l'obiettivo di semplificare la ricerca di attività e servizi equestri attraverso una piattaforma che tenga conto delle caratteristiche e delle necessità di ogni Rider.

Gli obiettivi principali sono:

- Facilitare la ricerca di maneggi, cavalli e lezioni.
- Permettere di individuare attività compatibili con il livello di esperienza, le discipline praticate, le preferenze e le disponibilità.
- Offrire ai maneggi uno spazio per pubblicare e aggiornare le proprie offerte.
- Agevolare i contatti tra Rider e strutture equestri.
- Centralizzare le informazioni e la documentazione rilevante per i profili.
- Prevedere strumenti di verifica dei profili e di gestione delle segnalazioni.

## 2. Problema e soluzione proposta

La ricerca di un maneggio, di un cavallo o di una lezione può richiedere la consultazione di numerose fonti e il contatto diretto con diverse strutture.

EquiNex intende semplificare questo processo mettendo a disposizione funzionalità di ricerca, filtri e valutazione della compatibilità. In questo modo, il Rider può individuare più facilmente le opzioni che rispondono alle proprie esigenze, mentre il maneggio può gestire le proprie informazioni e ricevere richieste attraverso la piattaforma.

La proposta di valore si basa su tre elementi:

1. **Ricerca mirata:** individuare le opportunità in base a criteri specifici.
2. **Compatibilità:** confrontare le caratteristiche del Rider con quelle di cavalli, maneggi e lezioni.
3. **Connessione:** facilitare la comunicazione tra utenti e strutture equestri.

## 3. Nicchia di mercato e utenti target

La nicchia individuata per EquiNex è quella dei servizi digitali dedicati al mondo equestre, con particolare attenzione alla ricerca di attività e opportunità adatte alle esigenze dei cavalieri.

La seguente segmentazione rappresenta il target progettuale previsto, non una nicchia di mercato già validata tramite una ricerca di mercato.

| Target | Esigenza principale | Soluzione offerta |
|---|---|---|
| Rider principianti | Trovare cavalli e lezioni adatti alla propria esperienza | Filtri per livello e caratteristiche del cavallo |
| Rider intermedi ed esperti | Individuare attività e strutture coerenti con i propri obiettivi | Ricerca per disciplina, disponibilità e compatibilità |
| Maneggi e centri equestri | Far conoscere la propria struttura e le attività disponibili | Profilo della struttura e pubblicazione di cavalli e lezioni |
| Istruttori | Rendere visibili le proprie qualifiche e competenze | Gestione delle informazioni tramite il profilo del maneggio |
| Amministratori della piattaforma | Mantenere organizzati e controllati profili e contenuti | Gestione degli account, verifiche e segnalazioni |

**Nicchia da approfondire:** Rider che cercano lezioni o cavalli adatti al proprio livello e maneggi che vogliono rendere più visibili le proprie offerte. Per confermare questo posizionamento sarà necessario confrontarlo con le soluzioni già presenti sul mercato e con le esigenze degli utenti.

## 4. Funzionalità dell'applicazione

Le funzionalità elencate in questa sezione derivano dal documento dei requisiti del progetto. Rappresentano le funzionalità previste e non implicano che siano già tutte implementate.
![Elenco completo delle funzionalità e dei requisiti](./elenco-completo-delle-funzionalit-e-requisiti.png)

### 4.1 Registrazione e gestione degli account

- Creazione di un account.
- Registrazione tramite nome, email e password.
- Scelta del tipo di account.
- Login e recupero della password.
- Modifica dei dati personali e della password.
- Gestione delle preferenze.
- Logout ed eliminazione dell'account.

### 4.2 Profilo Rider

- Inserimento e modifica dei dati personali.
- Indicazione del livello di esperienza: principiante, intermedio o esperto.
- Selezione delle discipline equestri di interesse.
- Inserimento di esigenze e preferenze.
- Gestione delle disponibilità.
- Caricamento e aggiornamento della documentazione pertinente.
- Visualizzazione dello stato dei documenti e delle relative scadenze.

### 4.3 Profilo Maneggio e gestione degli istruttori

- Inserimento e modifica dei dati della struttura.
- Gestione di indirizzo, posizione, descrizione e contatti.
- Indicazione delle discipline praticate.
- Gestione delle informazioni sugli istruttori e delle relative qualifiche.
- Caricamento della documentazione amministrativa e assicurativa.
- Gestione dell'eventuale affiliazione FISE.
- Gestione delle certificazioni e delle scadenze.
- Visualizzazione dello stato di verifica del profilo.

**Nota progettuale:** nel documento dei requisiti è indicato che l'istruttore deve essere gestito dal maneggio e non disporre necessariamente di una gestione autonoma del proprio profilo. Questa scelta deve essere mantenuta coerente anche nei diagrammi UML e nell'implementazione.

### 4.4 Ricerca dei maneggi

- Ricerca per località.
- Visualizzazione dei maneggi compatibili.
- Consultazione delle informazioni della struttura.
- Visualizzazione delle discipline offerte.
- Consultazione dei contatti.
- Visualizzazione dello stato di verifica del profilo.

### 4.5 Ricerca dei cavalli

- Visualizzazione dei cavalli disponibili.
- Filtri per livello di esperienza del Rider.
- Filtri per disciplina.
- Consultazione delle caratteristiche del cavallo.
- Valutazione della compatibilità tra Rider e cavallo.

### 4.6 Ricerca delle lezioni

- Visualizzazione delle lezioni disponibili.
- Ricerca per disciplina.
- Ricerca per livello richiesto.
- Ricerca per disponibilità.
- Consultazione dei dettagli delle lezioni.
- Verifica della compatibilità tra gli orari del Rider e quelli proposti.

### 4.7 Filtri e sistema di compatibilità

Il sistema di ricerca prevede filtri basati su:

- Livello di esperienza.
- Disciplina.
- Disponibilità.
- Località o distanza.
- Tipologia di lezione.
- Compatibilità con le esigenze del Rider.

Il sistema di compatibilità ha lo scopo di confrontare le caratteristiche del Rider con quelle dei maneggi, dei cavalli e delle lezioni, così da evidenziare le opzioni potenzialmente più adatte.

### 4.8 Preferiti e contatti

- Salvataggio dei maneggi preferiti.
- Salvataggio dei cavalli preferiti.
- Salvataggio delle lezioni preferite.
- Invio di richieste ai maneggi.
- Ricezione e gestione delle richieste da parte dei maneggi.
- Notifiche relative a richieste, contatti, modifiche e disponibilità.

### 4.9 Gestione delle pubblicazioni e delle disponibilità

I maneggi devono poter:

- Aggiungere, modificare ed eliminare i cavalli pubblicati.
- Creare, modificare ed eliminare le lezioni.
- Inserire e aggiornare gli orari disponibili.
- Mantenere aggiornate le informazioni pubblicate.

### 4.10 Documentazione e verifiche

La gestione documentale prevista comprende, quando pertinente:

- Certificati di idoneità sportiva.
- Documentazione amministrativa della struttura, inclusa la SCIA quando richiesta.
- Documentazione assicurativa.
- Qualifiche e certificazioni degli istruttori.
- Tesseramento, affiliazione e autorizzazioni FISE, quando pertinenti.
- Date di scadenza e notifiche per i documenti in scadenza.
- Indicazione dello stato di verifica dei profili e della documentazione.

I documenti personali e sensibili devono essere accessibili soltanto agli utenti autorizzati e gestiti in modo sicuro.

### 4.11 Segnalazioni e amministrazione

Le funzionalità amministrative previste comprendono:

- Gestione degli utenti e dei profili.
- Gestione dei maneggi.
- Controllo delle segnalazioni.
- Gestione dei contenuti pubblicati.
- Verifica della documentazione caricata.
- Gestione dello stato di verifica degli account.

Gli utenti devono inoltre poter segnalare profili o contenuti non appropriati e informazioni errate.

## 5. Casi d'uso UML

I casi d'uso descrivono le interazioni tra gli attori e il sistema. Un caso d'uso comprende i possibili scenari relativi a una funzionalità, incluse le eventuali alternative e situazioni di errore.

### 5.1 Attori principali

| Attore | Responsabilità |
|---|---|
| Visitatore | Esplora le funzionalità pubbliche e può registrarsi |
| Rider | Gestisce il profilo, cerca maneggi, cavalli e lezioni, salva preferiti e invia richieste |
| Maneggio | Gestisce il profilo della struttura, gli istruttori, i cavalli, le lezioni e le disponibilità |
| Amministratore | Gestisce utenti, contenuti, segnalazioni e verifiche |

L'istruttore è considerato nella gestione del profilo del maneggio, secondo le note presenti nel documento dei requisiti. L'eventuale definizione di un attore autonomo dovrà essere coerente con la scelta progettuale definitiva.

### 5.2 Principali casi d'uso

| ID | Caso d'uso | Attore principale |
|---|---|---|
| UC-01 | Registrare un account | Visitatore |
| UC-02 | Effettuare il login | Utente registrato |
| UC-03 | Recuperare la password | Utente registrato |
| UC-04 | Gestire il profilo Rider | Rider |
| UC-05 | Gestire il profilo del maneggio | Maneggio |
| UC-06 | Cercare maneggi | Rider |
| UC-07 | Cercare cavalli | Rider |
| UC-08 | Cercare lezioni | Rider |
| UC-09 | Filtrare e confrontare le opzioni | Rider |
| UC-10 | Visualizzare una scheda dettagliata | Rider |
| UC-11 | Gestire i preferiti | Rider |
| UC-12 | Inviare una richiesta a un maneggio | Rider |
| UC-13 | Gestire le richieste ricevute | Maneggio |
| UC-14 | Pubblicare e gestire cavalli e lezioni | Maneggio |
| UC-15 | Gestire le disponibilità | Maneggio |
| UC-16 | Caricare e aggiornare documenti | Rider / Maneggio |
| UC-17 | Gestire le notifiche | Utente registrato |
| UC-18 | Segnalare un contenuto | Utente registrato |
| UC-19 | Gestire utenti e contenuti | Amministratore |
| UC-20 | Verificare la documentazione | Amministratore |

L'elenco costituisce una sintesi iniziale. I singoli casi d'uso dovranno essere descritti in modo più dettagliato, indicando precondizioni, flusso principale, alternative e postcondizioni.

### 5.3 Diagrammi UML

I diagrammi UML devono rappresentare gli attori, i casi d'uso e le relazioni tra essi. La documentazione dei diagrammi sarà conservata nel repository, separatamente dall'elenco completo dei requisiti.

## 6. Stato di sviluppo delle funzionalità

Per distinguere ciò che è previsto da ciò che è realmente disponibile, ogni funzionalità dovrà avere uno stato di avanzamento verificabile.

| Stato | Significato |
|---|---|
| Da implementare | La funzionalità è prevista, ma non è ancora stata realizzata |
| Implementata, da testare | Il codice è presente, ma non è stata completata la verifica |
| Implementata e verificata | La funzionalità è stata provata e soddisfa il requisito |
| Implementata parzialmente | È disponibile soltanto una parte del comportamento previsto |
| Non prevista | La funzionalità è stata esclusa dal progetto |

**Importante:** le colonne `F`, `NF` e `D` presenti nel foglio Excel servono a classificare i requisiti come funzionali, non funzionali o di dominio. Non indicano se una funzionalità sia stata implementata.

Di conseguenza, lo stato effettivo di ciascuna funzionalità dovrà essere verificato confrontando i requisiti con il codice e con i test dell'applicazione.

Per facilitare questa attività, si consiglia di mantenere una tabella di tracciabilità con almeno questi campi:

| Campo | Descrizione |
|---|---|
| ID | Codice univoco del requisito |
| Requisito | Descrizione della funzionalità o del vincolo |
| Tipologia | Funzionale, non funzionale o di dominio |
| Stato | Avanzamento effettivo |
| Test | Verifica eseguita o ancora necessaria |
| Note | Problemi, dipendenze o aspetti da completare |

## 7. Requisiti non funzionali e di dominio

Oltre alle funzionalità visibili all'utente, EquiNex deve rispettare requisiti relativi alla sicurezza, all'affidabilità e alle caratteristiche specifiche del settore equestre.

### 7.1 Requisiti non funzionali

Tra i principali requisiti individuati nel documento figurano:

- **Sicurezza:** protezione degli account e gestione sicura delle credenziali.
- **Privacy:** protezione dei dati personali e limitazione dell'accesso ai documenti sensibili.
- **Autorizzazioni:** accesso alle funzioni amministrative e alla documentazione soltanto da parte degli utenti autorizzati.
- **Affidabilità:** salvataggio corretto dei dati e mantenimento delle informazioni pubblicate.
- **Prestazioni:** restituzione dei risultati di ricerca in tempi brevi.
- **Usabilità:** interfaccia e filtri semplici da comprendere e utilizzare.
- **Aggiornamento:** disponibilità di informazioni coerenti con gli orari, le offerte e le scadenze effettive.

Questi requisiti dovranno essere verificati mediante controlli e test adeguati. Quando possibile, dovranno essere trasformati in criteri misurabili.

### 7.2 Requisiti di dominio

I requisiti di dominio dipendono dalle caratteristiche del settore equestre e dalle condizioni applicabili alle singole attività.

Tra gli aspetti considerati nel progetto:

- Classificazione del livello di esperienza del Rider.
- Discipline equestri offerte dai maneggi.
- Compatibilità tra cavallo e cavaliere.
- Requisiti di idoneità sportiva, quando richiesti.
- Documentazione amministrativa e assicurativa delle strutture.
- Qualifiche e certificazioni degli istruttori.
- Tesseramento e autorizzazioni FISE, quando pertinenti.
- Gestione delle scadenze e verifica dei documenti.

La documentazione necessaria può variare in base all'attività e alla situazione specifica. I requisiti del progetto non sostituiscono quindi la verifica delle norme e degli obblighi effettivamente applicabili.

## 8. Analisi dei competitor

L'analisi della concorrenza serve a confrontare EquiNex con le soluzioni già disponibili, individuando funzionalità comuni, limiti e possibili elementi distintivi.

Questa sezione è da completare con una ricerca documentata: nei materiali forniti non è presente un elenco verificato di competitor.

Per ogni competitor individuato, la ricerca dovrebbe raccogliere:

| Elemento | Cosa analizzare |
|---|---|
| Nome e link | Nome della piattaforma e sito ufficiale |
| Target | Cavalieri, maneggi, istruttori o altri utenti |
| Funzionalità | Ricerca, prenotazione, annunci, profili, contatti |
| Filtri | Livello, disciplina, località, disponibilità |
| Punti di forza | Funzioni particolarmente utili o ben realizzate |
| Limiti | Funzioni mancanti o aspetti migliorabili, verificati tramite fonti |
| Differenze rispetto a EquiNex | Elementi che distinguono le due soluzioni |

### 8.1 Possibili elementi distintivi

EquiNex intende differenziarsi attraverso la combinazione di:

- Ricerca di maneggi, cavalli e lezioni in un'unica piattaforma.
- Filtri basati sul livello, sulle discipline e sulle disponibilità.
- Valutazione della compatibilità tra Rider e offerte.
- Gestione centralizzata delle informazioni e della documentazione.
- Strumenti per facilitare i contatti tra Rider e maneggi.

Questi elementi rappresentano la proposta progettuale di EquiNex. Per considerarli vantaggi competitivi effettivi sarà necessario confrontarli con le funzionalità reali dei servizi concorrenti.

## 9. Struttura del repository

La struttura seguente è una proposta organizzativa da adattare ai file effettivamente presenti nel repository.

```text
EquiNex/
├── README.md
├── docs/
│   ├── requirements/
│   │   ├── specifica-requisiti.pdf
│   │   ├── elenco-funzionalita.xlsx
│   │   └── classificazione-requisiti.txt
│   ├── uml/
│   │   └── use-case-diagram.png
│   └── competitors/
│       └── analisi-competitor.md
└── src/
    └── ...
```

Il file `README.md` presenta il progetto e rimanda alla documentazione di dettaglio. Il foglio Excel contiene l'elenco completo dei requisiti, mentre la cartella `uml/` raccoglie i diagrammi dei casi d'uso. La cartella `competitors/` può essere utilizzata per conservare le fonti e i risultati dell'analisi della concorrenza.

I nomi e i percorsi indicati sono esemplificativi e devono essere allineati alla struttura reale del repository.

## 10. Documentazione di riferimento

La progettazione di EquiNex si basa sui seguenti materiali:

| Documento | Utilizzo |
|---|---|
| `Elenco completo delle funzionalità e requisiti.xlsx` | Elenco dei requisiti, classificazione F/NF/D e User Story |
| `SpecificaDeiRequisiti.pdf` | Riferimento teorico per la definizione dei requisiti e dei casi d'uso |
| `Classificatione-per-tipologia.txt` | Criteri per distinguere requisiti funzionali, non funzionali e di dominio |
| `Link-how-to-create-UML-Use-Case.txt` | Riferimento per la creazione dei diagrammi UML |

Per i diagrammi UML è inoltre disponibile il riferimento indicato nel file dedicato: [yUML — Use Case Diagram Samples](https://yuml.me/diagram/scruffy/usecase/samples).

---

## Attività da completare

- [ ] Verificare lo stato reale di ogni funzionalità confrontando i requisiti con il codice e i test.
- [ ] Individuare competitor reali e documentare le differenze con fonti verificabili.
- [ ] Allineare la struttura descritta nel README con i percorsi effettivi del repository.
- [ ] Completare i diagrammi UML e le descrizioni dei singoli casi d'uso.
