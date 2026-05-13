# Glossar

Dieses Glossar versammelt die technischen Begriffe, Abkürzungen und Dienstnamen, die im gesamten Buch verwendet werden. AWS-Dienstnamen und Code-Bezeichner werden auf Englisch belassen, so wie sie in der AWS-Konsole und der offiziellen Dokumentation erscheinen. Bei jedem übersetzten Konzept ist das englische Äquivalent in Klammern angegeben, um das Nachschlagen in der englischsprachigen Originaldokumentation zu erleichtern.

---

## A

**AIF-C01** — Offizieller Code der Prüfung AWS Certified AI Practitioner. Wird in allen Kontexten auf Englisch belassen.

**agentische KI (agentic AI)** — KI-Systeme, die eigenständig Folgen von Aktionen planen und ausführen können, um mehrstufige Ziele zu erreichen, und dabei auf externe Werkzeuge und Datenquellen zugreifen.

**Algorithmus (algorithm)** — Eine definierte Menge von Anweisungen oder Regeln, die ein System befolgt, um ein Problem zu lösen oder eine Aufgabe auszuführen.

**Amazon Aurora** — Verwalteter relationaler Datenbankdienst von AWS, der mit MySQL und PostgreSQL kompatibel ist.

**Amazon Bedrock** — Verwalteter AWS-Dienst, der per API Zugang zu Basismodellen von Amazon und Drittanbietern bietet, einschließlich Werkzeugen für Anpassung, Guardrails, Agents und Knowledge Bases.

**Amazon Bedrock AgentCore** — AWS-Plattform zum Bereitstellen und Verwalten von KI-Agenten in der Produktion, einschließlich Identität, Autorisierung und dauerhafter Speicherung.

**Amazon Bedrock Agents** — Funktion von Amazon Bedrock, mit der KI-Agenten aufgebaut werden können, die mithilfe externer Werkzeuge und Datenquellen mehrstufige Aktionen planen und ausführen.

**Amazon Bedrock Guardrails** — Funktion von Amazon Bedrock, die Inhaltsfilter, gesperrte Themen, blockierte Wörter, Unterdrückung vertraulicher Informationen, kontextuelle Grundlagenprüfung und Schutz vor Prompt-Injektion auf Modelleingaben und -ausgaben anwendet.

**Amazon Bedrock Knowledge Bases** — Funktion von Amazon Bedrock, die Basismodelle mit externen Datenquellen verbindet und so Retrieval-Augmented Generation (RAG) ohne eigene Vektorinfrastruktur ermöglicht.

**Amazon CloudWatch** — AWS-Dienst für Überwachung und Beobachtbarkeit, der Metriken, Protokolle und Ereignisse von AWS-Ressourcen und Anwendungen erfasst.

**Amazon Comprehend** — AWS-Dienst zur Verarbeitung natürlicher Sprache, der Entitäten, Stimmungen, Themen und vertrauliche Daten wie personenbezogene Daten (PbD) in Text erkennt.

**Amazon EC2** — AWS-Cloud-Computing-Dienst, der skalierbare virtuelle Serverkapazität bereitstellt.

**Amazon ECS** — Vollständig verwalteter AWS-Dienst zur Container-Orchestrierung.

**Amazon Kendra** — Intelligenter AWS-Enterprise-Suchdienst, der Verarbeitung natürlicher Sprache nutzt, um präzise Antworten in internen Dokumenten zu finden.

**Amazon Lex** — AWS-Dienst zum Erstellen konversationeller Sprach- und Textschnittstellen (Chatbots und virtuelle Assistenten), der dieselbe Spracherkennungs- und NLP-Engine wie Alexa verwendet.

**Amazon Macie** — AWS-Datensicherheitsdienst, der Maschinelles Lernen einsetzt, um in Amazon S3 gespeicherte sensible Daten, darunter PbD und Anmeldeinformationen, automatisch zu erkennen und zu schützen.

**Amazon Neptune Analytics** — AWS-Graphdatenbank-Analysedienst mit integrierten Vektorsuchfunktionen.

**Amazon Nova** — Familie multimodaler Basismodelle von Amazon, die in Amazon Bedrock verfügbar sind, mit den Varianten Micro, Lite, Pro und Premier je nach dem Verhältnis zwischen Kosten und Leistungsfähigkeit.

**Amazon OpenSearch Service** — AWS-Such- und Analysedienst auf Basis von OpenSearch, der Vektorsuche für RAG-Anwendungsfälle unterstützt.

**Amazon Q** — Generativer KI-Assistent von AWS für Unternehmensexperten und Entwickler, mit Integration in Unternehmensdatenquellen.

**Amazon Quick** — AWS-Dienst für Business-Intelligence mit integrierten Funktionen für Generative KI, der Visualisierungen erstellt und Fragen zu Daten beantwortet.

