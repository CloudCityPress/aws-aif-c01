# Glosario

Este glosario reúne los términos técnicos, siglas y nombres de servicios que aparecen a lo largo del libro. Los nombres de servicios de AWS y los identificadores de código se mantienen en inglés, tal como aparecen en la consola y la documentación oficial de AWS. Para cada concepto traducido se indica el equivalente en inglés entre paréntesis a fin de facilitar la búsqueda en la documentación original.

---

## A

**AIF-C01** — Código oficial del examen AWS Certified AI Practitioner. Se mantiene en inglés en todos los contextos.

**ajuste fino (fine-tuning)** — Proceso de continuar el entrenamiento de un modelo fundacional preentrenado con un conjunto de datos más pequeño y especializado para adaptar su comportamiento a una tarea o dominio concreto.

**ajuste fino eficiente en parámetros (parameter-efficient fine-tuning, PEFT)** — Familia de técnicas de ajuste fino que modifican solo un subconjunto pequeño de los parámetros del modelo, reduciendo el costo computacional y el riesgo de sobreajuste. Las variantes más conocidas son LoRA y QLoRA.

**algoritmo (algorithm)** — Conjunto de instrucciones o reglas definidas que un sistema sigue para resolver un problema o llevar a cabo una tarea.

**almacenamiento en caché de indicaciones (prompt caching)** — Técnica que reutiliza los resultados de procesamiento de indicaciones repetidas para reducir la latencia y el costo por token en servicios de inferencia.

**alucinación (hallucination)** — Respuesta generada por un modelo de lenguaje que contiene información falsa o inventada presentada con aparente confianza. Un riesgo central de los modelos generativos que se mitiga con técnicas de fundamentación (RAG, Guardrails, validación de salidas).

**Amazon Aurora** — Servicio de base de datos relacional administrado de AWS compatible con MySQL y PostgreSQL.

**Amazon Bedrock** — Servicio administrado de AWS que proporciona acceso mediante API a modelos fundacionales de Amazon y de terceros, con herramientas para personalización, Guardrails, Agents y Knowledge Bases.

**Amazon Bedrock AgentCore** — Plataforma de AWS para desplegar y gestionar agentes de IA en producción, incluyendo identidad, autorización y memoria persistente.

**Amazon Bedrock Agents** — Característica de Amazon Bedrock que permite construir agentes de IA que pueden planificar y ejecutar acciones de varios pasos mediante herramientas y fuentes de datos externas.

**Amazon Bedrock Guardrails** — Característica de Amazon Bedrock que aplica filtros de contenido, temas denegados, palabras bloqueadas, supresión de información confidencial, verificación de fundamentación contextual y protección contra inyecciones de instrucciones a las entradas y salidas del modelo.

**Amazon Bedrock Knowledge Bases** — Característica de Amazon Bedrock que conecta modelos fundacionales con fuentes de datos externas para permitir la generación aumentada por recuperación (RAG) sin necesidad de administrar infraestructura de vectores.

**Amazon CloudWatch** — Servicio de monitoreo y observabilidad de AWS que recopila métricas, registros y eventos de los recursos de AWS y las aplicaciones.

**Amazon Comprehend** — Servicio de procesamiento del lenguaje natural de AWS que detecta entidades, sentimientos, temas y datos confidenciales como información de identificación personal (PII) en texto.

**Amazon EC2** — Servicio de cómputo en la nube de AWS que proporciona capacidad de servidor virtual escalable.

**Amazon ECS** — Servicio de orquestación de contenedores de AWS totalmente administrado.

**Amazon Kendra** — Servicio de búsqueda empresarial inteligente de AWS que utiliza procesamiento del lenguaje natural para encontrar respuestas precisas en documentos internos.

**Amazon Lex** — Servicio de AWS para crear interfaces conversacionales de voz y texto (chatbots y asistentes virtuales) usando el mismo motor de reconocimiento de voz y comprensión del lenguaje natural que Alexa.

**Amazon Macie** — Servicio de seguridad de datos de AWS que utiliza aprendizaje automático para descubrir y proteger automáticamente datos sensibles almacenados en Amazon S3, incluyendo PII y credenciales.

**Amazon Neptune Analytics** — Servicio de base de datos de grafos analíticos de AWS con capacidades de búsqueda vectorial integradas.

