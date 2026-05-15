# はじめに

人工知能（AI）は研究分野の好奇心から、ほぼすべてのビジネスプランの最重要項目へと移行しました。小規模な小売業者は在庫予測に AI を活用し、グローバル企業は機械学習（ML）でサプライチェーンを最適化し、カスタマーサービスチームはあらゆる場所で第一次対応のスクリプトを、やり取りのたびに学習する AI アシスタントへと置き換えています。AI 戦略を持つ組織とそうでない組織の差は四半期ごとに広がっており、導入のスピードがその現実を物語っています。

カスタマーサービスはその最もわかりやすい例です。AI アシスタントは日常的な問い合わせの大半を処理し、難しい案件を担当者にエスカレートし、すべての会話を継続的な改善ループにつなげます。ビジネスへの効果は、解決までの時間の短縮、対応コストの削減、そして顧客が本当に何を求めているかへの深い理解です。

医療分野では、ML が診断と治療計画を変えています。Harvard Medical School の 2024 年の研究によれば、CHIEF と呼ばれる AI ツールが 19 種類のがんにわたって 94% の精度でがんを検出し、分子プロファイル予測から患者の生存予測まで従来の手法を上回ることが示されました。[^005001] 重要な点は、このテクノロジーが臨床医に取って代わるのではなく、より確かな情報に基づいた判断をより迅速に下せるよう支援するということです。

金融部門は保守的な評判にもかかわらず AI を積極的に採用しています。ML ベースの不正検出システムはリアルタイムで数百万件のトランザクションを分析し、人間のレビュアーでは見逃してしまうようなパターンを検出します。業界分析によれば、ML モデルを既存のルールと並行して導入した機関は不正検出にかかる時間を 70% 以上削減したと報告されています。[^005002] コスト削減の効果も大きいですが、それ以上の収穫は顧客からの信頼です。

市場はこの流れを反映しています。Grand View Research は、グローバル AI 市場が 2024 年から年間複合成長率 36.6% で成長し、2030 年までに約 1.81 兆ドルに達すると予測しています。[^005003] その数字の背後にあるのは、独自モデルの内製からインフラ、モデルホスティング、セキュリティ基盤を担うマネージド AI サービスへの着実な移行です。

Amazon Web Services はその移行の中心にいます。画像・動画分析のための Amazon Rekognition のような事前学習済みサービスから、Amazon SageMaker AI や Amazon Bedrock などのプラットフォームまで、AWS は中小規模から大規模な組織がかつて社内チームに必要とした設備投資なしに AI を始められる環境を提供しています。[^005004] 2025 年と 2026 年には AWS AI ポートフォリオがさらに拡大し、本番エージェントランタイム向けの Amazon Bedrock AgentCore、エージェント構築のオープンソース SDK としての Strands Agents、AI を活用したソフトウェア開発環境の Kiro、そして従業員向けの統合ビジネスインテリジェンスとアシスタント機能を提供する Amazon Quick が加わりました。本書が対象とする試験はこれらすべての更新を反映しています。

ライドシェアプラットフォームの Lyft を例に挙げましょう。Lyft は Amazon Bedrock を通じて Anthropic の Claude を活用し、ドライバーとライダーの問い合わせに対応して、ほとんどのケースを人間にエスカレートすることなく解決する AI エージェントを運用しています。このエージェントは平均解決時間を 87% 削減しました。[^005005] Toyota Motor North America では、Amazon Bedrock ベースのディーラーアシスタントが公式車両情報に対する検索拡張生成（RAG）を活用し、月 7,000 件以上のディーラーとのやり取りを処理し、車種固有の正確な回答を数分ではなく数秒でスタッフに提供しています。[^005007] Cox Automotive では、Amazon Bedrock AgentCore と Strands Agents 上に構築された 5 つのエージェント型 AI 製品が、人間の監視なしに販売後サービスおよび時間外の問い合わせをエンドツーエンドで処理しています。[^005008] これらはパイロットプロジェクトではなく、本書で取り上げるサービスを使って今日実際に稼働している本番環境のデプロイです。

2022 年後半に主流となった生成 AI（GenAI）は、コンテンツの作り方とソフトウェアの書かれ方をすでに変えました。マーケティングチームはパーソナライズされたコンテンツを大規模に生成し、エンジニアリングチームはテスト作成、リファクタリングの提案、バグ追跡を行う AI アシスタントと協働しています。AWS 内部でも同様の変化が進んでいます。エージェント型システムは現在、Model Context Protocol などの標準プロトコルを通じてビジネス API を呼び出す多段階タスクを計画し、マネージドメモリサービスを使って長時間実行されるやり取りのコンテキストを保持しています。

