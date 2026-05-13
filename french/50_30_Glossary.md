# Glossaire

Ce glossaire réunit les termes techniques, les sigles et les noms de services qui apparaissent tout au long du livre. Les noms de services AWS et les identificateurs de code sont conservés en anglais, tels qu'ils apparaissent dans la console et la documentation officielle d'AWS. Pour chaque concept traduit, l'équivalent anglais est indiqué entre parenthèses pour faciliter la recherche dans la documentation originale.

---

## A

**AIF-C01** — Code officiel de l'examen AWS Certified AI Practitioner. Conservé en anglais dans tous les contextes.

**ajustement fin (fine-tuning)** — Processus consistant à poursuivre l'entraînement d'un modèle de fondation pré-entraîné avec un ensemble de données plus petit et spécialisé pour adapter son comportement à une tâche ou un domaine particulier.

**ajustement fin efficace en paramètres (parameter-efficient fine-tuning, PEFT)** — Famille de techniques d'ajustement fin qui modifient uniquement un petit sous-ensemble des paramètres du modèle, réduisant le coût informatique et le risque de surapprentissage. Les variantes les plus connues sont LoRA et QLoRA.

**algorithme (algorithm)** — Ensemble d'instructions ou de règles définies qu'un système suit pour résoudre un problème ou accomplir une tâche.

**Amazon Aurora** — Service de base de données relationnelle géré par AWS, compatible avec MySQL et PostgreSQL.

**Amazon Bedrock** — Service géré d'AWS qui fournit un accès par API aux modèles de fondation d'Amazon et de tiers, avec des outils de personnalisation, Guardrails, Agents et Knowledge Bases.

**Amazon Bedrock AgentCore** — Plateforme AWS pour déployer et gérer des agents IA en production, incluant l'identité, l'autorisation et la mémoire persistante.

**Amazon Bedrock Agents** — Fonctionnalité d'Amazon Bedrock permettant de construire des agents IA capables de planifier et d'exécuter des actions en plusieurs étapes à l'aide d'outils et de sources de données externes.

**Amazon Bedrock Guardrails** — Fonctionnalité d'Amazon Bedrock qui applique des filtres de contenu, des sujets refusés, des mots bloqués, la suppression des informations sensibles, la vérification de l'ancrage contextuel et la protection contre les injections d'invites aux entrées et sorties du modèle.

**Amazon Bedrock Knowledge Bases** — Fonctionnalité d'Amazon Bedrock qui connecte les modèles de fondation à des sources de données externes pour permettre la génération augmentée par récupération (RAG) sans avoir à gérer l'infrastructure de vecteurs.

**Amazon CloudWatch** — Service de surveillance et d'observabilité d'AWS qui collecte des métriques, des journaux et des événements depuis les ressources AWS et les applications.

**Amazon Comprehend** — Service de traitement du langage naturel d'AWS qui détecte les entités, les sentiments, les thèmes et les données confidentielles telles que les informations personnelles identifiables (IPI) dans le texte.

**Amazon EC2** — Service de calcul cloud d'AWS fournissant une capacité de serveur virtuel évolutive.

**Amazon ECS** — Service d'orchestration de conteneurs entièrement géré par AWS.

**Amazon Kendra** — Service de recherche d'entreprise intelligent d'AWS utilisant le traitement du langage naturel pour trouver des réponses précises dans les documents internes.

**Amazon Lex** — Service AWS permettant de créer des interfaces conversationnelles vocales et textuelles (chatbots et assistants virtuels) en utilisant le même moteur de reconnaissance vocale et de compréhension du langage naturel qu'Alexa.

**Amazon Macie** — Service de sécurité des données d'AWS qui utilise l'apprentissage automatique pour découvrir et protéger automatiquement les données sensibles stockées dans Amazon S3, y compris les IPI et les identifiants.

**Amazon Neptune Analytics** — Service de base de données de graphes analytiques d'AWS avec des capacités de recherche vectorielle intégrées.

**Amazon Nova** — Famille de modèles de fondation multimodaux d'Amazon disponibles dans Amazon Bedrock, avec les variantes Micro, Lite, Pro et Premier selon l'équilibre entre coût et capacité.