**Amazon Nova** — Familia de modelos fundacionales multimodales de Amazon disponibles en Amazon Bedrock, con variantes Micro, Lite, Pro y Premier según el equilibrio entre costo y capacidad.

**Amazon OpenSearch Service** — Servicio de búsqueda y análisis de AWS basado en OpenSearch, compatible con búsqueda vectorial para casos de uso de RAG.

**Amazon Q** — Asistente de IA generativa de AWS para profesionales de negocios y desarrolladores, con integración con fuentes de datos empresariales.

**Amazon Quick** — Servicio de análisis de negocio de AWS con capacidades de IA generativa integradas para crear visualizaciones y responder preguntas sobre datos.

**Amazon RDS** — Servicio de base de datos relacional administrado de AWS compatible con varios motores, incluyendo PostgreSQL con soporte para pgvector.

**Amazon Rekognition** — Servicio de visión computacional de AWS para análisis de imágenes y vídeo, incluyendo detección de objetos, caras y moderación de contenido.

**Amazon S3** — Servicio de almacenamiento de objetos de AWS con alta durabilidad, escalabilidad y funciones de control de acceso granular.

**Amazon SageMaker AI** — Plataforma de aprendizaje automático de AWS que cubre el ciclo de vida completo del modelo: preparación de datos, entrenamiento, ajuste fino, evaluación, despliegue y monitoreo.

**Amazon SageMaker Clarify** — Componente de Amazon SageMaker AI que detecta sesgo en datos y modelos, y genera explicaciones de predicciones mediante valores SHAP.

**Amazon SageMaker Ground Truth** — Servicio de etiquetado de datos de AWS que combina anotadores humanos con automatización asistida por aprendizaje automático.

**Amazon Textract** — Servicio de AWS que extrae texto, formularios y tablas de documentos escaneados mediante aprendizaje automático.

**Amazon Titan** — Familia de modelos fundacionales de Amazon disponibles en Amazon Bedrock, incluyendo Amazon Titan Embeddings para generación de representaciones vectoriales.

**Amazon Transcribe** — Servicio de reconocimiento automático de voz de AWS que convierte audio en texto.

**Amazon Translate** — Servicio de traducción automática neuronal de AWS.

**API (Interfaz de Programación de Aplicaciones, Application Programming Interface)** — Contrato de software que define cómo se comunican dos sistemas; en el contexto de IA generativa, el mecanismo principal para invocar modelos fundacionales desde aplicaciones.

**aprendizaje autosupervisado (self-supervised learning)** — Técnica de entrenamiento que genera automáticamente etiquetas a partir de los datos de entrada, sin requerir anotación humana. El preentrenamiento de modelos de lenguaje grande se basa en esta técnica.

**aprendizaje automático (ML, machine learning)** — Campo de la inteligencia artificial que permite a los sistemas aprender de datos y mejorar su rendimiento sin ser programados explícitamente para cada tarea.

**aprendizaje por refuerzo (reinforcement learning)** — Paradigma de aprendizaje automático en el que un agente aprende mediante la recepción de recompensas o penalizaciones según sus acciones en un entorno.

**aprendizaje profundo (deep learning)** — Subcampo del aprendizaje automático que utiliza redes neuronales con muchas capas para aprender representaciones jerárquicas de datos.

**aprendizaje semisupervisado (semi-supervised learning)** — Enfoque de entrenamiento que combina un pequeño conjunto de datos etiquetados con un conjunto grande de datos sin etiquetar.

**aprendizaje supervisado (supervised learning)** — Paradigma de entrenamiento en el que el modelo aprende a partir de pares de entradas y etiquetas de salida conocidas.

**asistente de IA (AI assistant)** — Aplicación de IA conversacional diseñada para ayudar a los usuarios con tareas mediante lenguaje natural.

**atención, mecanismo de (attention mechanism)** — Componente de la arquitectura Transformer que permite al modelo ponderar la relevancia de diferentes partes de la entrada al generar cada parte de la salida.

**auto-atención (self-attention)** — Variante del mecanismo de atención en la que las representaciones de los tokens de entrada se relacionan entre sí dentro de la misma secuencia, capturando dependencias a larga distancia.

**AWS** — Amazon Web Services, plataforma de servicios en la nube de Amazon.

**AWS Audit Manager** — Servicio de AWS que automatiza la recopilación de evidencia de cumplimiento normativo y organiza esa evidencia en informes listos para auditoría alineados a marcos como HIPAA, SOC 2, PCI DSS e ISO 27001.

