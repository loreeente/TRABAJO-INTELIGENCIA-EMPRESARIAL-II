# CI Podcast Intelligence Agent
### Proyecto: Inteligencia Competitiva — Spotify vs YouTube vs Apple Podcasts
**Persona 3 | AI Engineering** · Stack: Python · ChromaDB · Gemini API

## Descripción
Agente de Inteligencia Competitiva con arquitectura ReAct + RAG que analiza 
el mercado de podcasts usando documentos OSINT y 10-Ks de Alphabet, Apple y Spotify.

## Capacidades
- ReAct (Reasoning + Acting): ciclo Thought → Action → Observation auditable
- RAG: búsqueda semántica sobre 26 documentos CI indexados en ChromaDB
- Confidence Scoring: niveles HIGH / MEDIUM / LOW / UNCERTAIN
- Anti-alucinación: grounding check + uncertainty logging
- AMC Analyzer: evaluación automatizada Awareness / Motivation / Capability

## Archivos
- `CI_Podcast_Agent_P3.ipynb` — notebook ejecutable en Google Colab
- `response_TC-01.json` — Análisis motivación YouTube
- `response_TC-02.json` — Signposts escenario Video Disruption  
- `response_TC-03.json` — Recomendación inversión video Spotify
- `amc_analysis.json` — Análisis AMC completo YouTube + Apple

## Ejecución
Abrir `CI_Podcast_Agent_P3.ipynb` en Google Colab y ejecutar las celdas en orden.
Requiere API key de Google AI Studio (gratuita): https://aistudio.google.com/app/apikey