新しい機能とともに重要な課題も生まれています。AI システムの影響力が増すにつれ、倫理、バイアス、説明責任、データ漏洩に関する問題が、コンプライアンス上の特殊ケースから経営レベルの重要課題へと格上げされています。AI への投資に強力なガバナンス、明確なデータ処理ポリシー、継続的な人材育成を組み合わせた企業が着実に成果を上げています。

AI と隣接技術の融合が次の重要なフロンティアです。AI と **IoT（モノのインターネット）** センサーを組み合わせることで、リアルタイムで交通流を最適化する都市から数日前に機器の故障を予測する工場まで、「スマート」エコシステムが生まれます。AWS は、セキュアなデバイス接続のための **AWS IoT Core** やエッジで AI モデルを実行するための **AWS IoT Greengrass** といったサービスでこの動向を支えています。[^005006] これらのサービスは AI プラクティショナー試験の出題範囲外ですが、AI が次にデプロイされる場所を考える上で有用な背景知識です。

変化のスピードへの自然な反応は、興奮と不安の入り交じった感情です。どちらも正当です。筆者の考えでは、最も実用的な見方は AI が依然としてツールであるということです。その価値は人間の判断を増幅することから生まれ、人間を置き換えることではありません。AI プロジェクトのスコープを定め、適切なサービスを選び、責任を持ってリスクを管理する方法を習得した専門家が、次のビジネス変革の波をリードする人材です。

ビジネスプロフェッショナルにとって、AI リテラシーは今や職務要件の一部です。マーケティングで顧客体験をパーソナライズするにしても、財務でリスクモデルを改善するにしても、生産現場でオペレーションを最適化するにしても、AI は職場で存在感を増し続けます。**AWS 認定 AI プラクティショナー**試験（V1.1）は、その状況を自信を持って乗り越える力を身につけるための準備の場です。

本書では AI テクノロジーだけでなく、その実践的なビジネス応用も取り上げます。略語の背後にある概念をわかりやすく解説し、実際のユースケースを紹介し、どの AWS サービスがどのプロジェクトに適切かについて十分な情報に基づいた意思決定を支える語彙を提供します。

目標はみなさんを AI エンジニアやデータサイエンティストにすることではありません。AI の機会を発見し、技術チームと効果的にコミュニケーションを取り、特定の問題に AI を導入すべきかどうか、またどのように導入するかについて適切な判断を下せるビジネスプロフェッショナルになることです。本書を読み終える頃には、AWS 上の AI が今日できること、できないこと、そして責任を持って活用する方法が明確に見えているでしょう。

AI の世界は急速に動いており、学ぶべき知識の範囲は広がり続けています。本書を通じて学ぶことで、その領域を自信を持って歩み、自分自身と組織のための新たな機会を切り開く基盤が身につきます。ようこそ。

[^005001]: New AI tool can diagnose cancer, guide treatment, predict patient survival. Harvard Gazette, 2024. URL: <https://news.harvard.edu/gazette/story/2024/09/new-ai-tool-can-diagnose-cancer-guide-treatment-predict-patient-survival/>
[^005002]: Gartner's Vision: AI Transforming Healthcare Finance. LinkedIn, 2024. URL: <https://www.linkedin.com/pulse/gartners-vision-ai-transforming-healthcare-n43zf>
[^005003]: Artificial Intelligence Market Size Report, 2025-2030. Grand View Research. URL: <https://www.grandviewresearch.com/industry-analysis/artificial-intelligence-ai-market>
[^005004]: AWS AI Services Overview. URL: <https://aws.amazon.com/machine-learning/ai-services/>
[^005005]: Lyft uses Amazon Bedrock and Anthropic's Claude to power its driver and rider AI agent (re:Invent 2025). URL: <https://aws.amazon.com/blogs/aws/top-announcements-of-aws-reinvent-2025/>
[^005006]: AWS Internet of Things. URL: <https://aws.amazon.com/iot/>
[^005007]: Toyota Motor North America dealer assistant on Amazon Bedrock (re:Invent 2025). URL: <https://aws.amazon.com/blogs/industries/aws-reinvent-2025-recap-for-automotive-and-manufacturing/>
[^005008]: Cox Automotive deploys agentic AI on Amazon Bedrock AgentCore and Strands Agents (re:Invent 2025). URL: <https://aws.amazon.com/blogs/industries/aws-reinvent-2025-recap-automotive-and-manufacturing-highlights/>
