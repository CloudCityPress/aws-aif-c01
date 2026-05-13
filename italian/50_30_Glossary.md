# Glossario

Questo glossario raccoglie i termini tecnici, i nomi di servizi e i concetti chiave utilizzati in tutto il libro. Le voci sono ordinate alfabeticamente. Per i termini che non hanno un equivalente italiano consolidato, viene indicata la forma in uso nella letteratura tecnica italiana, seguita da una breve spiegazione in italiano. Per i servizi AWS e i nomi propri, il termine inglese originale è mantenuto invariato.

---

## A

**accuratezza** — Misura di quanto spesso un modello di apprendimento automatico produce la previsione corretta su un insieme di esempi di test. Si distingue dalla precisione (precision), che misura la proporzione di previsioni positive effettivamente corrette.

**addestramento** — Il processo mediante il quale un modello di apprendimento automatico apprende i pattern dai dati aggiornando i propri pesi in risposta agli errori. Vedere anche: pre-addestramento, fine-tuning.

**adattamento al dominio** — Tecnica di personalizzazione di un modello fondazionale per un settore o un insieme di argomenti specifici, attraverso la continua esposizione a dati di quel dominio senza modificarne la struttura fondamentale.

**agente** — Componente software che percepisce il proprio ambiente, pianifica una sequenza di azioni e le esegue autonomamente per raggiungere un obiettivo definito. Nell'IA generativa, gli agenti combinano un modello linguistico con strumenti e memoria per svolgere attività multi-passo.

**algoritmo** — Sequenza di istruzioni matematiche o logiche che un sistema informatico segue per risolvere un problema o produrre un risultato.

**allucinazione** — Fenomeno per cui un modello linguistico genera informazioni false, inventate o non supportate da fonti verificabili, presentandole come se fossero accurate. Le tecniche di grounding (come la generazione aumentata dal recupero) riducono questo rischio.

**API (Interfaccia di Programmazione delle Applicazioni)** — Insieme di definizioni e protocolli che permette a due applicazioni software di comunicare tra loro. Nel contesto di questo libro, il termine "API" è usato nella forma inglese, ampiamente adottata nella letteratura tecnica italiana.

**apprendimento automatico (ML)** — Branca dell'intelligenza artificiale in cui i sistemi imparano dai dati e migliorano le proprie prestazioni senza essere esplicitamente programmati per ogni singolo compito.

**apprendimento auto-supervisionato** — Tecnica di addestramento in cui il modello genera i propri segnali di supervisione dai dati non etichettati, come nel caso della previsione della parola successiva nei modelli linguistici.

**apprendimento per rinforzo** — Paradigma di apprendimento automatico in cui un agente apprende una policy ottimale ricevendo ricompense o penalità in base alle azioni intraprese in un ambiente simulato.

**apprendimento semi-supervisionato** — Tecnica che combina un piccolo insieme di dati etichettati con una grande quantità di dati non etichettati per addestrare un modello, riducendo il costo dell'etichettatura manuale.

**apprendimento supervisionato** — Paradigma di addestramento in cui il modello apprende da coppie di input etichettati, cercando di produrre l'output corretto per ciascun esempio.

**audit** — Processo formale di esame e verifica dei controlli, delle configurazioni e delle operazioni di un sistema per determinarne la conformità a standard, policy o normative applicabili.

**autenticazione** — Processo di verifica dell'identità di un utente, sistema o servizio prima di consentire l'accesso a risorse protette.

**autorizzazione** — Processo di determinazione delle azioni che un utente o sistema autenticato è autorizzato a compiere su risorse specifiche.

**auto-attenzione** — Meccanismo interno all'architettura Transformer che permette al modello di pesare l'importanza di ogni parola in una sequenza rispetto a tutte le altre, catturando relazioni a lunga distanza nel testo.

**avvio a freddo** — Ritardo iniziale che si verifica quando un endpoint di inferenza serverless deve allocare le risorse necessarie prima di poter rispondere alla prima richiesta.

---

## B

**base di conoscenza** — Archivio strutturato di informazioni dominio-specifiche che un sistema RAG consulta al momento dell'inferenza per arricchire i propri output con dati aggiornati e verificabili.

**benchmark** — Insieme standardizzato di test e metriche usato per confrontare le prestazioni di diversi modelli o sistemi in condizioni controllate e riproducibili.

