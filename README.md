# Knowledge Graph Learning Resources

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated collection of knowledge graph learning resources, including papers, tutorials, datasets, implementations, tools, and communities.

Resources are available in both English and Chinese. The language of each resource is indicated when it may not be clear from the title.

> **Link status:** All links were checked on August 26, 2026. Contributions that report broken links or improve the organization of the list are welcome.

> **Date convention:** The year shown for each resource is its latest meaningful update: recent repository or collection activity for maintained projects, and the publication or revision year for static papers, datasets, tutorials, and slides. Entries in each section are ordered from newest to oldest.

## Contents

- [Papers and Notes](#papers-and-notes)
- [Tutorials, Surveys, and Slides](#tutorials-surveys-and-slides)
- [Courses and Lectures](#courses-and-lectures)
- [Datasets](#datasets)
- [Projects and Implementations](#projects-and-implementations)
- [Libraries and Tools](#libraries-and-tools)
- [Communities](#communities)
- [Contributing](#contributing)

## Papers and Notes

Paper notes are organized with GitHub issue labels. Most existing notes are written in Chinese, but contributions in any language are welcome.

### Knowledge graph tasks

- **2023** [Information Extraction and Open IE](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22IE%28T%29%22)
- **2023** [Named Entity Recognition](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22NER%28T%29%22)
- **2023** [Relation Extraction](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22RE%28T%29%22)
- **2020** [Named Entity Linking](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22NEL%28T%29%22)
- **2020** [Knowledge Representation Learning and Knowledge Graph Embeddings](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22KRL%2FKGE%28%28T%2FM%29%22)
- **2020** [Knowledge Graph Population and Construction](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22KGP%2FKGC%28T%29%22) — constructing knowledge graphs from different sources
- **2019** [Knowledge-based Recommendation Systems](https://github.com/BrambleXu/knowledge-graph-learning/issues/250)
- **2019** [Knowledge Base Completion and Knowledge Graph Reasoning](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22KBC%2FKGR%28T%29%22) — entity prediction and link prediction
- **2019** [Ontology-based Information Extraction](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22OBIE%28T%29%22)
- **2019** [Semantic Role Labeling](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22SRL%28T%29%22)

<details>
<summary><strong>Related NLP and machine learning tasks</strong></summary>

#### Tasks

- **2024** [Recommendation](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22Recommendation%28T%29%22)
- **2023** [Question Answering and Machine Comprehension](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22QA%28T%29%22)
- **2023** [Relational Reasoning](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22RR%28T%29%22)
- **2021** [Annotation](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22Annotation%28T%29%22)
- **2021** [Domain Adaptation and Domain-specific Learning](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22DA%28T%29%22)
- **2020** [Coreference Resolution](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22CR%28T%29%22)
- **2019** [Data Augmentation](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22DataAug%28T%29%22)
- **2019** [Dependency Parsing](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22DP%28T%29%22)
- **2019** [Natural Language Understanding](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22NLU%28T%29%22)
- **2019** [Neural Machine Translation](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22NMT%28T%29%22)
- **2019** [Slot Filling](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22SF%28T%29%22)
- **2019** [Summarization](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22Summarization%28T%29%22)
- **2019** [Text Classification](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22TC%28T%29%22)

#### Models and methods

- **2023** [BERT](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22BERT%28M%29%22)
- **2023** [Embeddings and Pre-trained Models](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22Embedding%22)
- **2023** [Multi-task and Joint Learning](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22MTL%28M%29%22)
- **2019** [End-to-end Models](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22E2E%28M%29%22)
- **2019** [Graph Neural Networks](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22GNN%28M%29%22)
- **2019** [Transformer-based Models](https://github.com/BrambleXu/knowledge-graph-learning/issues?q=label%3A%22Transformer%28M%29%22)

</details>

## Tutorials, Surveys, and Slides

### General tutorials and articles

- **2026** [Awesome GraphRAG](https://github.com/DEEP-PolyU/Awesome-GraphRAG) — actively maintained collection of GraphRAG surveys, papers, benchmarks, and open-source projects
- **2025** [Ontotext Blog](https://www.ontotext.com/blog/)
- **2021** [Recent Trends in Entity Linking](https://github.com/izuna385/Entity-Linking-Recent-Trends)
- **2018** Knowledge Extraction and Inference from Text — KDD tutorial: [Part 1](https://malllabiisc.github.io/publications/tutorials/KDD2018-Part1.pdf), [Part 2](https://malllabiisc.github.io/publications/tutorials/KDD2018-Part2.pdf)
- **2018** [Knowledge Graphs: The Power of Graph-based Search](https://www.slideshare.net/neo4j/knowledge-graphs-the-power-of-graphbased-search) — Neo4j slides
- **2018** [Mining Knowledge Graphs from Text](https://kgtutorial.github.io/) — WSDM tutorial
- **2018** [知识图谱论文合集](https://zhuanlan.zhihu.com/p/44904796) (Chinese)
- **2018** [知识图谱入门（三）](http://pelhans.com/2018/03/19/xiaoxiangkg-note3/) (Chinese)
- **2017** [Enterprise Knowledge Graphs for Large Scale Analytics](https://cci.drexel.edu/bigdata/bigdata2017/files/Tutorial1-1.pdf) — IBM tutorial
- **2017** [Getting Started with Knowledge Graphs](https://www.slideshare.net/phaase/getting-started-with-knowledge-graphs) — metaphacts slides
- **2016** [Knowledge Integration in Practice](https://www.slideshare.net/pmika/knowledge-integration-in-practice) — Yahoo slides

### Surveys

- **2020** [A Survey on Knowledge Graphs: Representation, Acquisition and Applications](https://arxiv.org/pdf/2002.00388) — Shaoxiong Ji et al.
- **2019** [Deep Learning in Knowledge Graph](https://github.com/BrambleXu/knowledge-graph-learning/issues/31) — notes
- **2018** [Summary of Translation Models for Knowledge Graph Embeddings](https://medium.com/@zhuixiyou/summary-of-translate-model-for-knowledge-graph-embedding-29042be64273)
- **2017** [知识图谱研究进展](http://tie.istic.ac.cn/ch/reader/create_pdf.aspx?file_no=201701002&flag=&journal_id=qbgc&year_id=2017) — 漆桂林等 (Chinese)
- **2016** [知识图谱构建技术综述](https://crad.ict.ac.cn/cn/article/id/3127) — 刘峤等 (Chinese)
- **2016** [知识图谱技术综述](https://shengyp.github.io/files/%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1%E6%8A%80%E6%9C%AF%E7%BB%BC%E8%BF%B0.pdf) — 徐增林等 (Chinese)
- **2014** [垂直知识图谱构造工具与行业应用](http://bj.bcebos.com/cips-upload/kg2/kg2_rt.pdf) — 阮彤 (Chinese)
- **2014** [知识图谱：大数据语义链接的基石](http://bj.bcebos.com/cips-upload/kg2/kg2_ljz.pdf) — 李涓子 (Chinese)

### Relation extraction

- **2007** [A Survey on Relation Extraction](http://www.cs.cmu.edu/~nbach/papers/A-survey-on-Relation-Extraction-Slides.pdf) — CMU slides

### Event extraction

- **2018** [事件抽取与金融事件图谱构建](https://www.jiqizhixin.com/articles/2018-10-17-12) (Chinese)

## Courses and Lectures

- **2018** [从零开始构建知识图谱](https://zhuanlan.zhihu.com/c_1018901137012928512) — Zhihu column (Chinese)

## Datasets

### Relation extraction and semantic relationships

- **2021** [Annotated Semantic Relationships Datasets](https://github.com/davidsbatista/Annotated-Semantic-Relationships-Datasets) (English)
- **2019** [SemEval-2010 Task 8](https://github.com/sahitya0000/Relation-Classification) — [alternative implementation](https://github.com/shashwath94/Relation-Extraction-using-CNN)
- **2017** [TACRED](https://nlp.stanford.edu/projects/tacred/)

### Open and domain-specific knowledge graphs

- **2026** [KG-Hub and KG-OBO](https://kg-hub.berkeleybop.io/) — biomedical knowledge graph resources
- **2026** [OpenKG.CN Datasets](http://openkg.cn/datasets-type/) (Chinese)
- **2024** [PheKnowLator](https://github.com/callahantiff/PheKnowLator) — heterogeneous biomedical knowledge graphs and benchmarks

### GraphRAG benchmarks

- **2026** [GraphRAG-Bench](https://github.com/GraphRAG-Bench/GraphRAG-Benchmark) — benchmark, datasets, and evaluation code for graph-based retrieval-augmented generation

## Projects and Implementations

### GraphRAG and LLM–KG systems

- **2026** [HippoRAG](https://github.com/OSU-NLP-Group/HippoRAG) — knowledge graph and Personalized PageRank-based long-term memory framework for LLMs
- **2026** [KAG](https://github.com/OpenSPG/KAG) — logical form-guided reasoning and retrieval framework for domain knowledge bases
- **2026** [Knowledge Graph Builder](https://github.com/neo4j-labs/llm-graph-builder) — application for transforming documents and web content into a knowledge graph with LLMs
- **2026** [LightRAG](https://github.com/HKUDS/LightRAG) — graph-based retrieval-augmented generation framework with multiple storage backends and local deployment support

### Knowledge graph applications

- **2020** [KG-demo-for-movie](https://github.com/SimmerChan/KG-demo-for-movie) — movie knowledge graph and KBQA; [article](https://zhuanlan.zhihu.com/p/33363861) (Chinese)
- **2020** [Z_knowledge_graph](https://github.com/Pelhans/Z_knowledge_graph) — movie knowledge graph tutorial (Chinese)
- **2019** [KGQA_HLM](https://github.com/chizhu/KGQA_HLM) — *Dream of the Red Chamber* character graph and question answering system (Chinese)

## Libraries and Tools

### Knowledge graph construction and representation

- **2026** [BioCypher](https://github.com/biocypher/biocypher) — framework for creating and maintaining biomedical knowledge graphs
- **2026** [PyKEEN](https://github.com/pykeen/pykeen) — Python library for learning and evaluating knowledge graph embeddings
- **2024** [GRAPE](https://github.com/AnacletoLAB/grape) — Rust/Python library for graph representation learning and evaluation
- **2024** [OpenKE](https://github.com/thunlp/OpenKE) — knowledge graph embedding framework
- **2022** [cnSchema](https://github.com/cnschema/cnschema) — open Chinese knowledge graph schema
- **2020** [KnowledgeGraph](https://github.com/ownthink/KnowledgeGraph) — Chinese knowledge graph API
- **2017** [DeepDive](https://github.com/HazyResearch/deepdive) — system for extracting structured data from unstructured sources; [homepage](http://deepdive.stanford.edu/), [papers](https://github.com/HazyResearch/deepdive/blob/master/doc/papers.md)

### Semantic Web, RDF, and SPARQL

- **2026** [Apache Jena](https://github.com/apache/jena) — Java framework for Semantic Web and Linked Data applications
- **2026** [Oxigraph](https://github.com/oxigraph/oxigraph) — RDF and SPARQL toolkit and graph database with Rust, Python, and JavaScript interfaces
- **2026** [RDFLib](https://github.com/RDFLib/rdflib) — Python library for working with RDF and SPARQL

### Information extraction and annotation

- **2026** [DeepKE](https://github.com/zjunlp/DeepKE) — toolkit for entity, relation, attribute, and event extraction in knowledge graph construction
- **2026** [doccano](https://github.com/doccano/doccano) — text annotation tool
- **2025** [HanLP](https://github.com/hankcs/HanLP) — multilingual natural language processing library
- **2024** [OpenNRE](https://github.com/thunlp/OpenNRE/) — neural relation extraction toolkit; [related papers](https://github.com/thunlp/NREPapers)
- **2016** [fact_triple_extraction](https://github.com/twjiang/fact_triple_extraction) — dependency parsing-based fact triple extraction (Chinese)

### Visualization and APIs

- **2025** [InteractiveGraph](https://github.com/grapheco/InteractiveGraph) — graph visualization tool

### Additional collections

- **2025** [Useful Tools and Lectures Related to Data Science](https://github.com/BrambleXu/knowledge-graph-learning/issues/131) (Chinese)

## Communities

- **2026** [OpenKG.CN](http://openkg.cn/) — Chinese Open Knowledge Graph community
- **2016** [Beijing Knowledge Graph Study Group](https://github.com/memect/kg-beijing) (Chinese)

## Contributing

Contributions are welcome. Before opening a pull request, please make sure that:

- The resource is directly relevant to knowledge graph learning or engineering.
- The resource is publicly accessible and provides substantial educational or technical value.
- The link is stable and not duplicated elsewhere in the list.
- The entry includes a short, factual description and a language label when appropriate.
- The contribution does not primarily promote a paid product, commercial service, organization, or the contributor's own content.
- A pull request contains focused changes that are easy to review.

Commercial promotion, affiliate links, link farms, and low-content self-promotion will not be accepted. Maintainers may decline submissions at their discretion to keep the collection neutral and useful.

If you find a broken or outdated link, please open an issue or submit a pull request with a replacement.
