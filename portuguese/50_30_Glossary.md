# Glossário

Este glossário define os termos técnicos e os acrônimos mais importantes usados neste livro. Os termos aparecem em português com o equivalente em inglês entre parênteses quando a distinção é relevante para o exame. Os nomes de serviços, produtos e ferramentas da AWS são mantidos em inglês conforme o uso oficial.

## A

**acurácia** (accuracy) — Proporção de previsões corretas em relação ao total de previsões. Distingue-se de precisão e revocação: um modelo pode ter alta acurácia geral mas baixa precisão em uma classe específica.

**adaptação de domínio** (domain adaptation) — Técnica de ajuste fino que adapta um modelo pré-treinado de um domínio geral (por exemplo, texto da web) para um domínio específico (por exemplo, registros médicos) sem treinar do zero.

**ajuste fino** (fine-tuning) — Processo de continuar o treinamento de um modelo de fundação pré-treinado usando um conjunto de dados de domínio específico menor, para adaptar o modelo a um caso de uso particular.

**ajuste fino com eficiência de parâmetros** (parameter-efficient fine-tuning, PEFT) — Família de técnicas de ajuste fino que modificam apenas um pequeno subconjunto dos parâmetros do modelo, reduzindo o custo computacional. Inclui LoRA e QLoRA.

**ajuste de instrução** (instruction tuning) — Variante do ajuste fino que treina o modelo em pares de instrução e resposta para melhorar sua capacidade de seguir instruções em linguagem natural.

**alucinação** (hallucination) — Resposta gerada por um LLM que é apresentada com confiança mas é factualmente incorreta ou não está fundamentada em nenhuma fonte fornecida ao modelo.

**Amazon Augmented AI (A2I)** — Serviço da AWS para criar fluxos de trabalho de revisão humana de previsões de aprendizado de máquina, especialmente para interações de baixa confiança.

**Amazon Bedrock** — Serviço gerenciado da AWS que fornece acesso a modelos de fundação de vários provedores por meio de uma API unificada.

**Amazon Bedrock AgentCore** — Conjunto de capacidades no Amazon Bedrock para criar, implantar e gerenciar agentes de IA em produção, incluindo gerenciamento de identidade, autorização e memória.

**Amazon Bedrock Guardrails** — Camada configurável de políticas de conteúdo no Amazon Bedrock que filtra prompts e respostas por tópico, toxicidade, informações sensíveis e ancoragem.

**Amazon Bedrock Knowledge Bases** — Recurso do Amazon Bedrock que conecta modelos de fundação a fontes de dados externas para implementar a arquitetura RAG de forma gerenciada.

**Amazon SageMaker Clarify** — Ferramenta da AWS que calcula valores SHAP para atribuição de características em modelos de ML clássicos e métricas de viés pré e pós-treinamento.

**Amazon SageMaker Model Cards** — Documentos estruturados no Amazon SageMaker que registram o propósito, os dados de treinamento, as métricas de avaliação e as limitações de um modelo para fins de auditoria e governança.

**Amazon SageMaker Model Monitor** — Serviço que monitora continuamente as estatísticas das entradas de inferência e alertas quando detecta deriva em relação à distribuição do conjunto de dados de treinamento.

**ancoragem** (grounding) — Propriedade de uma resposta de IA que pode ser vinculada a fatos verificáveis nos documentos de origem. Em RAG, a ancoragem mede se a resposta do modelo é suportada pelo contexto recuperado.

**aprendizado autossupervisionado** (self-supervised learning) — Paradigma de treinamento no qual o modelo aprende a partir de dados não rotulados gerando seus próprios sinais de supervisão, como prever a próxima palavra em uma sequência.

**aprendizado de máquina (ML)** (machine learning) — Subcampo da inteligência artificial em que sistemas aprendem padrões a partir de dados sem serem explicitamente programados para cada tarefa.