**bias / distorsione** — Errore sistematico nelle previsioni di un modello che può derivare da dati di addestramento non rappresentativi, da scelte di progettazione del modello o da obiettivi di addestramento mal formulati. Il bias può produrre trattamenti iniqui di determinati gruppi demografici.

---

## C

**campionamento a nucleo** — Tecnica di campionamento (detta anche top-p) in cui il modello considera solo i token il cui potenziale cumulativo supera una soglia p, bilanciando diversità e coerenza dell'output.

**catena del pensiero** — Tecnica di prompt engineering in cui si guida il modello a produrre passaggi di ragionamento intermedi prima di fornire la risposta finale, migliorando l'accuratezza su problemi complessi.

**caso d'uso** — Applicazione specifica di una tecnologia o di un sistema per soddisfare un'esigenza aziendale o operativa definita.

**chatbot** — Applicazione software che simula una conversazione con gli utenti in linguaggio naturale, tipicamente per rispondere a domande, assistere nei processi o automatizzare attività ripetitive.

**classificazione** — Compito di apprendimento automatico in cui il modello assegna ogni input a una delle categorie predefinite, come la classificazione di email in "spam" o "non spam".

**clustering** — Tecnica di apprendimento non supervisionato che raggruppa gli esempi in base alla loro somiglianza, senza usare etichette predefinite.

**complessità del modello** — Misura del numero di parametri e della capacità rappresentativa di un modello. I modelli più complessi possono apprendere pattern più ricchi ma sono maggiormente soggetti a overfitting.

**computer vision (visione artificiale)** — Branca dell'IA che permette ai sistemi di interpretare e analizzare informazioni visive, come immagini e video, per compiti quali il riconoscimento di oggetti o la classificazione di scene.

**conformità** — Stato in cui un sistema, un processo o un'organizzazione rispetta i requisiti definiti da leggi, normative, standard di settore o policy interne applicabili.

**contesto** — Insieme delle informazioni fornite a un modello linguistico all'interno della finestra di contesto in una singola sessione di inferenza, incluse istruzioni di sistema, storia della conversazione e documenti di riferimento.

**crittografia** — Tecnica matematica che trasforma i dati in una forma illeggibile per chiunque non disponga della chiave di decrittazione appropriata, proteggendo la riservatezza dei dati a riposo e in transito.

**crittografia a riposo** — Protezione dei dati archiviati attraverso la loro cifratura, in modo che siano illeggibili anche se l'archiviazione fisica o logica viene compromessa.

**crittografia in transito** — Protezione dei dati mentre vengono trasmessi tra sistemi, tipicamente attraverso il protocollo TLS, impedendone l'intercettazione da parte di terzi.

---

## D

**dashboard** — Interfaccia visiva che aggrega e presenta metriche, allarmi e stati operativi in modo sintetico, permettendo il monitoraggio rapido di sistemi e processi.

**data drift** — Variazione nel tempo della distribuzione statistica dei dati in input a un modello in produzione rispetto alla distribuzione su cui il modello è stato addestrato, con conseguente possibile degrado delle prestazioni.

**data lake** — Archivio centralizzato che consente di archiviare grandi volumi di dati strutturati e non strutturati nella loro forma originale, senza richiedere una struttura predefinita al momento dell'ingestione.

**dataset** — Raccolta organizzata di dati utilizzata per addestrare, validare o testare un modello di apprendimento automatico.

**dati etichettati** — Dati di addestramento per cui la risposta corretta (etichetta) è stata annotata manualmente o automaticamente, utilizzati nell'apprendimento supervisionato.

**dati non etichettati** — Dati per cui non esiste un'etichetta predefinita, utilizzati in approcci non supervisionati o auto-supervisionati.

**dati non strutturati** — Informazioni che non seguono un formato tabellare predefinito, come testo libero, immagini, audio o video.

**dati strutturati** — Informazioni organizzate in un formato rigido e predefinito, come righe e colonne in un database relazionale.

**dati di serie temporali** — Sequenze di misurazioni ordinate cronologicamente, utilizzate per analisi di trend, rilevamento di anomalie e previsione.

**deep learning** — Sottobranca dell'apprendimento automatico che usa reti neurali con molti livelli nascosti per apprendere rappresentazioni gerarchiche dei dati.

**deriva del modello** — Fenomeno per cui le prestazioni di un modello in produzione peggiorano nel tempo a causa di cambiamenti nei dati di input o nel contesto operativo rispetto alle condizioni di addestramento.