**AWS Artifact** — Portal de autoservicio de AWS donde los clientes pueden descargar certificaciones de cumplimiento de terceros de AWS, incluyendo informes SOC, certificaciones ISO y Acuerdos de Socio Comercial HIPAA.

**AWS Backup** — Servicio centralizado de AWS para programar, supervisar y aplicar políticas de copia de seguridad y retención con puntos de recuperación inmutables.

**AWS Certified AI Practitioner** — Certificación de nivel fundacional de AWS que valida el conocimiento de conceptos de IA y aprendizaje automático, IA generativa y los servicios de AWS relevantes.

**AWS CloudTrail** — Servicio de AWS que registra de forma inmutable cada llamada a la API de los servicios de AWS, creando una pista de auditoría que demuestra quién hizo qué y cuándo.

**AWS Config** — Servicio de AWS que registra continuamente el estado de configuración de los recursos y evalúa su cumplimiento respecto a reglas definidas por política.

**AWS IAM Identity Center** — Servicio de AWS para gestionar el acceso centralizado de usuarios a múltiples cuentas y aplicaciones de AWS con inicio de sesión único.

**AWS Key Management Service (KMS)** — Servicio administrado de AWS para crear y controlar las claves de cifrado que protegen los datos en reposo y en tránsito.

**AWS Lambda** — Servicio de cómputo sin servidor de AWS que ejecuta código en respuesta a eventos sin necesidad de aprovisionar ni gestionar servidores.

**AWS Marketplace** — Catálogo digital de AWS donde los clientes pueden encontrar, probar y comprar software y servicios de terceros, incluyendo modelos fundacionales.

**AWS PrivateLink** — Tecnología de red de AWS que permite el acceso privado a servicios de AWS y de terceros desde una VPC sin exponer el tráfico a la internet pública.

**AWS Secrets Manager** — Servicio de AWS para almacenar, rotar y recuperar credenciales, claves de API y otros secretos de forma segura.

**AWS Security Hub** — Servicio de AWS que agrega hallazgos de seguridad de Config, Inspector, Macie y otros servicios en un panel centralizado de cumplimiento.

**AWS Trusted Advisor** — Herramienta de AWS que evalúa las configuraciones de cuenta respecto a las mejores prácticas en las categorías de seguridad, costo, rendimiento, tolerancia a fallos y límites de servicio.

**AWS Well-Architected Framework** — Marco de referencia de AWS que describe las mejores prácticas arquitectónicas para construir sistemas en la nube en torno a los pilares de excelencia operativa, seguridad, fiabilidad, eficiencia de rendimiento, optimización de costos y sostenibilidad.

---

## B

**barrera de seguridad / Guardrails (guardrail)** — Mecanismo de control aplicado a las entradas y salidas de un modelo de IA para prevenir contenido dañino, desinformación u otras respuestas fuera de política. En el contexto de AWS se refiere a Amazon Bedrock Guardrails.

**base de conocimiento (knowledge base)** — Repositorio de información estructurada o no estructurada que un sistema de RAG utiliza como fuente de recuperación para fundamentar las respuestas del modelo.

**base de datos vectorial (vector database)** — Sistema de almacenamiento optimizado para guardar y buscar representaciones vectoriales de alta dimensión mediante búsqueda por similitud semántica.

---

## C

**cadena de custodia** — Registro documentado y auditable de quién accedió, modificó o transfirió datos o artefactos del modelo a lo largo del tiempo.

**cadena de pensamiento (chain-of-thought)** — Técnica de ingeniería de indicaciones que solicita al modelo que razone paso a paso antes de dar una respuesta final, mejorando la exactitud en tareas de razonamiento complejo.

**canal de datos (data pipeline)** — Secuencia automatizada de pasos para mover, transformar y cargar datos desde fuentes hasta destinos de consumo.

**canal de procesamiento (pipeline)** — Secuencia de etapas de procesamiento donde la salida de cada etapa es la entrada de la siguiente. En el contexto de aprendizaje automático, describe el flujo completo de datos, entrenamiento e inferencia.

**caso de uso (use case)** — Aplicación o escenario específico en el que se utiliza un sistema de IA para resolver un problema real de negocio o usuario.

**chatbot** — Aplicación de software que simula una conversación con usuarios humanos mediante texto o voz, con frecuencia construida sobre modelos de procesamiento del lenguaje natural.

