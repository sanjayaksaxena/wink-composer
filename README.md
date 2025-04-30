# wink-composer ♫

### [![Stability](https://img.shields.io/badge/stability-1--experimental-orange.svg)](https://nodejs.org/api/documentation.html#documentation_stability_index)

## Streaming Data. Orchestrated. Explained.


[<img align="right" src="https://decisively.github.io/wink-logos/logo-title.png" width="100px" >](http://winkjs.org/)


WinkComposer is an **upcoming Open Source** low‑code, AI‑native streaming‑analytics framework on Node.js. It turns continuous data streams into actionable insights via a reactive processing graph, domain ontologies, and an LLM‑powered reasoning layer that delivers root‑cause analysis and recommendations.

## What is wink-composer?

WinkComposer is a high‑performance JavaScript framework for real‑time streaming analytics. It intelligently manages streaming work items, prioritising control and data messages while maintaining back‑pressure and adaptive yielding for maximum responsiveness.

Each graph node is lightweight and modular, designed to efficiently execute streaming-analytics algorithms in real time. The framework supports both synchronous CPU‑bound operations and asynchronous I/O‑bound processes, making it versatile for IoT, smart infrastructure, telematics, finance, and more. Statistical methods and machine‑learning algorithms are integrated directly into the engine and enriched by a knowledge graph that unifies business objects, patterns, and events. By persisting in graph databases such as Neo4j or ArangoDB, the knowledge graph forms a digital twin of your domain, empowering richer queries and delivering deeper insights.

WinkComposer leverages an ontology-driven, LLM-powered reasoning framework to analyze events, patterns, and data, uncover root causes, and deliver actionable recommendations. This supports near real-time insights, enabling faster, smarter decisions. Additionally, it helps support teams resolve issues quickly and accelerates onboarding with contextual learning for new team members.
	

### Our Focus
1. **Ease of Use**: Focus on your application logic without worrying about underlying complexities.

1. **Open Source/Weight LLMs**: Prioritizing smaller Open Source and efficient LLMs to empower developers.

1. **Extensibility**: Modular, loosely coupled components built for contribution.

1. **Safety & Security**: Responsible AI and OpenSSF compliance.

## Key Features

### Reactive Graph Execution
- **Adaptive Yield Threshold** keeps the event loop smooth.

- **Back‑pressure Management** prevents overload during peak streams.

- **Priority Scheduling** (control > data > async messages).

- **Monitoring Hooks & Memory Tracking** built in.

- **Node-Level Error Containment**: Node errors are captured and handled locally, ensuring the graph continues running smoothly.

- **Periodic Graph Snapshots**: Save graph state periodically to aid fast recovery.
 

### Low‑Code Graph DSL
- Declarative JSON/YAML definition of processing pipelines.

- Drag‑and‑drop UI planned.


### Plugin based Node Architecture
- Well-defined pattern for new plugin development

- Rich starter pack such as comprehensive streaming statistics, threshold/anomaly detectors, count-min sktech and MQTT/Kafka source connectors to Neo4j/Parquet sinks.

- Numerical stability
    

### Ontology, Knowledge Graph & Digital Twin
- Domain‑specific ontologies captured in a graph DB (Neo4j, ArangoDB).

- Patterns, aggregates, and events stored as first‑class nodes/edges.

- Query the digital twin for impact analysis, what‑if simulations, and contextual recommendations.

- **LLM‑assisted reasoning** layer explains anomalies and surfaces root causes.

## Contributions are welcome
We are in early development — join the conversation in [GitHub Discussions](https://github.com/winkjs/wink-composer/discussions) or email us at wink@graype.in.

Together, let’s shape the future of real‑time streaming analytics!

## About winkJS
[WinkJS](https://github.com/winkjs) is a family of open source packages for **Natural Language Processing**, **Machine Learning**, and **Statistical Analysis** in Javascript. The code is **thoroughly documented** for easy human comprehension and has a **test coverage of ~100%** for reliability to build production grade solutions.

## Copyright & License

**WinkComposer** is copyright 2024-25 [GRAYPE Systems Private Limited](https://graype.in/).

It is licensed under the terms of the MIT License.