**diffusione, modello di** — Architettura generativa che crea nuovi dati (ad esempio immagini) imparando a invertire un processo di aggiunta progressiva di rumore, producendo output di alta qualità a partire da rumore casuale.

**dimensionalità, riduzione della** — Tecnica che comprime la rappresentazione dei dati in uno spazio a minor numero di dimensioni mantenendo le informazioni più rilevanti, facilitando la visualizzazione e l'elaborazione.

---

## E

**embedding (rappresentazione vettoriale)** — Rappresentazione numerica densa di un testo, un'immagine o un altro dato sotto forma di vettore in uno spazio ad alta dimensionalità, in cui elementi simili sono vicini tra loro. Gli embedding sono la base dei sistemi di ricerca semantica e di RAG.

**endpoint** — Indirizzo di rete o punto di accesso a un servizio software tramite API, come l'URL di un modello di inferenza ospitato su Amazon Bedrock o SageMaker.

**epoca** — Una passata completa attraverso l'intero dataset di addestramento durante il processo di addestramento di un modello. Più epoche permettono al modello di affinare i propri pesi ma aumentano il rischio di overfitting.

**equità** — Proprietà di un sistema IA che garantisce trattamenti analoghi a individui o gruppi analoghi, minimizzando discriminazioni sistematiche basate su attributi protetti come genere, etnia o età.

---

## F

**feature engineering** — Processo di selezione, trasformazione e creazione di variabili di input a partire dai dati grezzi per migliorare le prestazioni di un modello di apprendimento automatico.

**fine-tuning** — Processo di addestramento aggiuntivo di un modello fondazionale preaddestrato su un dataset specifico del dominio o del compito, modificandone i pesi per adattarne il comportamento a un caso d'uso particolare.

**finestra di contesto** — Numero massimo di token che un modello linguistico può elaborare in una singola sessione, comprendendo sia l'input (prompt) sia l'output (risposta generata).

---

## G

**generazione aumentata dal recupero (RAG)** — Tecnica che combina la ricerca di documenti rilevanti da una base di conoscenza con la capacità generativa di un modello linguistico, riducendo le allucinazioni e aumentando l'accuratezza delle risposte.

**generazione di immagini** — Capacità di un modello generativo di creare immagini nuove a partire da descrizioni testuali o da altri input, tipicamente usando architetture a diffusione o GAN.

**generazione di testo** — Produzione di output testuale in linguaggio naturale da parte di un modello linguistico in risposta a un prompt o a un contesto fornito.

**governance** — Insieme di processi, policy, ruoli e responsabilità che un'organizzazione stabilisce per garantire che i propri sistemi operino in modo conforme, sicuro e allineato agli obiettivi aziendali.

**governance dei dati** — Disciplina che definisce le policy, i processi e i controlli per la gestione dei dati lungo il loro intero ciclo di vita, dalla raccolta all'archiviazione, alla conservazione e alla cancellazione.

**GPU** — Unità di elaborazione grafica (Graphics Processing Unit), largamente usata per l'addestramento e l'inferenza di modelli di apprendimento automatico grazie alla sua capacità di eseguire operazioni matematiche in parallelo.

**gradient boosting** — Tecnica di apprendimento automatico basata su ensemble che costruisce un modello predittivo combinando sequenzialmente molti modelli deboli, ciascuno dei quali corregge gli errori del precedente.

**guardrail / barriera di protezione** — Meccanismo di controllo applicato agli input e agli output di un sistema IA per bloccare contenuti dannosi, inappropriati o fuori ambito. Nel contesto di Amazon Bedrock, si riferisce ad Amazon Bedrock Guardrails, il servizio AWS dedicato.

---

## H

**hallucination** — Vedere: allucinazione.

---

## I

**IA agentiva** — Sistemi di intelligenza artificiale che operano con un elevato grado di autonomia, pianificando e concatenando azioni multiple per raggiungere obiettivi complessi, spesso interagendo con strumenti esterni, API e altre risorse.

**IA generativa (GenAI)** — Categoria di sistemi di intelligenza artificiale in grado di produrre contenuti nuovi, quali testo, immagini, audio o codice, sulla base di pattern appresi durante l'addestramento.

**IA responsabile** — Approccio allo sviluppo e all'operatività dei sistemi IA che pone al centro equità, trasparenza, robustezza, sicurezza, inclusività e veridicità, in linea con i valori etici e normativi dell'organizzazione.