**cifrado en reposo (encryption at rest)** — Protección criptográfica de datos almacenados para que sean ilegibles sin la clave de cifrado correspondiente.

**cifrado en tránsito (encryption in transit)** — Protección criptográfica de datos mientras se transmiten entre sistemas, típicamente mediante TLS.

**clasificación (classification)** — Tarea de aprendizaje automático supervisado en la que el modelo aprende a asignar entradas a una o más categorías predefinidas.

**complejidad del modelo (model complexity)** — Medida de la capacidad expresiva de un modelo, relacionada con el número de parámetros y la profundidad de la arquitectura.

**conjunto de datos (dataset)** — Colección organizada de datos utilizada para entrenar, validar o evaluar modelos de aprendizaje automático.

**context engineering** — Disciplina de diseñar, estructurar y gestionar la información que se coloca en el contexto de entrada de un modelo de lenguaje grande para optimizar la calidad de sus respuestas, incluyendo la selección y el orden de documentos recuperados, las instrucciones del sistema y los ejemplos en contexto.

**costo por token (cost per token)** — Métrica de coste que expresa cuánto se paga por procesar o generar cada token en un servicio de inferencia de modelo fundacional.

---

## D

**datos de series temporales (time-series data)** — Secuencias de valores de datos indexados por tiempo; son comunes en casos de uso de predicción de demanda, detección de anomalías y monitoreo de sistemas.

**datos estructurados (structured data)** — Datos organizados en un esquema predefinido de filas y columnas, como los almacenados en bases de datos relacionales o archivos CSV.

**datos etiquetados (labeled data)** — Datos de entrenamiento que incluyen tanto la entrada como la salida o etiqueta correcta asociada, necesarios para el aprendizaje supervisado.

**datos no estructurados (unstructured data)** — Datos que no tienen un esquema rígido predefinido, como texto libre, imágenes, audio o vídeo.

**datos sin etiquetar (unlabeled data)** — Datos de entrenamiento que contienen solo entradas sin etiquetas de salida asociadas, utilizados en aprendizaje no supervisado o autosupervisado.

**deriva del modelo (model drift)** — Degradación del rendimiento de un modelo en producción causada por cambios en la distribución de los datos de entrada (deriva de datos) o en la relación entre entradas y salidas objetivo (deriva del concepto).

**destilación (distillation)** — Técnica para transferir el conocimiento de un modelo grande (modelo profesor) a un modelo más pequeño (modelo alumno), produciendo un modelo más eficiente con un rendimiento similar.

**dimensionalidad, reducción de (dimensionality reduction)** — Técnica que disminuye el número de características o dimensiones de los datos manteniendo la información más relevante.

---

## E

**época (epoch)** — Una pasada completa a través de todo el conjunto de datos de entrenamiento durante el proceso de entrenamiento de un modelo.

**equidad (fairness)** — Propiedad de un sistema de IA que garantiza que sus predicciones o recomendaciones no produzcan resultados discriminatorios injustos para grupos de personas basados en características protegidas como raza, género o edad.

**evaluación (evaluation)** — Proceso de medir el rendimiento de un modelo de IA según métricas definidas en un conjunto de datos de prueba o en producción.

**exactitud (accuracy)** — Proporción de predicciones correctas respecto al total de predicciones realizadas; métrica de rendimiento fundamental en clasificación.

**explicabilidad (explainability)** — Capacidad de un sistema de IA para describir o justificar sus predicciones en términos comprensibles para los seres humanos.

---

## F

**few-shot** — Técnica de indicación en la que se proporcionan al modelo unos pocos ejemplos de entrada-salida en el contexto para guiar su respuesta. Es una técnica de aprendizaje en contexto (in-context learning).

**fragmentación (chunking)** — División de documentos largos en segmentos más pequeños para facilitar su almacenamiento en bases de datos vectoriales y su recuperación eficiente en sistemas RAG.

---

## G

**generación aumentada por recuperación (RAG, retrieval-augmented generation)** — Técnica que combina la recuperación de información relevante de una base de conocimiento externa con la capacidad generativa de un modelo de lenguaje, reduciendo las alucinaciones y fundamentando las respuestas en datos verificables.

**gobernanza (governance)** — Conjunto de políticas, procesos, responsabilidades y controles que rigen cómo se desarrollan, despliegan y operan los sistemas de IA dentro de una organización.

