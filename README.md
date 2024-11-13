# Awesome-LogCodeSecurity-LLMs

Welcome to **Awesome-LogCodeSecurity-LLMs**, a curated list of resources dedicated to the intersection of code, logs, and security with large language models (LLMs). This repository aims to serve as a comprehensive guide for researchers, developers, and enthusiasts who are exploring the innovative applications of LLMs in these areas.

## What You'll Find Here:

- **Code LLMs**: Resources focused on the application of LLMs in code-related tasks, enhancing areas like code generation, analysis, and comprehension.
- **Security LLMs**: Advanced methodologies that illustrate how LLMs can improve security measures, including vulnerability detection and threat analysis.
- **Log LLMs**: Insights into leveraging LLMs for log management, facilitating tasks such as log parsing, anomaly detection, and system monitoring.

Whether you're a beginner looking to get started or an expert seeking to stay updated with the latest advancements, this repository is your go-to resource. 

Feel free to explore, contribute, and be inspired!

# Code LLMs
Comming soon.

# Security LLMs
Comming soon.

# Log LLMs
## Datasets
- [CUHK] [Loghub](https://github.com/logpai/loghub) - A collection of log data from various systems and applications provided by the Chinese University of Hong Kong.
- [CUHK] [LogPub](https://github.com/logpai/LogPub) - A library released by the Chinese University of Hong Kong containing publicly available log data from multiple sources.
- [CUHK] [bughub](https://github.com/logpai/bughub) - A collection of vulnerability reports from various software projects provided by the Chinese University of Hong Kong.
- [NAB] [The Numenta Anomaly Benchmark(NAB)](https://github.com/numenta/NAB) - An anomaly detection benchmark dataset created by Numenta.
- [Microsoft Azure] [Azure Public Dataset](https://github.com/Azure/AzurePublicDataset) - Public datasets offered by Microsoft Azure, a cloud services platform.
- [Google] [Cluster Traces](https://github.com/google/cluster-data) - Cluster trace data published by Google reflecting workload situations in their production environment.
- [Backblaze] [Hard Drive Dataset](https://www.backblaze.com/b2/hard-drive-test-data.html) - A hard drive test dataset provided by Backblaze.
- [Baidu] [SMART Dataset of PAKDD CUP 2020](https://pan.baidu.com/share/link?shareid=189977&uk=4278294944#list/path=%2FS.M.A.R.T.dataset) - SMART attribute dataset for hard drive monitoring provided by Baidu for the PAKDD CUP 2020 competition.
- [Alibaba] [SSD SMART logs and failure data](https://github.com/alibaba-edu/dcbrain/tree/master/ssd_open_data) - SSD SMART logs and failure data offered by Alibaba.
- [Alibaba] [Alibaba Cluster Trace Program](https://github.com/alibaba/clusterdata) - Alibaba's cluster trace program recording the running status of clusters.
- [Tsinghua] [AIOps Challenge Dataset](https://competition.aiops-challenge.com/home/competition/) - An AI operations challenge dataset provided by Tsinghua University.
- [Yahoo] [A Labeled Anomaly Detection Dataset](https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70) - A labeled anomaly detection dataset provided by Yahoo.
- [Mike Sconzo] [Security Repo](https://www.secrepo.com/) - A repository of security-related data created by Mike Sconzo.
- [AIT] [AIT](https://zenodo.org/records/5789064#.YkFnZWJBxhE) -- [AIT aecid](https://github.com/ait-aecid/kyoushi-environment) - A dataset for information technology security training and simulation environments provided by Austria's Institute of Technology.

## Benchmarks
- [arXiv '22] [Constructing Large-Scale Real-World Benchmark Datasets for AIOps](https://arxiv.org/abs/2208.03938) - Discusses the methods and challenges of constructing large-scale real-world AIOps benchmark datasets.
- [ASPLOS '19] [An Open-Source Benchmark Suite for Microservices and Their Hardware-Software Implications for Cloud and Edge Systems](https://dl.acm.org/doi/10.1145/3297858.3304013) - An open-source benchmark suite for microservices presented at the 2019 ASPLOS conference, exploring implications for cloud and edge systems.
- [Google Cloud] [Online Boutique (A microservices demo application)](https://github.com/GoogleCloudPlatform/microservices-demo) - A microservices demo application named "Online Boutique" provided by Google Cloud Platform, showcasing best practices in cloud-native application development and management.
- [Fudan] [Train Ticket (A benchmark microservice system)](https://github.com/FudanSELab/train-ticket) - A benchmark microservice system named "Train Ticket" developed by Fudan University's research team for studying issues in microservice architecture.
- [Weaveworks] [Sock Shop (A microservices demo application)](https://microservices-demo.github.io/) - A microservices demo application named "Sock Shop" provided by Weaveworks, designed to demonstrate how to build and deploy microservices architecture applications.

## Root Cause Analysis
- [**ASE 2024**] [The Potential of One-Shot Failure Root Cause Analysis: Collaboration of the Large Language Model and Small Classifier](https://dl.acm.org/doi/10.1145/3691620.3695475). Explores one-shot failure RCA with collaborative techniques between LLMs and classifiers.
- [**FSE Industry 2024**] [LM-PACE: Confidence Estimation by Large Language Models for Effective Root Causing of Cloud Incidents](https://arxiv.org/pdf/2309.05833.pdf). LM-PACE focuses on the role of confidence estimation in root cause analysis by employing large language models.
- [**FSE Industry 2024**] [Automated Root Causing of Cloud Incidents using In-Context Learning with GPT-4](https://arxiv.org/pdf/2401.13810v1.pdf). Discusses automated RCA for cloud incidents utilizing GPL4 with in-context learning techniques.
- [**FSE Industry 2024**] [X-lifecycle Learning for Cloud Incident Management using LLMs](https://arxiv.org/pdf/2404.03662). Examines x-lifecycle learning as a method for cloud incident management through LLMs.
- [**FSE Industry 2024**] [Exploring LLM-based Agents for Root Cause Analysis](https://arxiv.org/pdf/2403.04123). Investigates the potential for LLM-based agents in performing RCA.
- [**ICSE 2024**] [Xpert: Empowering Incident Management with Query Recommendations via Large Language Models](https://arxiv.org/pdf/2312.11988). Xpert leverages the capabilities of large language models to enhance incident management through recommended diagnostic queries.
- [**ICSE 2023**] [Recommending Root-Cause and Mitigation Steps for Cloud Incidents using Large Language Models](https://arxiv.org/pdf/2301.03797.pdf). A study on LLM usage in recommending RCA and mitigation steps for cloud incidents.
- [**Preprint 2023**] [RCAgent: Cloud Root Cause Analysis by Autonomous Agents with Tool-Augmented Large Language Models](https://arxiv.org/pdf/2310.16340.pdf). RCAgent investigates autonomous RCAs augmented by LLM tools.
- [**EMNLP 2024(Findings)**] [mABC: Multi-Agent Blockchain-inspired Collaboration for Root Cause Analysis in Micro-Services Architecture](https://arxiv.org/pdf/2404.12135). mABC employs multi-agent blockchain collaborations for effective RCA in microservices.
- [Automatic Root Cause Analysis via Large Language Models for Cloud Incidents](https://arxiv.org/abs/2305.15778) - Introduces the use of large language models for automatically analyzing root causes of cloud incidents.
- [LLM As DBA](https://arxiv.org/abs/2308.05481) -- [project](https://github.com/TsinghuaDatabaseGroup/DB-GPT) - Explores using large language models as database administrators (DBAs) to assist with database-related tasks and improve efficiency and performance.
- [A Holistic View of AI-driven Network Incident Management](https://www.microsoft.com/en-us/research/uploads/prod/2023/09/LLM4IcMs___HotNets__23-6.pdf) - A comprehensive perspective presented by Microsoft Research on AI-driven network incident management, describing how AI can improve incident management processes.
- [Assess and Summarize: Improve Outage Understanding with Large Language Models](https://arxiv.org/abs/2305.18084) - Uses large language models to assess and summarize information, improving understanding of outage (interruption) events.
- [PACE-LM: Prompting and Augmentation for Calibrated Confidence Estimation with GPT-4 in Cloud Incident Root Cause Analysis](https://arxiv.org/abs/2309.05833) - Proposes prompting and augmentation techniques for confidence calibration of GPT-4 in cloud incident root cause analysis.

## Log/AIOps LLMs
- [**EMNLP Industry 2023**] [Empower Large Language Model to Perform Better on Industrial Domain-Specific Question Answering](https://aclanthology.org/2023.emnlp-industry.29.pdf) [[project](https://github.com/ModelInteraction/MSQA)]. MSQA aims to enhance LLM capabilities for domain-specific question-answering in industrial environments.
- [**ICLR 2024**] [OWL: A Large Language Model for IT Operations](https://openreview.net/pdf?id=SZOQ9RKYJu) [[project](https://github.com/HC-Guo/Owl)]. OWL is designed specifically for IT operations, incorporating instruction tuning for improved performance.
- [**SANER 2024**] [Gloss: Guiding Large Language Models to Answer Questions from System Logs](https://ieeexplore.ieee.org/abstract/document/10589781). Gloss explores strategies for guiding LLMs to provide answers to queries derived from system logs.
- [**Preprint 2023**] [An Empirical Study of NetOps Capability of Pre-Trained Large Language Models](https://arxiv.org/pdf/2309.05557.pdf) [[project](https://huggingface.co/datasets/NASP/neteval-exam)]. NetEval empirically assesses NetOps capabilities of pre-trained LLMs.
- [**Preprint 2023**] [OpsEval: A Comprehensive Task-Oriented AIOps Benchmark for Large Language Models](https://arxiv.org/pdf/2310.07637.pdf) [[project](https://opseval.cstcloud.cn/content/home#home)]. OpsEval offers a task-oriented AIOps benchmark evaluation for large language models.
- [codefuse-ai/codefuse-devops-eval](https://github.com/codefuse-ai/codefuse-devops-eval) -- paper coming soon? - An evaluation tool for development operations released by CodeFuse AI, with related paper coming soon.

## Log Parsing

- [**ISSTA 2024**] [A Large-Scale Evaluation for Log Parsing Techniques: How Far Are We?](https://arxiv.org/pdf/2308.10828). Conducts a comprehensive evaluation of current log parsing techniques, analyzing their performance.
- [**ASE-NIER 2023**] [Log Parsing: How Far Can ChatGPT Go?](https://arxiv.org/pdf/2306.01590.pdf) [[project](https://github.com/LogIntelligence/log-analytics-chatgpt)]. Explores the capabilities and limitations of ChatGPT in the context of log parsing.
- [**ICSE 2024**] [DivLog: Log Parsing with Prompt Enhanced In-Context Learning](https://arxiv.org/pdf/2307.09950.pdf). DivLog investigates log parsing strategies employing in-context learning improved through specific prompt designs.
- [**ICSE 2024**] [LLMParser: An Exploratory Study on Using Large Language Models for Log Parsing](https://arxiv.org/pdf/2404.18001). LLMParser explores log parsing using LLMs with approaches such as prompting and finetuning.
- [**FSE 2024**] [LILAC: Log Parsing using LLMs with Adaptive Parsing Cache](https://arxiv.org/pdf/2310.01796.pdf). LILAC uses adaptive parsing caches in LLMs for enhanced log parsing efficiency.
- [**ICPC 2024**] [Interpretable Online Log Analysis Using Large Language Models with Prompt Strategies](https://arxiv.org/pdf/2308.07610.pdf). LogPrompt emphasizes interpretable log analysis leveraging strategic prompt frameworks with LLMs.
- [**Preprint 2023**] [LEMUR : Log Parsing with Entropy Sampling and Chain-of-Thought Merging](https://arxiv.org/abs/2402.18205). LEMUR introduces entropy sampling and chain-of-thought techniques for improved log parsing accuracy.
- [**Preprint 2024**] [Stronger, Cheaper and Demonstration-Free Log Parsing with LLMs](https://arxiv.org/pdf/2406.06156). LogBatcher proposes cost-effective and highly efficient log parsing methods without extensive demonstrations.
- [LLMParser: A LLM-based Log Parsing Framework](https://arxiv.org/abs/2310.01796) - Proposes a log parsing framework based on large language models.
- [**Preprint 2024**] [LUNAR: Unsupervised LLM-based Log Parsing](https://arxiv.org/pdf/2406.07174). LUNAR presents unsupervised techniques in LLM-based log parsing applications.
- [**Preprint 2024**] [Log Parsing with Self-Generated In-Context Learning and Self-Correction](https://arxiv.org/pdf/2406.03376). AdaParser elaborates on self-generated learning strategies and self-correction mechanisms in log parsing.
- [**Preprint 2024**] [OpenLogParser: Unsupervised Parsing with Open-Source Large Language Models](https://www.arxiv.org/pdf/2408.01585). OpenLogParser offers an unsupervised approach leveraging open-source LLMs for parsing logs.

## Log Anomaly Detection

- [**ICPC 2024**] [Interpretable Online Log Analysis Using Large Language Models with Prompt Strategies](https://arxiv.org/pdf/2308.07610.pdf). LogPrompt contributes to interpretable online log analysis frameworks, focusing on anomaly detection strategies.
- [**Preprint 2023**] [Log-based Anomaly Detection based on EVT Theory with feedback](https://arxiv.org/pdf/2306.05032.pdf). ScaleAD integrates EVT theory with feedback mechanisms for log anomaly detection enhancements.
- [**Preprint 2023**] [LogGPT: Exploring ChatGPT for Log-Based Anomaly Detection](https://arxiv.org/pdf/2309.01189.pdf). Investigates the potential of using ChatGPT in the detection of anomalies within log data, integrating prompting strategies.
- [**Preprint 2024**] [RAGLog: Log Anomaly Detection using Retrieval Augmented Generation](https://arxiv.org/pdf/2311.05261.pdf). RAGLog develops retrieval-augmented generation strategies for log anomaly detection.
- [**Preprint 2024**] [Anomaly Detection on Unstable Logs with GPT Models](https://arxiv.org/pdf/2406.07467). Discusses anomaly detection on unstable log environments utilising the GPT model and finetuning enhancements.

## Logging Statement Generation 
- [**ICSE 2024**] [UniLog: Automatic Logging via LLM and In-Context Learning](https://www.computer.org/csdl/proceedings-article/icse/2024/021700a129/1RLIWpCelqg). UniLog focuses on automatic logging statement generation using LLMs and in-context learning methods.
- [**FSE 2024**] [Go Static: Contextualized Logging Statement Generation](https://arxiv.org/pdf/2402.12958.pdf). SCLogger applies contextual strategies for generating logging statements, utilizing LLM capabilities.
- [**TSE 2024**] [Exploring the Effectiveness of LLMs in Automated Logging Generation: An Empirical Study](https://arxiv.org/pdf/2307.05950.pdf) [[project](https://github.com/LogStudySE/LogStudy)]. An empirical study assessing how large language models can automate and improve logging statement generation processes.


## Survey
- [**Preprint 2024**] [A Survey of AIOps for Failure Management in the Era of Large Language Models](https://arxiv.org/pdf/2406.11213). A comprehensive survey exploring the application of AIOps in failure management enhanced by large language models.
- [**Preprint 2024**] [AI Assistants for Incident Lifecycle in a Microservice Environment: A Systematic Literature Review](https://arxiv.org/pdf/2410.04334). A systematic literature review on AI assistants within microservice environments, focusing on the incident lifecycle.
- [arXiv '23] [AI for IT Operations (AIOps) on Cloud Platforms: Reviews, Opportunities and Challenges](https://arxiv.org/abs/2304.04661) - A review of AI for IT operations (AIOps) on cloud platforms, exploring current research opportunities and challenges.
- [CSUR '22] [Anomaly Detection and Failure Root Cause Analysis in (Micro) Service-Based Cloud Applications: A Survey](https://dl.acm.org/doi/full/10.1145/3501297) - A survey of anomaly detection and failure root cause analysis techniques in service-based cloud applications.
- [ASE '22] [Going through the Life Cycle of Faults in Clouds: Guidelines on Fault Handling](https://github.com/IntelligentDDS/Post-mortems-Analysis) - Provides guidelines on the lifecycle handling of faults in cloud computing environments.
- [arXiv '21] [Experience Report: Deep Learning-based System Log Analysis for Anomaly Detection](https://arxiv.org/abs/2107.05908) - Reports on the practical experience of using deep learning-based system log analysis techniques for anomaly detection.
- [CSUR '21] [A Survey on Automated Log Analysis for Reliability Engineering](https://arxiv.org/abs/2009.07237) - Studies the application of automated log analysis techniques in reliability engineering.
- [ESEC/FSE '20] [Towards intelligent incident management: why we need it and how we make it](https://dl.acm.org/doi/abs/10.1145/3368089.3417055) - Discusses why intelligent incident management is needed and how to achieve it.
- [arXiv '20] [A Systematic Mapping Study in AIOps](https://arxiv.org/abs/2012.09108) - A systematic mapping study of the AIOps field, summarizing research trends and directions.
- [ICSE '19] [AIOps: Real-World Challenges and Research Innovations](https://ieeexplore.ieee.org/document/8802836) - Introduces the real-world challenges and research innovations in AIOps.
- [HotOS '19] [What bugs cause production cloud incidents?](https://dl.acm.org/doi/10.1145/3317550.3321438) - Explores what kinds of defects can cause incidents in cloud production environments.
- [ISSRE '16] [Experience Report: System Log Analysis for Anomaly Detection](https://ieeexplore.ieee.org/document/7774521) - Shares an experience report on using system log analysis for anomaly detection.
- [ASE '13] [Software analytics for incident management of online services: An experience report](https://ieeexplore.ieee.org/document/6693105) - Shares practical experience report on using software analytics for incident management of online services.

## Resources
- [VMware] [Proactive Incident and Problem Management](https://docplayer.net/8854482-Proactive-incident-and-problem-management.html) - A guide provided by VMware on how to proactively manage incidents and problems, aimed at helping enterprises prevent and reduce issues and incidents in IT operations.
- [Awesome Open Source] [Aiops Handbook](https://awesomeopensource.com/project/chenryn/aiops-handbook) - An open-source project compiling AIOps-related resources and tools, serving as a practical handbook for implementing AI in operations.
- [GREATOPS] [《Enterprise AIOps Implementation Recommendation》White Paper](https://pic.huodongjia.com/ganhuodocs/2018-04-16/1523873064.74.pdf) - A white paper released by the GREATOPS community, providing suggestions and solutions for enterprise-level AIOps implementation.
- [rob-med] [awesome-TS-anomaly-detection](https://github.com/rob-med/awesome-TS-anomaly-detection) - A curated list on GitHub gathering various resources, libraries, frameworks, and academic papers in the field of time series anomaly detection.

## WeChat Official Accounts
- Tencent Weaving Cloud (Tencent) - An official WeChat public account operated by Tencent, dedicated to sharing Tencent's technology and experience in cloud computing, data center management, and intelligent operations.
- Intelligent Operations Frontline (Tsinghua Pei Dan Team) - The official WeChat public account of Professor Pei Dan's team at Tsinghua University, publishing the latest research progress on intelligent operations and relevant news.
- AIOps Intelligent Operations (Baidu) - Baidu's official WeChat public account, focusing on the application of artificial intelligence in IT operations and sharing the latest developments and solutions in AIOps.
- Huawei Product Servicability (Huawei) - Huawei's official WeChat public account providing information on Huawei product operations, services, and servicability capabilities.

## Other Influential Repositories
- [https://github.com/logpai](https://github.com/logpai) [active] - Logpai is a GitHub organization dedicated to research on log analysis and providing related resources, including numerous log-related projects and datasets, with active updates.
- [https://github.com/logpai/awesome-log-analysis](https://github.com/logpai/awesome-log-analysis) [active] - Awesome-log-analysis is a list curated by the logpai organization compiling tools, libraries, and resources for log analysis, continuously updated and expanded.
- [https://github.com/chenryn/aiops-handbook](https://github.com/chenryn/aiops-handbook) [active] - Aiops-handbook is an open-source manual aiming to compile learning resources, tools, and practical guides in the AIOps field, with ongoing maintenance and updates.
- [https://github.com/OpsPAI/awesome-AIOps](https://github.com/OpsPAI/awesome-AIOps) [active] - Awesome-AIOps collects excellent resources, tools, papers, and communities related to AIOps, aiming to provide references for AIOps researchers and practitioners.
- [https://github.com/zhuyiche/awesome-anomaly-detection](https://github.com/zhuyiche/awesome-anomaly-detection) [not active] - Awesome-anomaly-detection is a resource list about the field of anomaly detection, but it is no longer actively updated.
- [https://github.com/linjinjin123/awesome-AIOps](https://github.com/linjinjin123/awesome-AIOps) [not active] - Awesome-AIOps is another compilation of resources for AIOps, including related papers, tools, and frameworks, but this repository is not actively maintained.