**IAM (Gestione delle Identità e degli Accessi)** — Framework AWS per controllare chi può accedere a quali risorse e quali operazioni può compiere, attraverso utenti, ruoli, gruppi e policy. Il termine "IAM" è usato nella forma inglese nella letteratura tecnica italiana.

**inclusività** — Proprietà di un sistema IA progettato per funzionare correttamente e con equità per una gamma ampia e diversificata di utenti, indipendentemente da caratteristiche demografiche, culturali o di abilità.

**inferenza** — Processo mediante il quale un modello addestrato genera un output a partire da un input nuovo, applicando i pattern appresi durante l'addestramento a dati mai visti prima.

**inferenza asincrona** — Modalità di inferenza in cui la richiesta viene inviata a un modello e la risposta viene recuperata in un secondo momento, adatta a input di grandi dimensioni o a elaborazioni di lunga durata.

**inferenza in batch** — Elaborazione di un grande volume di richieste di inferenza in gruppi, ottimizzando l'utilizzo delle risorse di calcolo per task non interattivi.

**inferenza in tempo reale** — Modalità di inferenza in cui il modello risponde a ogni richiesta entro pochi millisecondi, adatta ad applicazioni interattive con utenti.

**inferenza serverless** — Modalità di inferenza in cui l'infrastruttura di calcolo viene allocata automaticamente al momento della richiesta e rilasciata subito dopo, eliminando la necessità di gestire server dedicati.

**informazioni di identificazione personale (PII)** — Qualsiasi dato che, da solo o combinato con altri, permette di identificare un individuo specifico, come nome, indirizzo, numero di identificazione o dati biometrici.

**informazioni sensibili** — Dati che richiedono protezione speciale per ragioni legali, normative o etiche, incluse le PII, i dati sanitari, le informazioni finanziarie e le credenziali di sicurezza.

**ingegneria del contesto** — Disciplina emergente che ottimizza l'intero contenuto della finestra di contesto, inclusi prompt di sistema, istruzioni, storia della conversazione e documenti recuperati, per massimizzare la qualità degli output del modello.

**iniezione di prompt** — Attacco in cui un utente malintenzionato inserisce istruzioni nella richiesta inviata a un modello con l'obiettivo di alterarne il comportamento, aggirare i guardrail o estrarre informazioni riservate.

**iperparametro** — Parametro di configurazione di un processo di addestramento che viene impostato prima che l'addestramento inizi, come il tasso di apprendimento, il numero di epoche o la dimensione del batch.

---

## J

**jailbreak** — Tentativo di manipolare un sistema IA generativo per farlo operare al di fuori dei limiti di sicurezza previsti, inducendolo a produrre contenuti vietati o a ignorare le istruzioni di sistema.

---

## L

**latenza** — Tempo trascorso tra l'invio di una richiesta a un sistema e la ricezione della risposta. Per i sistemi di inferenza, la latenza è una metrica critica per le applicazioni interattive.

**lineage dei dati** — Tracciabilità dell'origine, del percorso e delle trasformazioni subite da un dato lungo il suo ciclo di vita, dalla raccolta fino all'uso finale nel modello o nell'applicazione.

**linea di base** — Punto di riferimento stabilito misurando le prestazioni o le caratteristiche di un sistema in condizioni iniziali note, usato per confrontare lo stato futuro e rilevare variazioni significative.

---

## M

**meccanismo di attenzione** — Componente dell'architettura Transformer che permette al modello di focalizzarsi sulle parti più rilevanti dell'input quando genera ciascun elemento dell'output.

**modalità** — Tipo di dato che un modello è in grado di elaborare o generare, come testo, immagini, audio o video. Un modello "multimodale" gestisce più tipi di dato in modo integrato.

**modello fondazionale (FM)** — Modello di apprendimento automatico addestrato su enormi quantità di dati non etichettati, in grado di essere adattato a una vasta gamma di compiti attraverso il prompting o il fine-tuning.

**modello linguistico di grandi dimensioni (LLM)** — Tipo di modello fondazionale specializzato nell'elaborazione e nella generazione di testo, addestrato su corpora di linguaggio naturale di grandi dimensioni.

**modello personalizzato** — Versione di un modello fondazionale che è stata adattata tramite fine-tuning, pre-addestramento continuo o distillazione per rispondere a esigenze specifiche di un'organizzazione.