**gobernanza de datos (data governance)** — Disciplina que gestiona la disponibilidad, usabilidad, integridad y seguridad de los datos utilizados en una organización, cubriendo el ciclo de vida completo desde la creación hasta la eliminación.

**GPU** — Unidad de procesamiento gráfico; componente de hardware utilizado para acelerar el entrenamiento e inferencia de modelos de aprendizaje profundo.

---

## H

**hiperparámetro (hyperparameter)** — Valor de configuración del proceso de entrenamiento que no se aprende de los datos, como la tasa de aprendizaje, el tamaño del lote o el número de épocas.

**humano en el circuito (human-in-the-loop)** — Diseño de sistema en el que los seres humanos revisan, aprueban o corrigen las salidas del modelo en puntos específicos del flujo de trabajo, especialmente para decisiones de alto riesgo.

---

## I

**IA agéntica (agentic AI)** — Sistemas de IA que pueden planificar y ejecutar secuencias de acciones de manera autónoma para alcanzar objetivos de múltiples pasos, utilizando herramientas y fuentes de datos externas.

**IA generativa (GenAI, generative AI)** — Categoría de sistemas de IA capaces de generar nuevos contenidos, como texto, imágenes, audio o código, a partir de indicaciones en lenguaje natural.

**IA responsable (responsible AI)** — Enfoque para el desarrollo y despliegue de sistemas de IA que prioriza la equidad, la transparencia, la explicabilidad, la robustez, la privacidad, la seguridad y la inclusividad.

**IAM (Gestión de Identidad y Acceso, Identity and Access Management)** — Marco de AWS para gestionar quién puede acceder a qué recursos de AWS, mediante políticas de permisos basadas en identidad y recursos.

**impulso de gradiente (gradient boosting)** — Técnica de conjunto de aprendizaje automático que construye modelos predictivos de forma iterativa, optimizando una función de pérdida mediante el descenso de gradiente.

**inclusividad (inclusivity)** — Propiedad de un sistema de IA y de sus datos de entrenamiento que garantiza la representación equitativa de grupos diversos de personas para evitar el sesgo de exclusión.

**indicación de sistema (system prompt)** — Instrucciones de alto nivel proporcionadas al modelo antes de la conversación del usuario para establecer el comportamiento, el tono y los límites de la respuesta.

**indicación por rol (role prompting)** — Técnica de ingeniería de indicaciones que asigna al modelo una identidad o función específica para orientar el estilo y el enfoque de sus respuestas.

**inferencia (inferencing)** — Proceso de utilizar un modelo de aprendizaje automático entrenado para generar predicciones o respuestas a partir de nuevas entradas.

**inferencia asíncrona (asynchronous inferencing)** — Modo de inferencia en el que la solicitud se envía y el resultado se recupera posteriormente, adecuado para entradas largas o procesamiento por lotes.

**inferencia en tiempo real (real-time inferencing)** — Modo de inferencia de baja latencia que devuelve resultados de forma inmediata o en flujo continuo, adecuado para aplicaciones interactivas.

**inferencia por lotes (batch inferencing)** — Procesamiento de un gran número de solicitudes de inferencia en conjunto, optimizando el uso de recursos a expensas de una mayor latencia.

**inferencia sin servidor (serverless inferencing)** — Modelo de despliegue de inferencia en el que el proveedor de nube gestiona automáticamente la infraestructura subyacente, escalando a cero cuando no hay solicitudes activas.

**información de identificación personal (PII, personally identifiable information)** — Cualquier dato que pueda usarse para identificar directa o indirectamente a una persona física, como nombre, número de identificación, dirección de correo electrónico o datos biométricos.

**información sensible (sensitive information)** — Datos que requieren protección especial por su naturaleza confidencial, que incluye pero no se limita a la PII, datos financieros, datos de salud y secretos comerciales.

**infraestructura (infrastructure)** — Conjunto de recursos de hardware, red y software que soportan el despliegue y la operación de sistemas de IA.

**ingeniería de características (feature engineering)** — Proceso de transformar datos brutos en representaciones numéricas más informativas para mejorar el rendimiento del modelo.

**ingeniería de contexto (context engineering)** — Véase "context engineering".

**ingeniería de indicaciones (prompt engineering)** — Disciplina de diseñar y optimizar las entradas textuales a los modelos de lenguaje grande para obtener salidas de mayor calidad, relevancia y seguridad.