**Amazon RDS** — Verwalteter relationaler AWS-Datenbankdienst, der verschiedene Datenbank-Engines unterstützt, darunter PostgreSQL mit pgvector-Erweiterung.

**Amazon Rekognition** — AWS-Computer-Vision-Dienst zur Bild- und Videoanalyse, einschließlich Objekterkennung, Gesichtserkennung und Inhaltsmoderation.

**Amazon S3** — AWS-Objektspeicherdienst mit hoher Langlebigkeit, Skalierbarkeit und differenzierten Zugriffskontrollen.

**Amazon SageMaker AI** — AWS-Plattform für Maschinelles Lernen, die den vollständigen Modell-Lebenszyklus abdeckt: Datenvorbereitung, Training, Feinabstimmung, Bewertung, Bereitstellung und Überwachung.

**Amazon SageMaker Clarify** — Komponente von Amazon SageMaker AI, die Verzerrungen in Daten und Modellen erkennt und Vorhersageerklärungen mithilfe von SHAP-Werten generiert.

**Amazon SageMaker Ground Truth** — AWS-Datenbeschriftungsdienst, der menschliche Annotatoren mit durch Maschinelles Lernen unterstützter Automatisierung kombiniert.

**Amazon Textract** — AWS-Dienst, der mithilfe von Maschinellem Lernen Text, Formulare und Tabellen aus gescannten Dokumenten extrahiert.

**Amazon Titan** — Familie von Basismodellen von Amazon, die in Amazon Bedrock verfügbar sind, einschließlich Amazon Titan Embeddings zur Erzeugung von Einbettungsvektoren.

**Amazon Transcribe** — AWS-Dienst zur automatischen Spracherkennung, der Audio in Text umwandelt.

**Amazon Translate** — AWS-Dienst für neuronale maschinelle Übersetzung.

**API (Programmierschnittstelle, Application Programming Interface)** — Softwarevertrag, der definiert, wie zwei Systeme miteinander kommunizieren. Im Kontext der Generativen KI ist die API der wichtigste Mechanismus, um Basismodelle aus Anwendungen heraus aufzurufen.

**asynchrone Inferenz (asynchronous inferencing)** — Inferenzmodus, bei dem eine Anfrage gesendet und das Ergebnis zu einem späteren Zeitpunkt abgerufen wird; geeignet für lange Eingaben oder die Stapelverarbeitung.

**Aufmerksamkeitsmechanismus (attention mechanism)** — Komponente der Transformer-Architektur, die es dem Modell ermöglicht, die Relevanz verschiedener Teile der Eingabe beim Erzeugen jedes Teils der Ausgabe zu gewichten.

**Ausgangswert / Basiswert (baseline)** — Satz von Referenzmetriken, der aus Trainingsdaten oder einem Zeitraum akzeptabler Leistung berechnet wird und dazu dient, Abweichungen im Produktionsbetrieb zu erkennen.

**AWS** — Amazon Web Services, Cloud-Computing-Plattform von Amazon.

**AWS Artifact** — AWS-Self-Service-Portal, über das Kunden Drittanbieter-Compliance-Zertifizierungen von AWS herunterladen können, darunter SOC-Berichte, ISO-Zertifizierungen und HIPAA-Partnerverträge.

**AWS Audit Manager** — AWS-Dienst, der die Erfassung von Compliance-Nachweisen automatisiert und diese in prüfungsfertige Berichte organisiert, die an Frameworks wie HIPAA, SOC 2, PCI DSS und ISO 27001 ausgerichtet sind.

**AWS Backup** — Zentralisierter AWS-Dienst zum Planen, Überwachen und Durchsetzen von Datensicherungs- und Aufbewahrungsrichtlinien mit unveränderlichen Wiederherstellungspunkten.

**AWS Certified AI Practitioner** — AWS-Zertifizierung auf Grundlagenniveau, die Kenntnisse zu KI- und ML-Konzepten, Generativer KI und relevanten AWS-Diensten nachweist.

**AWS CloudTrail** — AWS-Dienst, der jeden API-Aufruf an AWS-Dienste unveränderlich protokolliert und so einen Prüfpfad erstellt, der zeigt, wer was wann getan hat.

**AWS Config** — AWS-Dienst, der den Konfigurationsstatus von Ressourcen kontinuierlich aufzeichnet und deren Einhaltung von richtliniendefinierten Regeln bewertet.

**AWS IAM Identity Center** — AWS-Dienst zur zentralisierten Benutzerzugriffsverwaltung für mehrere AWS-Konten und -Anwendungen mit einmaligem Anmelden (Single Sign-On).

**AWS Key Management Service (KMS)** — Verwalteter AWS-Dienst zum Erstellen und Steuern der Verschlüsselungsschlüssel, die ruhende und übertragene Daten schützen.

**AWS Lambda** — Serverloser AWS-Computing-Dienst, der Code als Reaktion auf Ereignisse ausführt, ohne dass Server bereitgestellt oder verwaltet werden müssen.

