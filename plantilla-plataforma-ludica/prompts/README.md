# Prompts

Guarde aquí cada prompt relevante en un archivo Markdown nombrado así: `semana-N-tema.md`.

Cada archivo tiene cuatro partes:

## Objetivo
Agregar el endpoint GET /api/version que devuelva la versión oficial del proyecto con su prueba automatizada.

## Herramienta y modelo
GitHub Copilot, modelo Auto.

## Prompt
Lee AGENTS.md. Agrega el endpoint GET /api/version, que devuelva la versión definida en app/proyecto.py, con su prueba en tests/test_inicio.py. Antes de escribir código, explícame qué archivos vas a modificar y espera mi aprobación.

## Resultado
El agente modificó únicamente app/rutas/api.py y tests/test_inicio.py. Las 7 pruebas unitarias pasaron y Ruff no reportó errores.