**inicio en frío (cold start)** — Retardo que ocurre cuando se activa por primera vez un recurso de cómputo que ha estado inactivo, como una función Lambda o un punto de conexión sin servidor.

**inteligencia artificial (IA, artificial intelligence)** — Campo de la informática dedicado a construir sistemas capaces de realizar tareas que normalmente requieren inteligencia humana, como comprensión del lenguaje, reconocimiento de imágenes y toma de decisiones.

**inyección de indicaciones (prompt injection)** — Tipo de ataque adversario (OWASP LLM01) en el que entradas maliciosas en el prompt del usuario o en los documentos recuperados intentan manipular el comportamiento del modelo para ignorar las instrucciones del sistema o filtrar datos.

**ISO/IEC 42001** — Norma internacional de la Organización Internacional de Normalización para sistemas de gestión de inteligencia artificial, que define requisitos para establecer, implementar, mantener y mejorar continuamente un programa de gobernanza de IA.

---

## J

**jailbreak** — Técnica adversaria que intenta hacer que un modelo de lenguaje ignore sus restricciones de seguridad mediante indicaciones elaboradas para eludir los Guardrails o las instrucciones del sistema.

---

## K

**Kiro** — Entorno de desarrollo integrado de AWS con asistencia de IA generativa para desarrolladores.

---

## L

**lago de datos (data lake)** — Repositorio de almacenamiento centralizado que contiene datos estructurados y no estructurados en su formato original o transformado, a cualquier escala.

**latencia (latency)** — Tiempo transcurrido entre el envío de una solicitud y la recepción de la primera respuesta; métrica crítica para las aplicaciones de inferencia interactivas.

**linaje de datos (data lineage)** — Registro trazable del origen de los datos, las transformaciones que han sufrido y los sistemas que los han consumido, desde su creación hasta su uso en un modelo de IA.

**línea de base (baseline)** — Conjunto de métricas de referencia calculadas a partir de datos de entrenamiento o de un período de rendimiento aceptable, utilizada para detectar desviaciones en producción.

**LLM (modelo de lenguaje grande, large language model)** — Modelo fundacional entrenado en grandes corpus de texto que exhibe capacidades generales de comprensión y generación del lenguaje natural. Ejemplos: Anthropic Claude, Meta Llama, Amazon Nova.

---

## M

**mecanismo de atención** — Véase "atención, mecanismo de".

**modalidad (modality)** — Tipo de datos que puede procesar o generar un modelo, como texto, imagen, audio, vídeo o código.

**modelo de difusión (diffusion model)** — Arquitectura generativa que aprende a invertir un proceso progresivo de adición de ruido para generar imágenes u otros datos de alta calidad. Es la base de sistemas como Stable Diffusion.

**modelo de lenguaje grande (LLM)** — Véase "LLM".

**modelo de responsabilidad compartida de AWS (AWS shared responsibility model)** — Marco que define qué responsabilidades de seguridad corresponden a AWS (seguridad de la nube) y cuáles corresponden al cliente (seguridad en la nube).

**modelo fundacional (FM, foundation model)** — Modelo de aprendizaje automático de gran escala preentrenado en datos masivos y diversificados que puede adaptarse a múltiples tareas descendentes mediante ajuste fino o indicaciones.

**modelo multimodal (multimodal model)** — Modelo capaz de procesar y generar más de una modalidad de datos, como texto e imágenes de forma conjunta.

**modelo personalizado (custom model)** — Modelo fundacional que ha sido ajustado finamente o adaptado con datos propios de la organización para comportarse de manera específica en un dominio o tarea.

**monitoreo (monitoring)** — Práctica de seguimiento continuo de las métricas operativas y de calidad de un sistema de IA en producción para detectar degradaciones, anomalías o violaciones de política.

**motor de recomendaciones (recommendation engine)** — Sistema de aprendizaje automático que predice y sugiere elementos relevantes (productos, contenidos, acciones) según el comportamiento e historial del usuario.

**muestreo por núcleo (nucleus sampling, top-p)** — Estrategia de decodificación que selecciona aleatoriamente el siguiente token entre los que acumulativamente representan una probabilidad p del total, controlando la aleatoriedad de la salida.

**multimodal** — Véase "modelo multimodal".

---

## N

**neural network** — Véase "red neuronal".