**aprendizado por reforço** (reinforcement learning) — Paradigma de aprendizado em que um agente aprende a tomar ações em um ambiente para maximizar uma recompensa acumulada.

**aprendizado por reforço com feedback humano (RLHF)** (reinforcement learning from human feedback) — Técnica de ajuste fino que usa avaliações humanas das respostas do modelo para treinar um modelo de recompensa e então otimizar o modelo de linguagem para maximizar essa recompensa.

**aprendizado por transferência** (transfer learning) — Técnica que aplica o conhecimento adquirido em uma tarefa ou domínio a uma tarefa diferente mas relacionada.

**aprendizado profundo** (deep learning) — Subcampo do aprendizado de máquina que usa redes neurais com múltiplas camadas para aprender representações hierárquicas dos dados.

**aprendizado semissupervisionado** (semi-supervised learning) — Paradigma de aprendizado que combina uma pequena quantidade de dados rotulados com uma grande quantidade de dados não rotulados durante o treinamento.

**aprendizado supervisionado** (supervised learning) — Paradigma de aprendizado em que o modelo é treinado em pares de entrada e saída rotulados para aprender uma função de mapeamento.

**ataque adversarial** (adversarial attack) — Entrada criada deliberadamente para enganar ou degradar o desempenho de um modelo de ML, explorando suas vulnerabilidades internas.

**atribuição de características** (feature attribution) — Técnica de explicabilidade que quantifica a contribuição de cada característica de entrada para a previsão do modelo em uma instância específica.

**aumento de dados** (data augmentation) — Técnica de criação de exemplos de treinamento adicionais por meio de transformações dos dados existentes, como rotações de imagem ou substituições de palavras.

**avaliação** (evaluation) — Processo sistemático de medir o desempenho de um modelo de IA em relação a métricas definidas em um conjunto de dados de referência.

**avaliação de modelo** (model evaluation) — Avaliação abrangente do desempenho, segurança, equidade e limitações de um modelo, geralmente realizada antes da implantação em produção.

## B

**banco de dados vetorial** (vector database) — Banco de dados projetado para armazenar e consultar eficientemente representações vetoriais (embeddings), suportando pesquisa por similaridade semântica.

**barreira de proteção** (guardrail) — Controle de política aplicado às entradas ou saídas de um sistema de IA para bloquear conteúdo fora dos limites definidos pela organização.

**base de conhecimento** (knowledge base) — Coleção de documentos indexados e consultáveis que um sistema RAG recupera ao responder consultas.

**BLEU** — Métrica de avaliação automática de saídas de texto que mede a sobreposição de n-gramas entre o texto gerado e os textos de referência.

## C

**cadeia de pensamento** (chain-of-thought) — Técnica de engenharia de prompts que solicita ao modelo que mostre seu raciocínio passo a passo antes de apresentar a resposta final, melhorando o desempenho em tarefas de raciocínio.

**cache de prompts** (prompt caching) — Recurso de inferência que armazena o resultado do processamento de segmentos repetidos do prompt (como instruções de sistema longas), reduzindo latência e custo.

**catálogo de modelos** (model catalog) — Repositório centralizado de modelos de fundação disponíveis, com metadados sobre suas capacidades, provedores e termos de uso.

**chatbot** — Sistema conversacional baseado em software que simula interações em linguagem natural com usuários humanos.

**ciclo de vida dos dados** (data lifecycle) — Sequência completa das etapas pelas quais os dados passam, desde a criação ou aquisição até o arquivo ou exclusão, com controles de governança em cada etapa.

**classificação** (classification) — Tarefa de aprendizado de máquina que atribui entradas a categorias predefinidas.

**complexidade do modelo** (model complexity) — Grau de capacidade representacional de um modelo, determinado pelo número de parâmetros e pela profundidade de sua arquitetura.

**computação em nuvem** (cloud computing) — Entrega sob demanda de recursos de TI, como armazenamento, computação e banco de dados, por meio da internet com precificação por uso.