**moderazione dei contenuti** — Processo di revisione e filtraggio degli output di un sistema IA per garantire che rispettino standard di sicurezza, pertinenza e comportamento appropriato.

**monitoraggio** — Osservazione continua delle metriche operative e di qualità di un sistema IA in produzione, con lo scopo di rilevare anomalie, derive o violazioni delle policy.

**motore di raccomandazione** — Sistema che suggerisce agli utenti prodotti, contenuti o servizi sulla base delle loro preferenze storiche, del comportamento di utenti simili o di altri segnali contestuali.

**multimodale** — Capacità di un modello di elaborare o generare più di un tipo di dato contemporaneamente, come testo e immagini.

---

## N

**rete neurale** — Architettura computazionale ispirata alla struttura del cervello biologico, composta da strati di nodi (neuroni) connessi tra loro, utilizzata come base per la maggior parte dei sistemi di deep learning.

**NIST AI RMF** — AI Risk Management Framework del National Institute of Standards and Technology degli USA: framework volontario che definisce quattro funzioni (Govern, Map, Measure, Respond) per la gestione sistematica del rischio nei sistemi IA.

---

## O

**osservazione** — Pratica di monitoraggio continuo delle proprietà statistiche dei dati in ingresso a un sistema IA, volta a rilevare il data drift e ad attivare revisioni o aggiornamenti del modello prima che il degrado delle prestazioni diventi critico.

**overfitting (sovradattamento)** — Condizione in cui un modello impara troppo bene i pattern del dataset di addestramento, compreso il rumore, perdendo la capacità di generalizzare a nuovi dati. Il modello ha prestazioni eccellenti sul train set ma scadenti sul test set.

---

## P

**parametri di inferenza** — Valori configurabili che controllano il comportamento generativo di un modello durante l'inferenza, come temperatura, top-p, top-k e sequenza di stop.

**parametro** — Peso o bias appreso dal modello durante l'addestramento, archiviato nell'artifact del modello. I modelli fondazionali moderni contengono miliardi di parametri.

**peso** — Singolo valore numerico apprendibile in una rete neurale che controlla la forza della connessione tra due nodi. L'aggiornamento dei pesi durante l'addestramento è ciò che permette al modello di apprendere.

**pipeline** — Sequenza automatizzata di passaggi di elaborazione dei dati o di addestramento del modello, in cui l'output di ogni fase diventa l'input della successiva.

**pre-addestramento** — Fase iniziale di addestramento di un modello fondazionale su un corpus vastissimo di dati non etichettati, in cui il modello acquisisce una comprensione generale del linguaggio o del dominio.

**pre-addestramento continuo** — Tecnica che continua l'addestramento di un modello fondazionale già preaddestrato su nuovi dati specifici del dominio, aggiornandone le conoscenze senza modificare radicalmente la struttura.

**precisione (precision)** — Metrica di valutazione che misura la proporzione di previsioni positive di un modello che sono effettivamente corrette. Non va confusa con "accuratezza".

**prompt** — Input testuale fornito a un modello linguistico per guidarne la risposta. La qualità del prompt influenza direttamente la qualità e la pertinenza dell'output generato.

**prompt basato su ruolo** — Tecnica di prompt engineering in cui si assegna al modello un ruolo o una persona specifica (ad esempio "Sei un esperto di sicurezza informatica") per orientarne il tono e lo stile della risposta.

**prompt di sistema** — Istruzioni fornite al modello prima dell'input dell'utente, tipicamente invisibili all'utente finale, che definiscono il comportamento, la personalità e i vincoli del sistema IA.

**prompt engineering** — Disciplina che studia come formulare e strutturare gli input forniti a un modello linguistico per ottenere output di maggiore qualità, pertinenza e affidabilità.

---

## R

**RAG** — Vedere: generazione aumentata dal recupero.

**registrazione / logging** — Cattura automatica e archiviazione di eventi, chiamate API, accessi ai dati e output del modello per scopi di audit, monitoraggio e conformità.

**regressione** — Compito di apprendimento automatico in cui il modello prevede un valore numerico continuo, come il prezzo di un immobile o la temperatura futura.

**residenza dei dati** — Requisito normativo che impone che i dati rimangano archiviati ed elaborati entro una specifica area geografica, come lo Spazio Economico Europeo nel contesto del GDPR.