**Amazon OpenSearch Service** — Service de recherche et d'analyse d'AWS basé sur OpenSearch, compatible avec la recherche vectorielle pour les cas d'utilisation RAG.

**Amazon Q** — Assistant d'IA générative d'AWS pour les professionnels des affaires et les développeurs, avec intégration aux sources de données d'entreprise.

**Amazon Quick** — Service d'analyse métier d'AWS avec des capacités d'IA générative intégrées pour créer des visualisations et répondre à des questions sur les données.

**Amazon RDS** — Service de base de données relationnelle géré par AWS compatible avec plusieurs moteurs, y compris PostgreSQL avec prise en charge de pgvector.

**Amazon Rekognition** — Service de vision par ordinateur d'AWS pour l'analyse d'images et de vidéos, incluant la détection d'objets, de visages et la modération de contenu.

**Amazon S3** — Service de stockage d'objets d'AWS à haute durabilité, évolutivité et avec des fonctionnalités de contrôle d'accès granulaire.

**Amazon SageMaker AI** — Plateforme d'apprentissage automatique d'AWS couvrant le cycle de vie complet du modèle : préparation des données, entraînement, ajustement fin, évaluation, déploiement et surveillance.

**Amazon SageMaker Clarify** — Composant d'Amazon SageMaker AI qui détecte les biais dans les données et les modèles, et génère des explications de prédictions via les valeurs SHAP.

**Amazon SageMaker Ground Truth** — Service d'étiquetage de données d'AWS qui combine des annotateurs humains avec une automatisation assistée par apprentissage automatique.

**Amazon Textract** — Service AWS qui extrait du texte, des formulaires et des tableaux depuis des documents numérisés via l'apprentissage automatique.

**Amazon Titan** — Famille de modèles de fondation d'Amazon disponibles dans Amazon Bedrock, incluant Amazon Titan Embeddings pour la génération de représentations vectorielles.

**Amazon Transcribe** — Service de reconnaissance automatique de la parole d'AWS qui convertit l'audio en texte.

**Amazon Translate** — Service de traduction automatique neuronale d'AWS.