**conjunto de dados** (dataset) — Coleção de exemplos de dados usados para treinar, validar ou testar um modelo de aprendizado de máquina.

**conjunto de dados de referência** (benchmark dataset) — Conjunto de dados padronizado usado para comparar o desempenho de diferentes modelos ou abordagens em uma tarefa específica.

**conformidade** (compliance) — Estado de aderência a leis, regulamentos, padrões e políticas aplicáveis a um sistema ou organização.

**controle de acesso** (access control) — Conjunto de políticas e mecanismos que determinam quem pode acessar quais recursos e realizar quais ações.

**criptografia** (encryption) — Processo de codificação de dados de forma que apenas partes autorizadas possam decodificá-los e lê-los.

**criptografia em repouso** (encryption at rest) — Proteção de dados armazenados em disco, banco de dados ou outro meio de armazenamento contra acesso não autorizado.

**criptografia em trânsito** (encryption in transit) — Proteção de dados transmitidos por uma rede por meio de protocolos como TLS.

## D

**dados de séries temporais** (time-series data) — Dados coletados em intervalos de tempo regulares, como métricas de telemetria ou preços de ações.

**dados estruturados** (structured data) — Dados organizados em um formato predefinido, como tabelas de banco de dados ou arquivos CSV.

**dados não estruturados** (unstructured data) — Dados sem um formato organizado predefinido, como texto livre, imagens, áudios e vídeos.

**dados rotulados** (labeled data) — Dados de treinamento onde cada exemplo possui uma anotação ou rótulo de resposta correta produzida por humanos.

**dados sintéticos** (synthetic data) — Dados gerados artificialmente para simular dados reais, frequentemente usados quando os dados reais são escassos ou sensíveis.

**declaração de tarefa** (task statement) — Elemento do guia de exame AWS que descreve uma competência específica avaliada em um domínio do exame.

**deriva de dados** (data drift) — Mudança na distribuição estatística dos dados de entrada em produção em relação à distribuição dos dados de treinamento, podendo degradar o desempenho do modelo.

**deriva do modelo** (model drift) — Degradação gradual do desempenho de um modelo em produção causada por mudanças nos padrões de dados ou no ambiente operacional.

**destilação de modelo** (model distillation) — Técnica de compressão de modelos em que um modelo menor (aluno) aprende a imitar as saídas de um modelo maior (professor).

**difusão** (diffusion model) — Classe de modelos generativos que aprendem a gerar dados (especialmente imagens) revertendo iterativamente um processo de adição de ruído.

## E

**embeddings** — Representações numéricas densas de itens (palavras, documentos, imagens) em um espaço vetorial de alta dimensão, onde a similaridade semântica se reflete na proximidade geométrica.

**engenharia de características** (feature engineering) — Processo de selecionar, transformar e criar variáveis de entrada para melhorar o desempenho de um modelo de aprendizado de máquina.

**engenharia de contexto** (context engineering) — Prática de estruturar e otimizar as informações colocadas na janela de contexto do modelo para melhorar a qualidade das respostas.

**engenharia de prompts** (prompt engineering) — Prática de formular e otimizar prompts para obter as melhores respostas de um modelo de linguagem grande.

**época** (epoch) — Uma passagem completa por todos os exemplos do conjunto de dados de treinamento durante o processo de treinamento do modelo.

**equidade** (fairness) — Propriedade de um sistema de IA que garante que suas previsões e decisões não discriminem sistematicamente grupos de pessoas com base em atributos sensíveis como raça, gênero ou idade.

**explicabilidade** (explainability) — Capacidade de um sistema de IA de fornecer razões compreensíveis para humanos sobre como chegou a uma determinada saída, mesmo que a estrutura interna seja complexa.

## F

**F1 score** — Média harmônica de precisão e revocação, usada para avaliar o desempenho de classificadores especialmente quando as classes são desbalanceadas.