**AWS Marketplace** — Digitaler AWS-Katalog, in dem Kunden Software und Dienste von Drittanbietern suchen, testen und kaufen können, einschließlich Basismodelle.

**AWS PrivateLink** — AWS-Netzwerktechnologie, die privaten Zugriff auf AWS-Dienste und Drittanbieterdienste aus einer VPC heraus ermöglicht, ohne den Datenverkehr dem öffentlichen Internet auszusetzen.

**AWS Secrets Manager** — AWS-Dienst zum sicheren Speichern, Rotieren und Abrufen von Anmeldeinformationen, API-Schlüsseln und anderen Geheimnissen.

**AWS Security Hub** — AWS-Dienst, der Sicherheitsbefunde aus Config, Inspector, Macie und anderen Diensten in einem zentralisierten Compliance-Dashboard zusammenführt.

**AWS Trusted Advisor** — AWS-Tool, das Kontokonfigurationen anhand bewährter Methoden in den Kategorien Sicherheit, Kosten, Leistung, Fehlertoleranz und Servicekontingente bewertet.

**AWS Well-Architected Framework** — AWS-Referenzrahmen, der bewährte Architekturpraktiken für den Aufbau von Cloud-Systemen entlang der Säulen betriebliche Exzellenz, Sicherheit, Zuverlässigkeit, Leistungseffizienz, Kostenoptimierung und Nachhaltigkeit beschreibt.

---

## B

**Basismodell (FM, foundation model)** — Umfangreiches ML-Modell, das auf großen und vielfältigen Datenmengen vortrainiert wurde und sich durch Feinabstimmung oder Prompting für viele nachgelagerte Aufgaben anpassen lässt.

**Batch-Inferenz (batch inferencing)** — Verarbeitung einer großen Anzahl von Inferenzanfragen in einem Stapel, um die Ressourcennutzung auf Kosten einer höheren Latenz zu optimieren.

**Benchmark** — Standardisierter Satz von Aufgaben oder Metriken, der zur Bewertung und zum Vergleich der Leistung von KI-Modellen verwendet wird. Beispiele: MMLU, HellaSwag, HumanEval.

**benutzerdefiniertes Modell (custom model)** — Basismodell, das mit eigenen Daten der Organisation feinabgestimmt oder angepasst wurde, um sich in einem bestimmten Bereich oder bei einer bestimmten Aufgabe spezifisch zu verhalten.

**beschriftete Daten (labeled data)** — Trainingsdaten, die sowohl die Eingabe als auch die zugehörige korrekte Ausgabe oder Beschriftung enthalten; erforderlich für das Überwachte Lernen.

**Bestärkendes Lernen (reinforcement learning)** — Maschinelles-Lernen-Paradigma, bei dem ein Agent durch den Erhalt von Belohnungen oder Strafen für seine Aktionen in einer Umgebung lernt.

---

## C

**Chain-of-Thought (Gedankenkettenführung)** — Prompt-Engineering-Technik, bei der das Modell aufgefordert wird, Schritt für Schritt zu denken, bevor es eine endgültige Antwort gibt, was die Genauigkeit bei komplexen Schlussfolgerungsaufgaben verbessert.

**Chatbot** — Softwareanwendung, die eine Konversation mit menschlichen Benutzern über Text oder Sprache simuliert, häufig auf Basis von NLP-Modellen aufgebaut.

**Computer Vision (CV)** — Bereich der Künstlichen Intelligenz, der es Systemen ermöglicht, Bilder und Videos zu interpretieren und zu analysieren.

---

## D

**Data Lake** — Zentrales Speicher-Repository, das strukturierte und unstrukturierte Daten in ihrem ursprünglichen oder transformierten Format in beliebigem Umfang enthält.

**Datenherkunft (data lineage)** — Lückenlose Aufzeichnung des Ursprungs von Daten, der durchlaufenen Transformationen und der Systeme, die sie genutzt haben, von der Entstehung bis zum Einsatz in einem KI-Modell.

**Datenpipeline (data pipeline)** — Automatisierte Abfolge von Schritten zum Verschieben, Transformieren und Laden von Daten von Quellen zu Verbrauchszielen.

**Datensatz (dataset)** — Geordnete Sammlung von Daten, die zum Trainieren, Validieren oder Bewerten von ML-Modellen verwendet wird.

**Datenverwaltung (data governance)** — Disziplin, die Verfügbarkeit, Verwendbarkeit, Integrität und Sicherheit der in einer Organisation eingesetzten Daten verwaltet und den vollständigen Lebenszyklus von der Entstehung bis zur Löschung abdeckt.

**Deep Learning** — Teilbereich des Maschinellen Lernens, der neuronale Netze mit vielen Schichten verwendet, um hierarchische Datenrepräsentationen zu erlernen.

**Diffusionsmodell (diffusion model)** — Generative Architektur, die lernt, einen schrittweisen Rauschhinzufügungsprozess umzukehren, um hochwertige Bilder oder andere Daten zu erzeugen. Es bildet die Grundlage von Systemen wie Stable Diffusion.