**API (Interface de Programmation d'Application, Application Programming Interface)** — Contrat logiciel qui définit comment deux systèmes communiquent ; dans le contexte de l'IA générative, le mécanisme principal pour invoquer les modèles de fondation depuis les applications.

**apprentissage auto-supervisé (self-supervised learning)** — Technique d'entraînement qui génère automatiquement des étiquettes à partir des données d'entrée, sans nécessiter d'annotation humaine. Le pré-entraînement des grands modèles de langage repose sur cette technique.

**apprentissage automatique (ML, machine learning)** — Domaine de l'intelligence artificielle qui permet aux systèmes d'apprendre à partir de données et d'améliorer leurs performances sans être explicitement programmés pour chaque tâche.

**apprentissage par renforcement (reinforcement learning)** — Paradigme d'apprentissage automatique dans lequel un agent apprend en recevant des récompenses ou des pénalités selon ses actions dans un environnement.

**apprentissage profond (deep learning)** — Sous-domaine de l'apprentissage automatique qui utilise des réseaux de neurones à nombreuses couches pour apprendre des représentations hiérarchiques de données.

**apprentissage semi-supervisé (semi-supervised learning)** — Approche d'entraînement qui combine un petit ensemble de données étiquetées avec un grand ensemble de données non étiquetées.

**apprentissage supervisé (supervised learning)** — Paradigme d'entraînement dans lequel le modèle apprend à partir de paires d'entrées et d'étiquettes de sortie connues.

**assistant IA (AI assistant)** — Application d'IA conversationnelle conçue pour aider les utilisateurs dans leurs tâches via le langage naturel.

**attention, mécanisme d' (attention mechanism)** — Composant de l'architecture Transformer qui permet au modèle de pondérer la pertinence de différentes parties de l'entrée lors de la génération de chaque partie de la sortie.

**auto-attention (self-attention)** — Variante du mécanisme d'attention dans laquelle les représentations des jetons d'entrée se mettent en relation les unes avec les autres au sein de la même séquence, capturant les dépendances à longue distance.

**AWS** — Amazon Web Services, plateforme de services cloud d'Amazon.

**AWS Audit Manager** — Service AWS qui automatise la collecte de preuves de conformité réglementaire et organise ces preuves en rapports prêts pour l'audit alignés sur des cadres tels que HIPAA, SOC 2, PCI DSS et ISO 27001.

**AWS Artifact** — Portail en libre-service d'AWS où les clients peuvent télécharger les certifications de conformité tierces d'AWS, y compris les rapports SOC, les certifications ISO et les accords de partenariat commercial HIPAA.

**AWS Backup** — Service centralisé d'AWS pour planifier, surveiller et appliquer des politiques de sauvegarde et de conservation avec des points de récupération immuables.

**AWS Certified AI Practitioner** — Certification de niveau fondamental d'AWS qui valide la connaissance des concepts d'IA et d'apprentissage automatique, de l'IA générative et des services AWS pertinents.

**AWS CloudTrail** — Service AWS qui enregistre de façon immuable chaque appel API aux services AWS, créant une piste d'audit qui prouve qui a fait quoi et quand.

**AWS Config** — Service AWS qui enregistre continuellement l'état de configuration des ressources et évalue leur conformité par rapport à des règles définies par politique.

**AWS IAM Identity Center** — Service AWS pour gérer l'accès centralisé des utilisateurs à plusieurs comptes et applications AWS avec authentification unique.

**AWS Key Management Service (KMS)** — Service géré d'AWS pour créer et contrôler les clés de chiffrement qui protègent les données au repos et en transit.

**AWS Lambda** — Service de calcul sans serveur d'AWS qui exécute du code en réponse à des événements sans nécessiter de provisionner ni de gérer des serveurs.

**AWS Marketplace** — Catalogue numérique d'AWS où les clients peuvent trouver, tester et acheter des logiciels et services tiers, y compris des modèles de fondation.

**AWS PrivateLink** — Technologie réseau d'AWS permettant l'accès privé aux services AWS et tiers depuis un VPC sans exposer le trafic à l'internet public.

**AWS Secrets Manager** — Service AWS pour stocker, faire pivoter et récupérer des identifiants, des clés d'API et d'autres secrets de façon sécurisée.

**AWS Security Hub** — Service AWS qui agrège les résultats de sécurité de Config, Inspector, Macie et d'autres services dans un tableau de bord de conformité centralisé.

**AWS Trusted Advisor** — Outil AWS qui évalue les configurations de compte par rapport aux meilleures pratiques dans les catégories de sécurité, coût, performance, tolérance aux pannes et limites de service.

**AWS Well-Architected Framework** — Cadre de référence AWS qui décrit les meilleures pratiques architecturales pour construire des systèmes cloud autour des piliers d'excellence opérationnelle, de sécurité, de fiabilité, d'efficacité des performances, d'optimisation des coûts et de durabilité.

---

## B

**base de connaissances (knowledge base)** — Référentiel d'informations structurées ou non structurées qu'un système RAG utilise comme source de récupération pour ancrer les réponses du modèle.

**base de données vectorielle (vector database)** — Système de stockage optimisé pour stocker et rechercher des représentations vectorielles à haute dimension via une recherche par similarité sémantique.

**biais (bias)** — Distorsion systématique dans les prédictions d'un modèle qui crée des résultats injustes ou inexacts pour certains groupes ou conditions. Peut provenir des données d'entraînement, de l'architecture du modèle ou du processus d'étiquetage.

**boosting par gradient (gradient boosting)** — Technique d'apprentissage automatique d'ensemble qui construit des modèles prédictifs de façon séquentielle, chaque modèle corrigeant les erreurs du précédent.

---

## C

**cadence d'examen (review cadence)** — Calendrier selon lequel les décisions de gouvernance concernant les systèmes IA sont révisées, ajustées ou reconfirmées ; typiquement structuré en révisions mensuelles de la dérive, trimestrielles des modèles et pré-déploiement.

**cas d'usage (use case)** — Application ou scénario spécifique dans lequel un système d'IA est utilisé pour résoudre un problème réel d'affaires ou d'utilisateur.

**chaîne de pensée (chain-of-thought)** — Technique d'ingénierie des invites qui demande au modèle de raisonner étape par étape avant de donner une réponse finale, améliorant l'exactitude pour les tâches de raisonnement complexe.

**chaîne de traçabilité (chain of custody)** — Enregistrement documenté et auditable de qui a accédé, modifié ou transféré des données ou des artefacts de modèle au fil du temps.

**chatbot** — Application logicielle qui simule une conversation avec des utilisateurs humains via du texte ou de la voix, souvent construite sur des modèles de traitement du langage naturel.

**chiffrement au repos (encryption at rest)** — Protection cryptographique des données stockées pour les rendre illisibles sans la clé de chiffrement correspondante.

**chiffrement en transit (encryption in transit)** — Protection cryptographique des données lors de leur transmission entre systèmes, typiquement via TLS.

**classification (classification)** — Tâche d'apprentissage automatique supervisé dans laquelle le modèle apprend à attribuer des entrées à une ou plusieurs catégories prédéfinies.

**complexité du modèle (model complexity)** — Mesure de la capacité d'un modèle à représenter des relations dans les données, généralement liée au nombre de paramètres ; des modèles trop complexes sont sujets au surapprentissage.

---

## D

**données de séries temporelles (time-series data)** — Séquences de valeurs enregistrées à intervalles réguliers dans le temps ; utilisées dans les prédictions et la détection d'anomalies.

**données étiquetées (labeled data)** — Données d'entraînement associées à des annotations de sortie correctes fournies par des humains ou un processus automatisé.

**données non étiquetées (unlabeled data)** — Données d'entraînement sans annotations de sortie ; utilisées dans l'apprentissage non supervisé et auto-supervisé.

**données non structurées (unstructured data)** — Données qui ne suivent pas un format prédéfini, comme du texte libre, des images, de l'audio ou des vidéos ; représentent la majorité des données traitées par les systèmes d'IA générative.

**données structurées (structured data)** — Données organisées dans un format prédéfini, comme des tableaux de base de données, des fichiers CSV ou des schémas JSON.

**démarrage à froid (cold start)** — Délai de latence lors de la première invocation d'une fonction sans serveur ou d'un point de terminaison qui doit être initialisé depuis un état inactif.

**dérive du modèle (model drift)** — Dégradation de la performance d'un modèle en production due à des changements dans les données d'entrée ou les conditions du monde réel qui s'écartent de la distribution d'entraînement.

**distillation (distillation)** — Technique de compression de modèle dans laquelle un modèle étudiant plus petit apprend à reproduire le comportement d'un modèle enseignant plus grand, réduisant les exigences informatiques tout en préservant une grande partie de la performance.

---

## E

**embedding — voir représentation vectorielle**

**entraînement (training)** — Processus d'optimisation itérative des paramètres d'un modèle en minimisant une fonction de perte sur un ensemble de données d'entraînement.

**époque (epoch)** — Un passage complet à travers l'ensemble du jeu de données d'entraînement lors d'un processus d'entraînement.

**équité (fairness)** — Propriété d'un système IA qui garantit que ses décisions et sorties ne désavantagent pas systématiquement certains groupes démographiques ou catégories d'utilisateurs.

**évaluation (evaluation)** — Processus de mesure systématique de la qualité et des performances d'un modèle IA en utilisant des métriques quantitatives, des évaluateurs humains ou des benchmarks établis.

**exactitude (accuracy)** — Métrique de performance mesurant la proportion de prédictions correctes d'un modèle sur l'ensemble du jeu de données de test.

**explicabilité (explainability)** — Capacité à décrire, en termes compréhensibles pour les humains, comment un modèle d'IA est arrivé à une prédiction ou une sortie particulière.

---

## F

**fenêtre de contexte (context window)** — Nombre maximal de jetons qu'un modèle de langage peut traiter en une seule invocation, couvrant à la fois l'entrée et la sortie.

**fiche de modèle (model card)** — Document standardisé qui décrit les capacités d'un modèle, ses limitations, les données d'entraînement, les évaluations de performance, les risques connus et le périmètre d'utilisation prévu.

**filtrage de sortie (output filtering)** — Couche de contrôle appliquée après la génération du modèle pour détecter et supprimer le contenu nuisible, incorrect ou hors politique avant de le présenter à l'utilisateur.

---

## G

**garde-fou / Guardrails (guardrail)** — Mécanisme de contrôle appliqué aux entrées et sorties d'un modèle IA pour prévenir le contenu nuisible, la désinformation ou d'autres réponses hors politique. Dans le contexte AWS, désigne Amazon Bedrock Guardrails.

**génération augmentée par récupération (RAG, retrieval-augmented generation)** — Architecture qui connecte un modèle de fondation à une base de connaissances externe, récupérant des documents pertinents au moment de l'inférence pour ancrer les réponses dans des faits vérifiables.

**génération d'images (image generation)** — Tâche d'IA générative dans laquelle un modèle produit de nouvelles images à partir de descriptions textuelles ou d'images de référence.

**gouvernance (governance)** — Ensemble de politiques, processus et contrôles qui encadrent la façon dont les systèmes IA sont développés, déployés, surveillés et améliorés en continu.

**gouvernance des données (data governance)** — Discipline de gestion du cycle de vie complet des données, de la collecte à la suppression, avec des contrôles définis à chaque étape pour garantir la qualité, la confidentialité et la conformité.

**GPU** — Unité de traitement graphique (Graphics Processing Unit) ; processeur spécialisé dans le calcul parallèle massif, essentiel pour l'entraînement et l'inférence des modèles d'apprentissage profond.

**grand modèle de langage (LLM, large language model)** — Modèle de fondation entraîné sur de très grands corpus de texte pour comprendre et générer du langage naturel ; la catégorie inclut des modèles comme Anthropic Claude, Meta Llama et Amazon Nova.

---

## H

**hallucination (hallucination)** — Réponse générée par un modèle de langage qui contient des informations fausses ou inventées présentées avec une apparente confiance. Risque central des modèles génératifs atténué par des techniques d'ancrage (RAG, Guardrails, validation des sorties).

**humain dans la boucle (human-in-the-loop)** — Approche de conception de système IA qui maintient un superviseur humain dans le flux de décision pour les cas à risque élevé, ambigus ou dépassant les seuils de confiance.

**hyperparamètre (hyperparameter)** — Paramètre de configuration défini avant l'entraînement qui contrôle le processus d'apprentissage lui-même, comme le taux d'apprentissage, la taille du lot ou le nombre d'époques.

---

## I

**IAM (Gestion des identités et des accès, Identity and Access Management)** — Service AWS qui contrôle qui est authentifié et autorisé à utiliser les ressources AWS via des politiques, des rôles et des groupes.

**IA agentique (agentic AI)** — Paradigme d'IA dans lequel un système d'IA poursuit des objectifs à plusieurs étapes de façon autonome en utilisant des outils, en accédant à des données externes et en prenant des décisions sans intervention humaine à chaque étape.

**IA générative (GenAI, generative AI)** — Catégorie de systèmes IA capables de produire de nouveaux contenus (texte, images, code, audio) en apprenant les distributions statistiques des données d'entraînement.

**IA responsable (responsible AI)** — Ensemble de pratiques et de propriétés garantissant que les systèmes d'IA se comportent de façon équitable, transparente, robuste, sûre et véridique tout au long de leur cycle de vie.

**inclusivité (inclusivity)** — Propriété d'un système IA garantissant que ses données d'entraînement et ses sorties représentent équitablement des groupes démographiques divers et n'excluent pas systématiquement certaines populations.

**inférence (inferencing)** — Processus d'utilisation d'un modèle entraîné pour générer des prédictions ou des sorties à partir de nouvelles données d'entrée.

**inférence asynchrone (asynchronous inferencing)** — Mode d'inférence dans lequel la demande est soumise et la réponse est récupérée ultérieurement, adapté aux charges de travail à long temps de traitement ou aux grands lots.

**inférence en temps réel (real-time inferencing)** — Mode d'inférence avec une latence faible conçu pour les applications interactives qui nécessitent des réponses immédiates.

**inférence par lots (batch inferencing)** — Mode d'inférence qui traite de grands volumes de demandes en une seule opération planifiée, optimisant le débit et le coût.

**inférence sans serveur (serverless inferencing)** — Mode d'inférence dans lequel l'infrastructure s'adapte automatiquement et est facturée selon l'utilisation, sans provisionner d'instances dédiées.

**ingénierie de contexte (context engineering)** — Pratique de conception et de structuration du contenu de la fenêtre de contexte d'un modèle, incluant les invites, les documents récupérés et l'historique des conversations, pour guider le comportement du modèle.

**ingénierie des caractéristiques (feature engineering)** — Processus de sélection, de transformation et de création de variables d'entrée à partir de données brutes pour améliorer la performance d'un modèle d'apprentissage automatique.

**ingénierie des invites (prompt engineering)** — Pratique de conception d'invites efficaces pour guider le comportement d'un modèle de fondation vers les sorties souhaitées.

**injection d'invites (prompt injection)** — Attaque de sécurité dans laquelle des entrées malveillantes tentent de remplacer ou de contourner l'invite système d'un modèle de fondation pour le faire agir en dehors de son périmètre prévu.

**innocuité (safety)** — Dans le contexte de l'IA responsable, propriété qui garantit qu'un système IA ne cause pas de préjudice, ne génère pas de contenu nuisible et fonctionne dans des limites définies.

**intelligence artificielle (IA, artificial intelligence)** — Domaine de l'informatique axé sur la création de systèmes capables d'accomplir des tâches qui requièrent normalement une intelligence humaine.

**Internet des objets (IoT, Internet of Things)** — Réseau d'appareils physiques connectés à internet qui collectent et échangent des données ; les services AWS IoT incluent AWS IoT Core et AWS IoT Greengrass.

**invite (prompt)** — Texte d'entrée fourni à un modèle de fondation pour guider sa génération de réponse ; comprend l'invite système, le contexte et la requête de l'utilisateur.

**invite par rôle (role prompting)** — Technique d'ingénierie des invites dans laquelle on demande au modèle d'adopter une persona ou un rôle spécifique pour influencer le style et le contenu de ses réponses.

**invite système (system prompt)** — Instruction initiale fournie à un modèle de fondation qui définit son rôle, ses restrictions et son comportement avant que l'utilisateur n'interagisse avec lui.

**ISO/IEC 42001** — Norme internationale pour les systèmes de management de l'intelligence artificielle qui définit les exigences pour l'établissement, la mise en œuvre et l'amélioration continue d'un programme de gouvernance IA.

---

## J

**jailbreak** — Tentative d'exploitation des vulnérabilités d'un modèle de fondation pour l'amener à ignorer ses garde-fous et à produire des sorties interdites.

**jeu de données (dataset)** — Collection de données structurées ou non structurées utilisée pour entraîner, valider ou tester un modèle d'apprentissage automatique.

**jeton (token)** — Unité de base de traitement du texte pour un modèle de langage ; peut correspondre à un mot, un sous-mot ou un caractère selon le schéma de tokenisation utilisé.

---

## K

**Kiro** — Outil de développement AWS intégrant des capacités d'IA pour assister les développeurs dans la rédaction de spécifications et la génération de code.

---

## L

**lac de données (data lake)** — Référentiel de stockage centralisé qui contient de grandes quantités de données brutes dans leur format natif jusqu'à leur utilisation.

**latence (latency)** — Temps entre la soumission d'une demande d'inférence et la réception d'une réponse complète ; métrique clé pour les applications interactives.

---

## M

**mise en cache des invites (prompt caching)** — Technique qui réutilise les résultats de traitement d'invites répétées pour réduire la latence et le coût par jeton dans les services d'inférence.

**modalité (modality)** — Type de données qu'un modèle peut traiter ou produire, comme le texte, les images, l'audio, la vidéo ou le code. Un modèle multimodal gère plusieurs modalités.

**modèle de diffusion (diffusion model)** — Architecture de modèle génératif qui apprend à générer des données en inversant un processus d'ajout progressif de bruit ; largement utilisé pour la génération d'images.

**modèle de fondation (FM, foundation model)** — Grand modèle d'apprentissage automatique pré-entraîné sur de grandes quantités de données pour accomplir un large éventail de tâches ; constitue la base sur laquelle les applications d'IA générative sont construites.

**modèle personnalisé (custom model)** — Modèle de fondation adapté par ajustement fin ou apprentissage continu pour répondre aux besoins d'un domaine ou d'une tâche spécifique d'une organisation.

**moteur de recommandations (recommendation engine)** — Système qui analyse les patterns de comportement des utilisateurs et les propriétés des éléments pour suggérer du contenu, des produits ou des actions pertinents.

**multimodal (multimodal)** — Se dit d'un modèle ou d'un système capable de traiter et de produire plusieurs types de données (texte, images, audio, vidéo) dans une seule architecture unifiée.

---

## N

**NIST AI RMF** — Cadre de gestion des risques IA du National Institute of Standards and Technology (NIST), définissant quatre fonctions : Gouverner, Cartographier, Mesurer et Répondre pour gérer les risques IA.

**réseau de neurones (neural network)** — Modèle d'apprentissage automatique composé de couches de noeuds interconnectés qui transforment les entrées en sorties via des fonctions d'activation pondérées.

---

## O

**OAuth 2.0** — Protocole d'autorisation standard ouvert permettant aux applications d'accéder aux ressources d'un utilisateur sans exposer ses identifiants ; utilisé dans Amazon Bedrock AgentCore Identity.

---

## P

**paramètre (parameter)** — Variable interne d'un modèle apprise pendant l'entraînement qui encode les patterns et les connaissances des données d'entraînement ; les grands modèles peuvent avoir des milliards de paramètres.

**pipeline** — Séquence d'étapes de traitement où la sortie de chaque étape est l'entrée de la suivante ; dans le contexte de l'apprentissage automatique, décrit le flux complet de données, d'entraînement et d'inférence.

**politique (policy)** — Document de gouvernance qui établit l'utilisation acceptable, définit les responsabilités et fixe les limites pour le développement et l'exploitation des systèmes IA.

**poids (weight)** — Dans les réseaux de neurones, paramètre appris qui détermine la force de la connexion entre les noeuds ; mis à jour pendant l'entraînement pour minimiser la fonction de perte.

**point de terminaison (endpoint)** — Interface réseau exposant un modèle IA déployé pour recevoir des demandes d'inférence ; dans Amazon SageMaker et Amazon Bedrock, chaque modèle déployé est accessible via un point de terminaison.

**préentraînement (pre-training)** — Phase initiale d'entraînement d'un modèle de fondation sur de très grands corpus de données pour acquérir des connaissances générales avant une spécialisation ultérieure.

**préentraînement continu (continuous pre-training)** — Processus consistant à poursuivre le préentraînement d'un modèle de fondation existant avec de nouvelles données de domaine pour lui faire acquérir des connaissances spécialisées sans repartir de zéro.

**professionnel des affaires (business professional)** — Personne travaillant dans un rôle commercial ou de gestion qui utilise les systèmes IA pour prendre des décisions ou piloter des processus métier sans nécessairement avoir une formation technique en apprentissage automatique.

---

## R

**RAG — voir génération augmentée par récupération**

**référence comparative (benchmark)** — Ensemble de tests ou de métriques standardisé utilisé pour comparer les performances des modèles IA dans un contexte reproductible et objectif.

**référence de base (baseline)** — Mesure ou configuration de référence établie avant un changement, utilisée pour évaluer l'amélioration ou la dégression dans les évaluations de modèle et la surveillance de dérive.

**régression (regression)** — Tâche d'apprentissage automatique supervisé dans laquelle le modèle prédit une valeur numérique continue plutôt qu'une catégorie discrète.

**représentation vectorielle (embedding)** — Représentation numérique à haute dimension d'un élément de données (texte, image, audio) qui encode sa signification sémantique dans un espace vectoriel ; la base de la recherche par similarité dans les architectures RAG.

**résidence des données (data residency)** — Exigence que les données restent dans une limite géographique définie, généralement imposée par la loi ou la réglementation, comme le RGPD pour les données des résidents de l'UE.

**résumé (summarization)** — Tâche d'IA générative qui condense un document long en une version plus courte préservant les informations clés.

**rétention (retention)** — Politique définissant combien de temps les données doivent être conservées (minimum réglementaire) et quand elles doivent être supprimées (maximum de confidentialité).

**robustesse (robustness)** — Propriété d'un système IA qui maintient des performances et un comportement cohérents face à des entrées variées, des données adversariales ou des changements dans les conditions opérationnelles.

---

## S

**score de confiance (confidence score)** — Valeur numérique indiquant le niveau de certitude d'un modèle dans sa prédiction ou sa réponse ; utilisé pour router les cas à faible confiance vers un examen humain.

**segmentation (chunking)** — Processus de division de longs documents en morceaux plus petits et sémantiquement cohérents pour l'indexation dans une base de données vectorielle pour le RAG.

**séquence d'arrêt (stop sequence)** — Jeton ou chaîne de caractères qui, lorsqu'il est généré, indique au modèle de cesser de produire des jetons supplémentaires.

**sous-apprentissage (underfitting)** — Condition dans laquelle un modèle est trop simple pour capturer les patterns sous-jacents des données d'entraînement, entraînant de mauvaises performances sur les données d'entraînement et de test.

**Strands Agents** — Cadre open source AWS pour construire des agents IA avec des capacités d'intégration d'outils et de raisonnement multi-étapes.

**surapprentissage (overfitting)** — Condition dans laquelle un modèle apprend trop précisément les patterns de l'ensemble de données d'entraînement, y compris le bruit, et généralise mal aux nouvelles données.

**surveillance (monitoring)** — Pratique de suivi continu des performances, du comportement et de l'utilisation d'un système IA en production pour détecter les violations de politique, la dérive et les anomalies.

**système multi-agents (multi-agent system)** — Architecture dans laquelle plusieurs agents IA collaborent ou se spécialisent pour accomplir des tâches complexes décomposées entre plusieurs composants.

---

## T

**température (temperature)** — Paramètre d'inférence contrôlant le caractère aléatoire de la génération ; des valeurs basses produisent des sorties plus déterministes, des valeurs élevées favorisent la diversité et la créativité.

**texte vers image (text-to-image)** — Capacité d'IA générative qui produit des images à partir de descriptions textuelles.

**tokenisation (tokenization)** — Processus de décomposition du texte en jetons que le modèle peut traiter ; le schéma de tokenisation détermine comment les mots, sous-mots et caractères sont mappés aux identifiants numériques.

**traçabilité des données (data lineage)** — Documentation du parcours d'une donnée depuis sa source jusqu'à son utilisation, permettant une traçabilité complète lors d'audits ou d'enquêtes réglementaires.

**traitement du langage naturel (NLP, natural language processing)** — Sous-domaine de l'IA axé sur la capacité des ordinateurs à comprendre, interpréter et générer du langage humain.

**transformeur (transformer)** — Architecture de réseau de neurones introduite en 2017 qui utilise l'auto-attention pour traiter les séquences en parallèle ; constitue la base de la plupart des grands modèles de langage.

**transparence (transparency)** — Propriété d'un système IA qui permet aux parties prenantes de comprendre comment il fonctionne, quelles données il utilise et comment il arrive à ses sorties.

---

## V

**véracité (veracity)** — Propriété d'un système IA qui garantit que ses sorties sont exactes, fondées sur des faits vérifiables et non susceptibles de tromper les utilisateurs.

**vision par ordinateur (CV, computer vision)** — Sous-domaine de l'IA qui permet aux systèmes informatiques de comprendre et d'interpréter les données visuelles comme les images et les vidéos.

**VPC (Cloud Privé Virtuel, Virtual Private Cloud)** — Réseau virtuel isolé dans AWS qui permet aux clients de lancer des ressources dans un environnement réseau défini par eux-mêmes.

---

## Z

**zero-shot** — Capacité d'un modèle à effectuer une tâche sans aucun exemple dans l'invite, en s'appuyant uniquement sur les connaissances acquises lors du pré-entraînement.
