# AEGIS-v1

AEGIS v1 is a **hybrid AI automation architecture** built around **reflex routing + hemisphere based routing**, designed to stay lightweight and efficient.

## Architecture (v1)
Flow:
- External Query
- Spinal (reflex layer)
- Decision Core
- Hemisphere Router (Logic / Creative)
- Refinery Core
- Final Output

## Features
- Reflex vs Route Classification
- Logiv vs Creative Hemisphere routing
- Hybrid mode: Local + API-friendly design
- Lightweight + Low-RAM friendly architecture

## Requirements
- Python 3.9+
- Ollama (optional, but recommended for reflex layer)
- Openrouter API (Default for hemispheres, cloud provider can be changed or can also use Ollama)

## Run (example)
```bash
pip install -r requirements.txt
python Main_aegis/query_handler.py