**Dimensionsreduktion (dimensionality reduction)** — Technik, die die Anzahl der Merkmale oder Dimensionen von Daten verringert und dabei die relevantesten Informationen beibehält.

---

## E

**Echtzeit-Inferenz (real-time inferencing)** — Inferenzmodus mit niedriger Latenz, der Ergebnisse sofort oder als kontinuierlichen Datenstrom zurückgibt und für interaktive Anwendungen geeignet ist.

**Einbettungsvektor (embedding)** — Umwandlung von Text, Bildern oder anderen Daten in einen hochdimensionalen Zahlenvektor, der semantische Beziehungen erfasst. Ermöglicht die Ähnlichkeitssuche in Vektordatenbanken.

**Empfehlungssystem (recommendation engine)** — ML-System, das auf der Grundlage von Nutzerverhalten und Verlaufsdaten relevante Elemente (Produkte, Inhalte, Aktionen) vorhersagt und vorschlägt.

**Epoche (epoch)** — Ein vollständiger Durchlauf durch den gesamten Trainingsdatensatz während des Modelltrainings.

**Erklärbarkeit (explainability)** — Fähigkeit eines KI-Systems, seine Vorhersagen in für Menschen verständlichen Begriffen zu beschreiben oder zu begründen.

---

## F

**Fairness** — Eigenschaft eines KI-Systems, die sicherstellt, dass seine Vorhersagen oder Empfehlungen keine ungerechtfertigt diskriminierenden Ergebnisse für Personengruppen auf der Grundlage geschützter Merkmale wie Rasse, Geschlecht oder Alter erzeugen.

**Feature-Engineering** — Prozess der Umwandlung von Rohdaten in informativere numerische Repräsentationen zur Verbesserung der Modellleistung.

**Feinabstimmung (fine-tuning)** — Prozess der Fortsetzung des Trainings eines vortrainierten Basismodells mit einem kleineren, spezialisierten Datensatz, um sein Verhalten an eine bestimmte Aufgabe oder Domäne anzupassen.

**Few-Shot** — Prompt-Technik, bei der dem Modell einige Eingabe-Ausgabe-Beispiele im Kontext bereitgestellt werden, um seine Antwort zu lenken. Es handelt sich um eine In-Context-Learning-Technik.

---

## G

**gemeinsames Verantwortungsmodell von AWS (AWS shared responsibility model)** — Rahmenwerk, das festlegt, welche Sicherheitsverantwortlichkeiten bei AWS liegen (Sicherheit der Cloud) und welche beim Kunden (Sicherheit in der Cloud).

**Generative KI (GenAI, generative AI)** — Kategorie von KI-Systemen, die in der Lage sind, neue Inhalte wie Text, Bilder, Audio oder Code auf der Grundlage von Eingaben in natürlicher Sprache zu erzeugen.

**Genauigkeit (accuracy)** — Anteil der richtigen Vorhersagen an der Gesamtzahl der getroffenen Vorhersagen; eine grundlegende Leistungsmetrik bei der Klassifizierung.

**Gewicht (weight)** — Synonymer Begriff für Parameter im Kontext neuronaler Netze; erlernter numerischer Wert, der den Einfluss jeder Verbindung zwischen Neuronen gewichtet.

**Governance** — Gesamtheit der Richtlinien, Prozesse, Verantwortlichkeiten und Kontrollen, die festlegen, wie KI-Systeme innerhalb einer Organisation entwickelt, eingesetzt und betrieben werden.

**GPU** — Graphics Processing Unit; Hardwarekomponente, die zur Beschleunigung des Trainings und der Inferenz von Deep-Learning-Modellen eingesetzt wird.

**Gradient Boosting** — Ensemble-Technik des Maschinellen Lernens, die Vorhersagemodelle iterativ aufbaut und dabei eine Verlustfunktion durch Gradientenabstieg optimiert.

**Großes Sprachmodell (LLM, large language model)** — Basismodell, das auf großen Textkorpora trainiert wurde und über allgemeine Fähigkeiten zum Sprachverständnis und zur Textgenerierung verfügt. Beispiele: Anthropic Claude, Meta Llama, Amazon Nova.

---

## H

**Halluzination (hallucination)** — Antwort eines Sprachmodells, die falsche oder erfundene Informationen enthält, die mit scheinbarer Überzeugung präsentiert werden. Ein zentrales Risiko generativer Modelle, das durch Grundlagentechniken (RAG, Guardrails, Ausgabenvalidierung) gemindert wird.

**Halbüberwachtes Lernen (semi-supervised learning)** — Trainingsansatz, der eine kleine Menge beschrifteter Daten mit einer großen Menge unbeschrifteter Daten kombiniert.

**Hyperparameter** — Konfigurationswert des Trainingsprozesses, der nicht aus den Daten gelernt wird, wie Lernrate, Stapelgröße oder Anzahl der Epochen.