**NIST AI RMF** — Marco de Gestión de Riesgos de IA del Instituto Nacional de Estándares y Tecnología (National Institute of Standards and Technology) de los Estados Unidos, que define cuatro funciones para gestionar el riesgo de IA: Gobernar, Mapear, Medir y Responder.

**NLP (procesamiento del lenguaje natural)** — Véase "procesamiento del lenguaje natural".

**núcleo, muestreo por** — Véase "muestreo por núcleo".

---

## O

**OAuth 2.0** — Protocolo estándar de autorización que permite a aplicaciones acceder a recursos en nombre de un usuario sin compartir credenciales; utilizado por Amazon Bedrock AgentCore Identity para gestionar la autenticación de agentes en herramientas externas.

**one-shot** — Variante de la técnica de indicación en la que se proporciona exactamente un ejemplo de entrada-salida en el contexto del prompt.

---

## P

**parámetro (parameter)** — Valor numérico aprendido por el modelo durante el entrenamiento que determina su comportamiento; los LLMs modernos tienen miles de millones de parámetros.

**pgvector** — Extensión de código abierto para PostgreSQL que añade soporte nativo para almacenar y buscar representaciones vectoriales, utilizable con Amazon RDS y Aurora.

**peso (weight)** — Sinónimo de parámetro en el contexto de redes neuronales; valor numérico aprendido que pondera la influencia de cada conexión entre neuronas.

**política (policy)** — Documento formal que establece las normas, responsabilidades y límites de comportamiento aceptable para el desarrollo y la operación de sistemas de IA dentro de una organización.

**preentrenamiento (pre-training)** — Primera fase del entrenamiento de un modelo fundacional, en la que el modelo aprende representaciones generales del lenguaje, imágenes u otros datos a gran escala y sin supervisión humana directa.

**preentrenamiento continuo (continuous pre-training)** — Técnica que continúa el proceso de preentrenamiento de un modelo fundacional existente con datos adicionales de un dominio específico, sin modificar su arquitectura. Más económico que el preentrenamiento desde cero.

**procesamiento del lenguaje natural (PLN / NLP, natural language processing)** — Campo de la inteligencia artificial que se ocupa de la interacción entre computadoras y el lenguaje humano, abarcando tareas como comprensión, generación, traducción y análisis de sentimientos.

**Professional Solutions Architect** — Título profesional del autor; se mantiene en inglés.

**prompt** — Entrada de texto que se proporciona a un modelo de lenguaje grande para obtener una respuesta generada. Equivalente a "indicación" en prosa; se usa "prompt" en contextos de código y en nombres de técnicas como "zero-shot prompt".

---

## R

**RAG (generación aumentada por recuperación)** — Véase "generación aumentada por recuperación".

**red neuronal (neural network)** — Arquitectura computacional inspirada en el cerebro humano que consiste en capas de nodos interconectados (neuronas artificiales) que aprenden representaciones de datos mediante el ajuste de pesos durante el entrenamiento.

**reducción de dimensionalidad** — Véase "dimensionalidad, reducción de".

**referencia comparativa (benchmark)** — Conjunto de tareas o métricas estandarizadas utilizadas para evaluar y comparar el rendimiento de modelos de IA. Ejemplos: MMLU, HellaSwag, HumanEval.

**regresión (regression)** — Tarea de aprendizaje automático supervisado en la que el modelo predice un valor numérico continuo.

**representación vectorial (embedding)** — Transformación de texto, imágenes u otros datos en un vector numérico de alta dimensión que captura relaciones semánticas. Permite la búsqueda por similitud en bases de datos vectoriales.

**residencia de datos (data residency)** — Requisito regulatorio o de política que exige que los datos permanezcan almacenados y procesados dentro de una jurisdicción geográfica específica.

**retención (retention)** — Política que define los períodos mínimo y máximo durante los cuales deben conservarse los datos antes de su archivo o eliminación definitiva.

**robustez (robustness)** — Capacidad de un sistema de IA para mantener su rendimiento y comportamiento correcto ante entradas inesperadas, adversarias o fuera de distribución.

**ruido (noise)** — Variación aleatoria o irrelevante en los datos que puede dificultar el aprendizaje de patrones significativos por parte del modelo.

---

## S

**secuencia de parada (stop sequence)** — Token o cadena de caracteres específica que indica al modelo que debe dejar de generar texto en ese punto.

