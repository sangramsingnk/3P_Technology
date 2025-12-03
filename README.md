# Self-Learning Impact Analysis System (RAG + LLM) — Submission

**Candidate**: Sangramsing N. Kayte  
**Assignment used**: Technical Assignment — LLM & RAG Implementation. 

This project implements a **Self-Learning Impact Analysis System for Industrial Automation** for industrial automation projects, featuring: RAG-based knowledge search, tender text parsing, learning metrics, and a knowledge graph.

---

## 📂 Project Structure

## 3P/ # Working prototype code
data/
└─ example_projects.json # Knowledge base with 10 example projects
rag_pipeline.py # Knowledge Query (RAG) pipeline
parser.py # Tender Parser (extracts I/O points, protocols, redundancy, response time)
knowledge_graph.py # Knowledge Graph implementation and visualization
app.py # Streamlit Learning Metrics Dashboard
roi_calculation.md # ROI computation document


## Deliverables
- Working prototype (code in `3P/`)
- Knowledge base with 10 example projects (`data/example_projects.json`)
- Knowledge Query (RAG) (`rag_pipeline.py`)
- Tender Parser (`parser.py`)
- Learning metrics dashboard (`app.py`)
- ROI computation (``roi_calculation.md`)



## How to run (local)
1. Create virtualenv and install:
```bash
python -m venv 3P
source 3P/bin/activate
pip install -r requirements.txt

2. Start dashboard:
streamlit run app.py

3. Run demo:
python run_demo.py



⚙️ Requirements
Python 3.9+
Streamlit
Pandas
NetworkX
PyVis
Matplotlib
pip install streamlit pandas networkx pyvis matplotlib

🚀 How to Run
Clone the repository.
Ensure data/example_projects.json exists.
Run the dashboard:
streamlit run app.py


## Notes
This is a prototype for demonstration. Replace LLM API calls with your API keys and cloud vector DB for production.