---

## I

**IAM (Identitäts- und Zugriffsverwaltung, Identity and Access Management)** — AWS-Framework zur Verwaltung, wer auf welche AWS-Ressourcen zugreifen kann, durch identitäts- und ressourcenbasierte Berechtigungsrichtlinien.

**Inferenz (inferencing)** — Prozess der Verwendung eines trainierten ML-Modells zur Erzeugung von Vorhersagen oder Antworten auf der Grundlage neuer Eingaben.

**Inferenzendpunkt (endpoint)** — Bereitgestellte Ressource, die eine Schnittstelle zum Empfang von Inferenzanfragen und zur Rückgabe von Modellvorhersagen bereitstellt.

**Infrastruktur (infrastructure)** — Gesamtheit der Hardware-, Netzwerk- und Softwareressourcen, die die Bereitstellung und den Betrieb von KI-Systemen unterstützen.

**Inklusion (inclusivity)** — Eigenschaft eines KI-Systems und seiner Trainingsdaten, die eine gerechte Repräsentation verschiedener Personengruppen sicherstellt, um Ausgrenzungsverzerrungen zu vermeiden.

**ISO/IEC 42001** — Internationale Norm der Internationalen Organisation für Normung für KI-Managementsysteme, die Anforderungen zum Aufbau, zur Implementierung, Pflege und kontinuierlichen Verbesserung eines KI-Governance-Programms definiert.

---

## J

**Jailbreak** — Adversarielle Technik, die versucht, ein Sprachmodell dazu zu bringen, seine Sicherheitsbeschränkungen durch ausgeklügelte Prompts zu umgehen, um Guardrails oder Systemaufforderungen zu überlisten.

---

## K

**Kaltstart (cold start)** — Verzögerung, die auftritt, wenn eine zuvor inaktive Computing-Ressource erstmals aktiviert wird, etwa eine Lambda-Funktion oder ein serverloser Inferenzendpunkt.

**KI-Assistent (AI assistant)** — Konversationelle KI-Anwendung, die Benutzern bei Aufgaben mithilfe natürlicher Sprache hilft.

**Kiro** — AWS-integrierte Entwicklungsumgebung mit Generativer KI-Unterstützung für Entwickler.

**Klassifizierung (classification)** — Aufgabe des Überwachten Lernens, bei der das Modell lernt, Eingaben einer oder mehreren vordefinierten Kategorien zuzuordnen.

**Kontextfenster (context window)** — Maximale Anzahl von Token, die ein Modell in einem einzelnen Inferenzaufruf verarbeiten kann, einschließlich des Eingabe-Prompts und der generierten Antwort.

**Kontextgestaltung (context engineering)** — Disziplin des Entwerfens, Strukturierens und Verwaltens der Informationen, die in den Eingabekontext eines Großen Sprachmodells gestellt werden, um die Qualität der Antworten zu optimieren, einschließlich der Auswahl und Reihenfolge abgerufener Dokumente, Systemaufforderungen und In-Context-Beispiele.

**Kontinuierliches Vortraining (continuous pre-training)** — Technik, bei der der Vortraining-Prozess eines vorhandenen Basismodells mit zusätzlichen domänenspezifischen Daten fortgesetzt wird, ohne seine Architektur zu ändern. Kostengünstiger als das Vortraining von Grund auf.

**Kosten pro Token (cost per token)** — Kostenmetrik, die angibt, wie viel für die Verarbeitung oder Generierung jedes Tokens in einem Basismodell-Inferenzdienst bezahlt wird.

**Künstliche Intelligenz (KI, artificial intelligence)** — Informatikbereich, der sich dem Aufbau von Systemen widmet, die Aufgaben ausführen können, die normalerweise menschliche Intelligenz erfordern, wie Sprachverständnis, Bilderkennung und Entscheidungsfindung.

---

## L

**Latenz (latency)** — Zeit, die zwischen dem Senden einer Anfrage und dem Empfang der ersten Antwort vergeht; eine kritische Metrik für interaktive Inferenzanwendungen.

---

## M

**Maschinelles Lernen (ML, machine learning)** — Bereich der Künstlichen Intelligenz, der Systemen ermöglicht, aus Daten zu lernen und ihre Leistung zu verbessern, ohne explizit für jede Aufgabe programmiert zu werden.

**Mensch-in-der-Schleife (human-in-the-loop)** — Systemdesign, bei dem Menschen Modellausgaben an bestimmten Punkten des Workflows überprüfen, genehmigen oder korrigieren, insbesondere bei Entscheidungen mit hohem Risiko.

**Modalität (modality)** — Datentyp, den ein Modell verarbeiten oder erzeugen kann, wie Text, Bild, Audio, Video oder Code.

