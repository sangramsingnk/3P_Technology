# Self-Learning Impact Analysis System (RAG + LLM) — Submission

**Candidate**: Sangramsing N. Kayte  
**Assignment used**: Technical Assignment — LLM & RAG Implementation. 

## Deliverables
- Working prototype (code in `3P/`)
- Knowledge base with 10 example projects (`data/example_projects.json`)
- Learning metrics dashboard (`dashboard/app.py`)
- Demo showing before/after learning (`run_demo.py`)
- Strategy document and ROI computation (`docs/strategy_document.md`, `docs/roi_calculation.md`)

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

## Notes
This is a prototype for demonstration. Replace LLM API calls with your API keys and cloud vector DB for production.
