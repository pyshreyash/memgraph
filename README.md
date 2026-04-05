# MemGraph: Memory Graph
The core idea is to interpret LLM conversation context, documents, etc. as Knowledge Graphs(KGs), as the size increases running typical RAG retrival pipeline face increased latency. We extend upon the idea to coarsen these KGs to Memory Graph, this optimizes the retrival process by acting as a hierarcial memory and reduces the reasoning depth for LLMs.

These KGs are heterogenous in nature, meaning different node types(entities) and edge types (relations). We aim to apply heterogenous graph coarsening methods to achieve our objective