**Modellabweichung (model drift)** — Leistungsverschlechterung eines Modells im Produktionsbetrieb, die durch Änderungen in der Verteilung der Eingabedaten (Daten-Drift) oder in der Beziehung zwischen Eingaben und Zielausgaben (Konzept-Drift) verursacht wird.

**Modellkarte (model card)** — Strukturiertes Dokument, das die Eigenschaften eines ML-Modells beschreibt, einschließlich seines Zwecks, seiner Trainingsdaten, Leistungsmetriken, bekannten Verzerrungen, Einschränkungen und beabsichtigten Nutzungsrichtlinien.

**Modellkomplexität (model complexity)** — Maß für die Ausdrucksfähigkeit eines Modells, das mit der Anzahl der Parameter und der Tiefe der Architektur zusammenhängt.

**Multi-Agenten-System (multi-agent system)** — Architektur, in der mehrere KI-Agenten zusammenarbeiten oder sich koordinieren, um komplexe Aufgaben zu bewältigen, die die Fähigkeiten eines einzelnen Agenten übersteigen.

**multimodal** — Beschreibt ein Modell, das mehr als eine Datenmodalität verarbeiten und erzeugen kann, wie Text und Bilder gemeinsam.

---

## N

**Neuronales Netz (neural network)** — Rechnerarchitektur, die vom menschlichen Gehirn inspiriert ist und aus Schichten miteinander verbundener Knoten (künstliche Neuronen) besteht, die durch die Anpassung von Gewichten während des Trainings Datenrepräsentationen erlernen.

**NIST AI RMF** — KI-Risikomanagement-Rahmenwerk des US-amerikanischen National Institute of Standards and Technology, das vier Funktionen zur Steuerung des KI-Risikos definiert: Steuern (Govern), Abbilden (Map), Messen (Measure) und Reagieren (Manage).

**Nucleus-Sampling (top-p)** — Decodierungsstrategie, die zufällig das nächste Token aus denjenigen auswählt, die zusammen eine Wahrscheinlichkeit von p des Gesamtwertes ausmachen, und so die Zufälligkeit der Ausgabe steuert.

---

## O

**OAuth 2.0** — Standardautorisierungsprotokoll, das Anwendungen erlaubt, im Namen eines Benutzers auf Ressourcen zuzugreifen, ohne Anmeldeinformationen weiterzugeben. Wird von Amazon Bedrock AgentCore Identity zur Verwaltung der Agent-Authentifizierung bei externen Werkzeugen verwendet.

**One-Shot** — Variante der Prompt-Technik, bei der genau ein Eingabe-Ausgabe-Beispiel im Prompt-Kontext bereitgestellt wird.

---

## P

**Parameter** — Numerischer Wert, den das Modell während des Trainings erlernt und der sein Verhalten bestimmt. Moderne LLMs haben Milliarden von Parametern.

**parametereffiziente Feinabstimmung (parameter-efficient fine-tuning, PEFT)** — Familie von Feinabstimmungstechniken, die nur eine kleine Teilmenge der Modellparameter ändern, um den Rechenaufwand und das Risiko der Überanpassung zu reduzieren. Die bekanntesten Varianten sind LoRA und QLoRA.

**personenbezogene Daten (PII, personally identifiable information)** — Alle Daten, die dazu verwendet werden können, eine natürliche Person direkt oder indirekt zu identifizieren, wie Name, Identifikationsnummer, E-Mail-Adresse oder biometrische Daten.

**pgvector** — Open-Source-Erweiterung für PostgreSQL, die native Unterstützung zum Speichern und Suchen von Einbettungsvektoren hinzufügt und mit Amazon RDS und Aurora verwendet werden kann.

**Pipeline** — Abfolge von Verarbeitungsschritten, bei der die Ausgabe jedes Schritts die Eingabe des nächsten ist. Im ML-Kontext beschreibt sie den vollständigen Daten-, Trainings- und Inferenzfluss.

**Prompt (Eingabeaufforderung)** — Texteingabe, die einem Großen Sprachmodell bereitgestellt wird, um eine generierte Antwort zu erhalten. In der Prosa wird "Eingabeaufforderung" bei der Ersterwähnung verwendet; danach und in Code-Kontexten steht "Prompt".

**Prompt-Engineering** — Disziplin des Entwerfens und Optimierens von Texteingaben an Große Sprachmodelle, um qualitativ hochwertigere, relevantere und sicherere Ausgaben zu erhalten.

**Prompt-Injektion (prompt injection)** — Art eines adversariellen Angriffs (OWASP LLM01), bei dem bösartige Eingaben im Benutzer-Prompt oder in abgerufenen Dokumenten versuchen, das Modellverhalten zu manipulieren, um Systemaufforderungen zu ignorieren oder Daten preiszugeben.

**Prompt-Zwischenspeicherung (prompt caching)** — Technik, die Verarbeitungsergebnisse wiederholter Prompts wiederverwendet, um Latenz und Token-Kosten in Inferenzdiensten zu reduzieren.

---

## R