**filtragem de conteúdo** (content filtering) — Aplicação de políticas para remover ou bloquear conteúdo inadequado das entradas ou saídas de um sistema de IA.

**fragmentação** (chunking) — Processo de dividir documentos longos em partes menores e sobrepostas para ingestão em um armazenamento vetorial de RAG.

**função de ativação** (activation function) — Função matemática aplicada à saída de cada neurônio em uma rede neural para introduzir não-linearidade, como ReLU ou sigmoide.

**fundamentação** (grounding) — Veja ancoragem.

## G

**geração aumentada por recuperação (RAG)** (retrieval-augmented generation) — Arquitetura que melhora as respostas de um LLM recuperando documentos relevantes de uma base de conhecimento e incluindo-os no contexto do prompt antes da geração.

**geração de imagens** (image generation) — Tarefa de criação de imagens a partir de descrições textuais ou outras imagens usando modelos generativos.

**governança** (governance) — Conjunto de políticas, processos e controles que garantem que os sistemas de IA sejam desenvolvidos e operados de forma responsável, segura e em conformidade com as regulamentações.

**governança de dados** (data governance) — Disciplina de gerenciamento do ciclo de vida, qualidade, acesso, residência e retenção dos dados ao longo de todo o seu ciclo de vida.

**GPU** (Graphics Processing Unit) — Processador especializado em computação paralela em larga escala, amplamente utilizado para treinar modelos de aprendizado profundo.

## H

**hiperparâmetro** (hyperparameter) — Parâmetro do processo de treinamento (como taxa de aprendizado ou tamanho do lote) definido antes do treinamento, em contraste com os parâmetros do modelo que são aprendidos durante o treinamento.

**humano no circuito** (human-in-the-loop) — Design de sistema que mantém revisores humanos no processo de tomada de decisões da IA, especialmente para casos de baixa confiança ou alto impacto.

## I

**IA agêntica** (agentic AI) — Sistema de IA capaz de executar sequências de ações de forma autônoma para alcançar um objetivo, usando ferramentas e tomando decisões sem intervenção humana em cada etapa.

**IA generativa (GenAI)** (generative AI) — Classe de sistemas de IA capazes de gerar conteúdo novo, como texto, imagens, código e áudio, com base em dados de treinamento e prompts.

**IA responsável** (responsible AI) — Conjunto de princípios e práticas para desenvolver e operar sistemas de IA que sejam seguros, equitativos, transparentes, robustos e em conformidade com regulamentações.

**identidade** (identity) — No contexto de segurança de nuvem, representação de um usuário, serviço ou recurso que pode ser autenticado e autorizado a acessar outros recursos.

**inclusividade** (inclusivity) — Propriedade de sistemas de IA que garante que eles funcionem bem para todos os grupos de usuários, independentemente de características demográficas, idioma ou nível de habilidade.

**inferência** (inference) — Processo de usar um modelo treinado para gerar previsões ou respostas a partir de novas entradas.

**inferência assíncrona** (asynchronous inference) — Modo de inferência em que as solicitações são enfileiradas e processadas em segundo plano, adequado para cargas de trabalho em lote.

**inferência em lote** (batch inference) — Processamento de múltiplas entradas em um único job, em vez de processar cada solicitação individualmente em tempo real.

**inferência sem servidor** (serverless inference) — Modelo de implantação em que a infraestrutura de inferência é gerenciada automaticamente e escala para zero quando não há solicitações.

**inferência sob demanda** (on-demand inference) — Modelo de uso de inferência em que você paga pelo número de tokens processados sem pré-provisionar capacidade.

**informação de identificação pessoal (PII)** (personally identifiable information) — Qualquer dado que possa ser usado para identificar um indivíduo específico, como nome, CPF, endereço ou número de telefone.

**informação sensível** (sensitive information) — Dados que requerem proteção especial devido ao seu valor ou ao risco que sua exposição cria, incluindo PII, segredos comerciais e informações financeiras.

