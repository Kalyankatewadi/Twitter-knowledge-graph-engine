# Twitter Knowledge Graph Engine  
### Entity Extraction • Co-Occurrence Graphs • PageRank • Community Detection • PyVis Dashboard

This project builds a **full knowledge-graph analytics pipeline** on tweets related to:

- **AI**  
- **Bitcoin**  
- **Stock Market**  
- **OpenAI**

It uses **snscrape** to collect tweets, **spaCy** for named entity extraction,  
builds a **Knowledge Graph** using NetworkX, identifies communities,  
computes **influence scores (PageRank)**, and displays everything in an  
interactive **PyVis Dashboard**.

---

## 🚀 Features

### ✓ Tweet Collection (snscrape)
No API keys required — enables large-volume scraping.

### ✓ Deep Text Cleaning
Noise removal → normalization → casefolding.

### ✓ Named Entity Recognition (NER)
Extracted entity types:

- PERSON  
- ORG  
- PRODUCT  
- MONEY  
- EVENT  
- GPE  

### ✓ Knowledge Graph Construction
Nodes = entities  
Edges = co-occurrences in the same tweet

### ✓ Graph Analytics
- PageRank (influence scoring)  
- Louvain community detection  
- Edge weight analysis

### ✓ Interactive Visualization
PyVis network dashboard (zooming, node selection, physics dynamics)

---

## 🧠 Architecture