**Rauschen (noise)** — Zufällige oder irrelevante Variation in den Daten, die das Erlernen bedeutsamer Muster durch das Modell erschweren kann.

**Regression** — Aufgabe des Überwachten Lernens, bei der das Modell einen kontinuierlichen numerischen Wert vorhersagt.

**Retrieval-Augmented Generation (RAG)** — Technik, die die Abfrage relevanter Informationen aus einer externen Wissensbasis mit der generativen Fähigkeit eines Sprachmodells kombiniert, um Halluzinationen zu reduzieren und Antworten auf überprüfbaren Daten zu verankern.

**Robustheit (robustness)** — Fähigkeit eines KI-Systems, seine Leistung und sein korrektes Verhalten bei unerwarteten, adversariellen oder verteilungsfremden Eingaben aufrechtzuerhalten.

**rollenbasiertes Prompting (role prompting)** — Prompt-Engineering-Technik, bei der dem Modell eine bestimmte Identität oder Rolle zugewiesen wird, um den Stil und den Fokus seiner Antworten zu lenken.

---

## S

**Segmentierung (chunking)** — Aufteilung langer Dokumente in kleinere Segmente, um deren Speicherung in Vektordatenbanken und die effiziente Abfrage in RAG-Systemen zu erleichtern.

**Selbst-Attention (self-attention)** — Variante des Aufmerksamkeitsmechanismus, bei der die Repräsentationen der Eingabe-Token innerhalb derselben Sequenz aufeinander bezogen werden, um weitreichende Abhängigkeiten zu erfassen.

**Selbstüberwachtes Lernen (self-supervised learning)** — Trainingstechnik, die automatisch Beschriftungen aus den Eingabedaten generiert, ohne menschliche Annotation zu erfordern. Das Vortraining Großer Sprachmodelle basiert auf dieser Technik.

**sensible Informationen (sensitive information)** — Daten, die aufgrund ihrer vertraulichen Natur besonderen Schutz erfordern, einschließlich, aber nicht beschränkt auf personenbezogene Daten, Finanzdaten, Gesundheitsdaten und Geschäftsgeheimnisse.

**Serverlose Inferenz (serverless inferencing)** — Inferenz-Bereitstellungsmodell, bei dem der Cloud-Anbieter die zugrunde liegende Infrastruktur automatisch verwaltet und auf null skaliert, wenn keine aktiven Anfragen vorliegen.

**Sicherheit / Unbedenklichkeit (safety)** — Im Bereich der Cybersicherheit: Schutz von Systemen vor unbefugtem Zugriff und Angriffen. Im Bereich der verantwortungsvollen KI: Eigenschaft, die sicherstellt, dass das System keine schädlichen oder gefährlichen Ausgaben für Benutzer erzeugt.

**Stability AI** — KI-Drittanbieterunternehmen, bekannt für das Diffusionsmodell Stable Diffusion, das in einigen AWS-Marketplace-Kontexten verfügbar ist.

**Stoppsequenz (stop sequence)** — Token oder Zeichenfolge, die dem Modell signalisiert, an diesem Punkt mit der Textgenerierung aufzuhören.

**Strands Agents** — Open-Source-Framework von AWS zum Aufbau von KI-Agenten mit Reasoning-Schleifen, Speicher und Werkzeugzugriff.

**strukturierte Daten (structured data)** — Daten, die in einem vordefinierten Schema aus Zeilen und Spalten organisiert sind, wie sie in relationalen Datenbanken oder CSV-Dateien gespeichert werden.

**Systemaufforderung (system prompt)** — Übergeordnete Anweisungen, die dem Modell vor dem Benutzer-Gespräch bereitgestellt werden, um Verhalten, Ton und Grenzen der Antwort festzulegen.

---

## T

**Temperatur (temperature)** — Inferenzparameter, der die Zufälligkeit der Textgenerierung steuert: Niedrige Werte erzeugen deterministischere Ausgaben; hohe Werte erzeugen vielfältigere und kreativere Ausgaben.

**Text-zu-Bild (text-to-image)** — Multimodale Generierungsaufgabe, bei der das Modell ein Bild aus einer Textbeschreibung erzeugt.

**TLS** — Transport Layer Security; kryptografisches Protokoll, das die Kommunikation während der Übertragung zwischen Clients und Servern schützt.

**Token** — Grundlegende Verarbeitungseinheit für Text in Großen Sprachmodellen. Kann ein Wort, ein Teil eines Worts oder ein Satzzeichen sein. Der Großteil der Preise für FM-Dienste wird nach der Anzahl der verarbeiteten Token berechnet.

**Tokenisierung (tokenization)** — Prozess der Aufteilung von Text in Token für die Verarbeitung durch ein Sprachmodell.

**top-k** — Inferenzparameter, der die Auswahl des nächsten Tokens auf die k wahrscheinlichsten Token begrenzt und so die Zufälligkeit der Ausgabe reduziert.