**injeção de prompt** (prompt injection) — Ataque no qual um usuário ou fonte de dados maliciosa incorpora instruções em uma entrada para fazer o modelo ignorar suas instruções originais e executar ações não autorizadas.

**isolamento de rede** (network isolation) — Separação de recursos de computação em sub-redes privadas para impedir acesso não autorizado pela internet pública.

## J

**janela de contexto** (context window) — Quantidade máxima de texto (medida em tokens) que um modelo de linguagem pode processar em uma única inferência, incluindo o prompt e a resposta gerada.

**jailbreak** — Técnica de prompt que tenta fazer um modelo de linguagem contornar suas diretrizes de segurança e gerar conteúdo que normalmente seria recusado.

## L

**lago de dados** (data lake) — Repositório centralizado que armazena grandes volumes de dados em formato bruto e em múltiplos formatos, adequado para análises e treinamento de modelos.

**latência** (latency) — Tempo decorrido entre o envio de uma solicitação e o recebimento da resposta de um sistema de inferência.

**linhagem de dados** (data lineage) — Registro completo de onde os dados se originaram, como foram transformados e como foram usados, permitindo rastreabilidade para fins de auditoria.

**log de auditoria** (audit log) — Registro cronológico e imutável de eventos, ações e acesso a recursos em um sistema, usado para fins de conformidade e investigação de incidentes.

**LoRA (Low-Rank Adaptation)** — Técnica de ajuste fino eficiente em parâmetros que adiciona matrizes de baixa dimensão treináveis ao modelo pré-treinado, reduzindo os custos computacionais.

## M

**marca d'água** (watermarking) — Técnica para incorporar um sinal oculto no conteúdo gerado por IA para permitir sua identificação posterior como produzido por máquina.

**matriz de confusão** (confusion matrix) — Tabela que resume o desempenho de um classificador mostrando as contagens de previsões corretas e incorretas para cada classe.

**mecanismo de atenção** (attention mechanism) — Componente fundamental da arquitetura Transformer que permite ao modelo pesar a importância de diferentes partes da entrada ao gerar cada parte da saída.

**memória (IA agêntica)** (memory) — Capacidade de um agente de IA de armazenar e recuperar informações de interações anteriores para manter o contexto ao longo de múltiplas sessões.

**modelo de caixa branca** (white-box model) — Modelo de aprendizado de máquina cuja lógica de decisão é inerentemente legível e interpretável, como árvores de decisão ou regressão linear.

**modelo de caixa preta** (black-box model) — Modelo de aprendizado de máquina cujo processo de decisão interno é demasiadamente complexo para ser interpretado diretamente, como redes neurais profundas.

**modelo de fundação (FM)** (foundation model) — Modelo de aprendizado de máquina de grande escala pré-treinado em enormes volumes de dados que pode ser adaptado para uma ampla variedade de tarefas downstream.

**modelo de linguagem grande (LLM)** (large language model) — Modelo de fundação baseado na arquitetura Transformer, treinado em vastos corpora de texto, capaz de gerar, resumir, traduzir e compreender linguagem natural.

**modelo de terceiros** (third-party model) — Modelo de fundação desenvolvido por uma empresa que não é a AWS, disponível por meio de serviços como o Amazon Bedrock.

**modelo personalizado** (custom model) — Modelo de fundação adaptado às necessidades específicas de uma organização por meio de ajuste fino ou pré-treinamento contínuo com dados proprietários.

**modalidade** (modality) — Tipo de dado que um modelo pode processar ou gerar, como texto, imagem, áudio, vídeo ou código.

**modelo de responsabilidade compartilhada** (shared responsibility model) — Divisão das responsabilidades de segurança entre a AWS e o cliente: a AWS protege a infraestrutura subjacente; o cliente protege seus dados, configurações e aplicativos.

