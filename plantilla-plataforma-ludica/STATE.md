# STATE.md

Estado del proyecto. Leer al iniciar cada sesión y actualizar al cerrarla.

## Estado actual

Proyecto de plataforma lúdica configurado.
Curso asignado: Lectura.
Mecánica: Niveles.
Regla: desbloquear el siguiente nivel con mínimo 80 % de aciertos.
Las 7 pruebas pasan correctamente, incluyendo GET /api/version.
El endpoint GET /api/version devuelve {"version": proyecto.VERSION}.
AGENTS.md actualizado y ajustado a máximo 40 líneas.

## Decisiones

| Fecha | Decisión | Motivo |
| --- | --- | --- |
| 23/11/2026 | Curso Lectura y mecánica Niveles | Según el Anexo A |
| 23/11/2026 | Desbloqueo con 80 % de aciertos | Cumplir la regla de la mecánica |
| 23/11/2026 | Endpoint GET /api/version con la versión de app/proyecto.py | Exponer la versión centralizada del proyecto y comprobarla con una prueba |

## Siguiente paso

Continuar con la Actividad 3 del Taller 3: configuración de secretos y permisos de los agentes.