**top-p** — Siehe "Nucleus-Sampling (top-p)".

**Transformer** — Neuronale Netzarchitektur, die 2017 eingeführt wurde und Selbst-Attention-Mechanismen verwendet, um weitreichende Abhängigkeiten in Sequenzen zu erfassen. Sie bildet die Grundlage der meisten modernen Großen Sprachmodelle.

**Transparenz (transparency)** — Eigenschaft eines KI-Systems, die es Benutzern, Betreibern und Regulierungsbehörden ermöglicht zu verstehen, wie das System funktioniert, welche Daten es verwendet, welche Einschränkungen es hat und wie es seine Entscheidungen trifft.

---

## U

**Überanpassung (overfitting)** — Phänomen, bei dem ein Modell die Details und das Rauschen der Trainingsdaten so präzise erlernt, dass es die Fähigkeit zur Verallgemeinerung auf neue Daten verliert.

**Überwachtes Lernen (supervised learning)** — Trainingsparadigma, bei dem das Modell aus Paaren von Eingaben und bekannten Ausgabe-Beschriftungen lernt.

**unbeschriftete Daten (unlabeled data)** — Trainingsdaten, die nur Eingaben ohne zugehörige Ausgabe-Beschriftungen enthalten, verwendet beim Unüberwachten oder Selbstüberwachten Lernen.

**Unteranpassung (underfitting)** — Phänomen, bei dem ein Modell zu einfach ist, um die zugrunde liegende Struktur der Daten zu erfassen, und sowohl beim Training als auch bei der Bewertung eine schlechte Leistung zeigt.

**unstrukturierte Daten (unstructured data)** — Daten ohne ein starres vordefiniertes Schema, wie Freitext, Bilder, Audio oder Video.

---

## V

**Vektordatenbank (vector database)** — Speichersystem, das für die Speicherung und Suche hochdimensionaler Vektorrepräsentationen durch semantische Ähnlichkeitssuche optimiert ist.

**verantwortungsvolle KI (responsible AI)** — Ansatz für Entwicklung und Einsatz von KI-Systemen, der Fairness, Transparenz, Erklärbarkeit, Robustheit, Datenschutz, Sicherheit und Inklusion priorisiert.

**Verarbeitung natürlicher Sprache (VNS / NLP, natural language processing)** — Bereich der Künstlichen Intelligenz, der sich mit der Interaktion zwischen Computern und menschlicher Sprache befasst und Aufgaben wie Verstehen, Generieren, Übersetzen und Stimmungsanalyse umfasst.

**Verlässlichkeit (veracity)** — Eigenschaft eines verantwortungsvollen KI-Systems, die misst, inwieweit seine Ausgaben korrekt, evidenzbasiert und frei von Halluzinationen sind.

**Verschlüsselung im Ruhezustand (encryption at rest)** — Kryptografischer Schutz gespeicherter Daten, damit diese ohne den entsprechenden Verschlüsselungsschlüssel nicht lesbar sind.

**Verschlüsselung während der Übertragung (encryption in transit)** — Kryptografischer Schutz von Daten bei der Übertragung zwischen Systemen, typischerweise über TLS.

**Verzerrung (bias)** — Systematische Tendenz eines KI-Modells, ungenaue oder unfaire Vorhersagen zu erzeugen, die häufig aus Ungleichgewichten oder einer unzureichenden Repräsentation von Gruppen in den Trainingsdaten entsteht.

**VPC (Virtuelle Private Cloud, Virtual Private Cloud)** — Isoliertes, privates virtuelles Netzwerk innerhalb von AWS, das vollständige Kontrolle über die Netzwerkumgebung bietet, einschließlich IP-Adressbereichen, Subnetzen, Routing-Tabellen und Gateways.

**Vortraining (pre-training)** — Erste Phase des Trainings eines Basismodells, in der das Modell allgemeine Repräsentationen von Sprache, Bildern oder anderen Daten im großen Maßstab und ohne direkte menschliche Aufsicht erlernt.

---

## W

**Wissensbasis (knowledge base)** — Repository mit strukturierten oder unstrukturierten Informationen, das ein RAG-System als Abrufquelle verwendet, um die Antworten des Modells zu verankern.

---

## Z

**Zeitreihendaten (time-series data)** — Sequenzen von Datenwerten, die nach Zeit indiziert sind; häufig in Anwendungsfällen wie Bedarfsprognose, Anomalieerkennung und Systemüberwachung.

**Zero-Shot** — Prompt-Technik, bei der das Modell aufgefordert wird, eine Aufgabe auszuführen, ohne dass im Prompt-Kontext ein einziges Beispiel bereitgestellt wird, und dabei ausschließlich auf das während des Vortrainings erworbene Wissen zurückgreift.

**Zusammenfassung (summarization)** — Aufgabe der Generativen KI, bei der das Modell einen langen Text kondensiert und die wichtigsten Informationen in einer kürzeren Form wiedergibt.