**monitoramento** (monitoring) — Processo contínuo de rastrear o desempenho, a disponibilidade e o comportamento de sistemas de IA em produção para detectar anomalias e violações de política.

**multimodal** — Capacidade de um modelo de processar ou gerar múltiplos tipos de dados (texto, imagem, áudio) em uma única interação.

## N

**rede neural** (neural network) — Modelo computacional inspirado no cérebro biológico, composto por camadas de neurônios artificiais que aprendem representações hierárquicas dos dados.

**rede neural convolucional (CNN)** (convolutional neural network) — Arquitetura de rede neural especializada para processamento de dados em grade, como imagens.

**rede neural recorrente (RNN)** (recurrent neural network) — Arquitetura de rede neural projetada para processar sequências de dados, mantendo um estado interno que captura dependências temporais.

## O

**orquestração** (orchestration) — Coordenação de múltiplos componentes, serviços ou agentes de IA para executar fluxos de trabalho complexos de forma coordenada.

## P

**parâmetro** (parameter) — Valor numérico aprendido durante o treinamento de um modelo de rede neural, como pesos e vieses, que define o comportamento do modelo.

**perplexidade** (perplexity) — Métrica de avaliação de modelos de linguagem que mede quão bem o modelo prevê uma amostra de texto; valores menores indicam melhor desempenho preditivo.

**peso** (weight) — Parâmetro de uma rede neural que representa a força da conexão entre dois neurônios.

**política** (policy) — Documento ou conjunto de regras que define o comportamento esperado, as responsabilidades e os limites para o uso de sistemas de IA em uma organização.

**pré-treinamento** (pre-training) — Fase inicial do treinamento de um modelo de fundação em um conjunto de dados massivo e diversificado para aprender representações gerais de linguagem ou outras modalidades.

**pré-treinamento contínuo** (continuous pre-training) — Continuação do pré-treinamento de um modelo de fundação usando dados especializados de domínio para aprofundar seu conhecimento em uma área específica sem substituir o conhecimento geral.

**precisão** (precision) — No contexto de métricas de ML, a fração de previsões positivas que são realmente positivas. No contexto geral, sinônimo de acurácia.

**processamento de linguagem natural (PLN)** (natural language processing, NLP) — Campo da IA que estuda como computadores podem entender, gerar e manipular a linguagem humana.

**prompt** — Entrada de texto (instrução, pergunta ou contexto) fornecida a um modelo de linguagem para guiar sua resposta.

**prompt de sistema** (system prompt) — Instrução fornecida ao modelo antes da conversa com o usuário que define o papel, o comportamento e as restrições do assistente de IA.

**prompting por papel** (role prompting) — Técnica de engenharia de prompts que instrui o modelo a assumir um papel específico (por exemplo, "aja como um especialista em direito tributário") para influenciar o estilo e o conteúdo das respostas.

**provedor de modelo** (model provider) — Empresa ou organização que desenvolve e disponibiliza modelos de fundação para uso por terceiros, como Anthropic, Meta ou Cohere.

## R

**raciocínio em múltiplas etapas** (multi-step reasoning) — Capacidade de um agente ou modelo de decompor um problema complexo em subtarefas sequenciais e resolvê-las em ordem.

**regressão** (regression) — Tarefa de aprendizado de máquina que prevê um valor contínuo em vez de uma categoria discreta.

**registro de logs** (logging) — Captura sistemática de eventos, acessos e ações em um sistema para fins de auditoria, depuração e conformidade.

**representação vetorial** (embedding) — Veja embeddings.

**residência de dados** (data residency) — Requisito legal ou organizacional de que os dados permaneçam armazenados e processados dentro de uma determinada fronteira geográfica.

**responsável pela privacidade** (privacy officer) — Função organizacional responsável por garantir que os sistemas e práticas de tratamento de dados estejam em conformidade com as leis de privacidade aplicáveis.

**revocação** (recall) — Fração dos casos positivos reais que o modelo identifica corretamente; também chamada de sensibilidade.