**seguridad / inocuidad (safety)** — En ciberseguridad: protección de sistemas contra accesos no autorizados y ataques. En IA responsable: propiedad que garantiza que el sistema no produzca salidas dañinas o peligrosas para los usuarios.

**sesgo (bias)** — Tendencia sistemática de un modelo de IA a producir predicciones inexactas o injustas, a menudo originada por desequilibrios o representación insuficiente de grupos en los datos de entrenamiento.

**sistema multiagente (multi-agent system)** — Arquitectura en la que múltiples agentes de IA colaboran o se coordinan para completar tareas complejas que superan las capacidades de un único agente.

**sobreajuste (overfitting)** — Fenómeno en el que un modelo aprende los detalles y el ruido de los datos de entrenamiento de forma tan precisa que pierde capacidad de generalización a datos nuevos.

**Stability AI** — Empresa de IA de terceros conocida por el modelo de difusión Stable Diffusion, disponible en algunos contextos de AWS Marketplace.

**Strands Agents** — Marco de código abierto de AWS para construir agentes de IA con bucles de razonamiento, memoria y acceso a herramientas.

**subajuste (underfitting)** — Fenómeno en el que un modelo es demasiado simple para capturar la estructura subyacente de los datos, produciendo un rendimiento deficiente tanto en entrenamiento como en evaluación.

---

## T

**tarjeta de modelo (model card)** — Documento estructurado que describe las características de un modelo de aprendizaje automático, incluyendo su propósito, datos de entrenamiento, métricas de rendimiento, sesgos conocidos, limitaciones y políticas de uso previstas.

**temperatura (temperature)** — Parámetro de inferencia que controla la aleatoriedad de la generación de texto: valores bajos producen salidas más deterministas; valores altos, salidas más variadas y creativas.

**texto a imagen (text-to-image)** — Tarea de generación multimodal en la que el modelo genera una imagen a partir de una descripción textual.

**TLS** — Transport Layer Security; protocolo criptográfico que protege las comunicaciones en tránsito entre clientes y servidores.

**token** — Unidad básica de procesamiento de texto en los modelos de lenguaje grande. Puede ser una palabra, parte de una palabra o un símbolo de puntuación; la mayor parte de los precios de los servicios de FM se calculan por número de tokens procesados.

**tokenización (tokenization)** — Proceso de dividir texto en tokens para su procesamiento por un modelo de lenguaje.

**top-k** — Parámetro de inferencia que limita la selección del siguiente token a los k tokens con mayor probabilidad, reduciendo la aleatoriedad de la salida.

**top-p** — Véase "muestreo por núcleo".

**transformador (Transformer)** — Arquitectura de red neuronal introducida en 2017 que utiliza mecanismos de auto-atención para capturar dependencias a larga distancia en secuencias. Es la base de la mayoría de los modelos de lenguaje grande modernos.

**transparencia (transparency)** — Propiedad de un sistema de IA que permite a los usuarios, operadores y reguladores comprender cómo funciona el sistema, qué datos utiliza, qué limitaciones tiene y cómo toma sus decisiones.

---

## U

**uso aceptable, política de (AI-use policy)** — Documento de gobernanza que define qué casos de uso empresarial están autorizados para utilizar sistemas de IA, qué categorías de datos pueden procesar esos sistemas y qué decisiones pueden influenciar sin revisión humana.

---

## V

**veracidad (veracity)** — Propiedad de un sistema de IA responsable que mide el grado en que sus salidas son precisas, fundamentadas en evidencia y exentas de alucinaciones.

**ventana de contexto (context window)** — Número máximo de tokens que un modelo puede procesar en una sola llamada de inferencia, incluyendo el prompt de entrada y la respuesta generada.

**visión computacional (CV, computer vision)** — Campo de la inteligencia artificial que permite a los sistemas interpretar y analizar imágenes y vídeos.

**VPC (Nube Privada Virtual, Virtual Private Cloud)** — Red virtual privada e isolada dentro de AWS que proporciona control completo sobre el entorno de red, incluyendo rangos de direcciones IP, subredes, tablas de rutas y puertas de enlace.

---

## Z

**zero-shot** — Técnica de indicación en la que se solicita al modelo realizar una tarea sin proporcionar ningún ejemplo en el contexto del prompt, confiando únicamente en el conocimiento adquirido durante el preentrenamiento.