**robustezza** — Capacità di un sistema IA di mantenere prestazioni affidabili in presenza di input avversariali, rumore, dati fuori distribuzione o variazioni nelle condizioni operative.

---

## S

**scalabilità** — Capacità di un sistema di aumentare o diminuire le risorse di calcolo in risposta alla domanda, mantenendo prestazioni accettabili e costi proporzionali all'utilizzo effettivo.

**scheda del modello** — Documento strutturato che descrive le caratteristiche, le prestazioni, i limiti, i bias noti e le condizioni d'uso appropriate di un modello di apprendimento automatico, fornendo trasparenza alle parti interessate.

**sequenza di stop** — Token o stringa di caratteri che segnala al modello di smettere di generare output, usata per controllare la lunghezza e la struttura delle risposte.

**sintesi / riassunto** — Compito di elaborazione del linguaggio naturale in cui il modello produce una versione condensata di un testo più lungo, preservandone le informazioni essenziali.

**sistema multi-agente** — Architettura in cui più agenti IA autonomi collaborano o competono per risolvere compiti complessi che richiedono specializzazione, parallelismo o verifica incrociata.

**spiegabilità** — Proprietà di un sistema IA che permette di comprendere il ragionamento alla base delle sue previsioni o decisioni, espressa in termini comprensibili agli utenti e agli stakeholder non tecnici.

**suddivisione in blocchi (chunking)** — Processo di divisione di testi o documenti lunghi in segmenti di dimensioni gestibili prima dell'indicizzazione in un database vettoriale, per ottimizzare la ricerca semantica nei sistemi RAG.

**supervisione umana nel ciclo** — Approccio in cui operatori umani rivedono e validano gli output di un sistema IA prima che vengano utilizzati per prendere decisioni o intraprende azioni, garantendo un livello aggiuntivo di controllo.

---

## T

**temperatura** — Parametro di inferenza che controlla la casualità degli output di un modello linguistico. Valori bassi producono risposte più deterministiche e prevedibili; valori alti aumentano la creatività e la diversità.

**throughput / capacità di elaborazione** — Numero di richieste di inferenza che un sistema può gestire in un'unità di tempo, spesso espressa in token al secondo o richieste al minuto.

**token** — Unità base di elaborazione di un modello linguistico, corrispondente approssimativamente a una parola o a un insieme di caratteri. Il costo e la latenza dell'inferenza sono tipicamente misurati in token.

**tokenizzazione** — Processo di suddivisione di un testo in token prima che venga elaborato da un modello linguistico, usando un vocabolario definito durante l'addestramento.

**trasparenza** — Proprietà di un sistema IA che rende accessibili e comprensibili le informazioni sul suo funzionamento, le sue limitazioni e le sue decisioni agli utenti, agli auditor e agli stakeholder.

**transformer** — Architettura di rete neurale introdotta nel 2017 che utilizza il meccanismo di auto-attenzione per elaborare sequenze di dati in parallelo. La stragrande maggioranza dei modelli linguistici di grandi dimensioni è basata sull'architettura Transformer.

---

## U

**underfitting (sottoapprendimento)** — Condizione in cui un modello è troppo semplice per catturare i pattern nei dati di addestramento, producendo prestazioni scadenti sia sul train set sia sul test set.

---

## V

**valutazione del modello** — Processo sistematico di misurazione delle prestazioni di un modello rispetto a metriche definite, su dataset di test separati da quelli usati per l'addestramento.

**veridicità** — Proprietà di un sistema IA che produce output allineati a fatti verificabili e a fonti attendibili, minimizzando le allucinazioni e le affermazioni non supportate.

**visione artificiale** — Vedere: computer vision.

**VPC (Cloud Privato Virtuale)** — Rete virtuale isolata all'interno dell'infrastruttura AWS in cui è possibile lanciare risorse con controllo completo sulle impostazioni di rete, come la selezione degli indirizzi IP, la configurazione delle tabelle di routing e i gateway di rete.

---

## W

**watermark / filigrana digitale** — Segnale incorporato negli output di un sistema IA generativo che permette di identificarne l'origine artificiale, anche quando il testo o l'immagine vengono successivamente modificati.

---

## Z

**zero-shot** — Capacità di un modello linguistico di svolgere un compito senza esempi dimostrativi nel prompt, affidandosi esclusivamente alla comprensione implicita acquisita durante il pre-addestramento.