**robustez** (robustness) — Capacidade de um sistema de IA de manter seu desempenho diante de variações nos dados de entrada, erros, perturbações adversariais ou mudanças no ambiente operacional.

**ROUGE** — Conjunto de métricas para avaliação automática de sumarização e tradução que mede a sobreposição de n-gramas entre o texto gerado e os textos de referência.

## S

**segurança** (safety) — Em sistemas de IA responsável, propriedade que garante que o sistema não produza saídas prejudiciais ou que provoquem danos físicos, psicológicos, financeiros ou sociais.

**sistema multiagente** (multi-agent system) — Arquitetura em que múltiplos agentes de IA autônomos colaboram para resolver problemas complexos que seriam difíceis para um único agente.

**sobreajuste** (overfitting) — Fenômeno em que um modelo aprende os padrões específicos do conjunto de treinamento, incluindo o ruído, e não generaliza bem para dados novos.

**sumarização** (summarization) — Tarefa de geração de um resumo conciso de um texto mais longo, preservando as informações mais importantes.

## T

**taxa de transferência** (throughput) — Número de solicitações ou tokens que um sistema de inferência processa por unidade de tempo.

**taxa de transferência provisionada** (provisioned throughput) — Modelo de faturamento de inferência em que o cliente pré-compra capacidade de processamento dedicada para garantir desempenho previsível em altos volumes.

**temperatura** (temperature) — Parâmetro de inferência que controla a aleatoriedade das saídas do modelo: valores mais altos produzem saídas mais diversas e criativas; valores mais baixos produzem saídas mais determinísticas.

**tokenização** (tokenization) — Processo de divisão do texto em unidades menores (tokens) antes de alimentá-lo ao modelo; cada token pode representar uma palavra, parte de uma palavra ou um caractere.

**token** — Unidade básica de texto processada por um LLM; pode ser uma palavra, parte de uma palavra, um sinal de pontuação ou um espaço.

**toxicidade** (toxicity) — Propriedade de conteúdo gerado por IA que é prejudicial, ofensivo, discriminatório ou de outra forma inadequado para o público pretendido.

**transformador** (Transformer) — Arquitetura de rede neural baseada em mecanismos de atenção, introduzida em 2017, que é a base da maioria dos modelos de linguagem modernos.

**transparência** (transparency) — Propriedade de um modelo de IA cuja estrutura interna, dados de treinamento e lógica de decisão podem ser inspecionados diretamente por pessoas autorizadas.

**treinamento** (training) — Processo de ajuste dos parâmetros de um modelo de aprendizado de máquina usando dados de exemplo e um algoritmo de otimização para minimizar uma função de perda.

## U

**uso de ferramentas** (tool use) — Capacidade de um agente de IA de chamar funções ou APIs externas para obter informações ou executar ações além da geração de texto.

## V

**validação cruzada** (cross-validation) — Técnica de avaliação que divide os dados em múltiplos subconjuntos e treina e avalia o modelo em diferentes combinações para estimar o desempenho generalizado.

**veracidade** (veracity) — Propriedade de sistemas de IA responsável que garante que as saídas sejam factuais, precisas e não enganosas.

**viés** (bias) — Em sistemas de IA, tendência sistemática de produzir previsões ou resultados que tratam grupos de maneira desigual ou que refletem preconceitos presentes nos dados de treinamento.

**visão computacional (VC)** (computer vision, CV) — Campo da IA que permite que computadores interpretem e entendam o conteúdo de imagens e vídeos.

**VPC (Nuvem Privada Virtual)** (Virtual Private Cloud) — Rede virtual isolada na AWS onde os recursos de computação podem ser lançados em um ambiente de rede definido pelo cliente.

## Z

**zero-shot** — Capacidade de um modelo de executar uma tarefa sem exemplos de demonstração no prompt, baseando-se apenas na instrução em linguagem natural.
