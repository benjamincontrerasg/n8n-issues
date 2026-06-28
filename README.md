# 🤖 Generador de Ideas de Portafolio con IA

Workflow automatizado con n8n que usa Claude AI para generar 
ideas de proyectos de desarrollo web cada día y las publica 
automáticamente como issues en GitHub.

## Flujo
Schedule Trigger → Claude API → Parser JSON → GitHub API

## Tecnologías
- n8n (automatización low-code)
- Claude AI API (Haiku)
- GitHub REST API
- JavaScript (nodo Code)
