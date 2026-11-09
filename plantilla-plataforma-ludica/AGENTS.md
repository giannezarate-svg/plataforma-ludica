# AGENTS.md

Leer este archivo y STATE.md antes de cualquier cambio.

## Proyecto
Plataforma web lúdica para niños.
Curso: Lectura.
Mecánica: Niveles.
Regla: desbloquear el siguiente nivel con mínimo 80 % de aciertos.
Roles: docente y niño. El niño ingresa con código de clase y avatar, sin correo.

## Tecnologías
Python 3.11+, FastAPI, Jinja2, SQLModel, SQLite, PostgreSQL, pytest, Ruff, GitHub Actions y Render.

## Estructura
- app/rutas/: reciben peticiones y llaman servicios.
- app/servicios/: reglas de negocio.
- app/modelos/: modelos de datos.
- app/templates/ y app/static/: interfaz y PWA.
- tests/: pruebas del proyecto.

## Comandos
Instalar: `pip install -r requirements-dev.txt`; ejecutar: `uvicorn app.main:app --reload`; probar: `pytest -v`; estilo: `ruff check .`.

## Convenciones
- Usar nombres claros y completos en español.
- Hacer cambios pequeños y probarlos.
- Revisar los cambios antes de aprobarlos.
- No hacer commit ni push: los hace el desarrollador.

## Qué no hacer
- No escribir claves ni contraseñas en el código.
- No instalar dependencias sin verificarlas.
- No modificar ni borrar pruebas para hacerlas pasar.
- No usar datos personales reales.

## Lecciones aprendidas
Registrar cada error del agente y la regla para evitar repetirlo.