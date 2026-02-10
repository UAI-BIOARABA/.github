# Guía de Contribución

Esta guía define las normas de trabajo para este repositorio para mantener la consistencia, calidad y trazabilidad.

## ♻️ Flujo de trabajo General

1.  **Issue:** Crear un issue describiendo la tarea o bug (si aplica).
2.  **Rama:** Crear una rama desde `main` siguiendo la convención de nombres.
3.  **Código:** Hacer commits pequeños y descriptivos (Conventional Commits).
4.  **PR:** Crear un Pull Request vinculando el issue.
5.  **Revisión:** Esperar aprobación antes de hacer merge.
6.  **Limpieza:** Borrar la rama una vez fusionada.

## 🪾 Convención de Ramas

Formato: `tipo/descripcion-muy-breve`

| Tipo | Uso | Ejemplo |
| :--- | :--- | :--- |
| `feature/` | Nuevas funcionalidades | `feature/mover-pierna` |
| `fix/` | Corrección de errores | `fix/error-brazo-colapsa` |
| `refactor/` | Mejoras sin cambio funcional | `refactor/ordenar-servicios` |
| `chore/` | Tareas técnicas (deps, config) | `chore/actualizar-dependencias` |
| `docs/` | Documentación | `docs/mejora-docs` |

## ⬆️ Convención de Commits

Usamos **Conventional Commits**.
* Imperativo ("agregar", no "agregado").
* Máximo ~50 caracteres en el título.
* Sin punto final.

**Estructura:**
`tipo: descripción breve`

**Tipos permitidos:**
* `feat`: Nueva funcionalidad
* `fix`: Corrección de bug
* `docs`: Documentación
* `style`: Formato (espacios, comas)
* `refactor`: Refactor sin cambio de comportamiento
* `test`: Tests
* `chore`: Tareas varias

**Ejemplo:** `feat: agregar script para mover pierna`

## 🧹 Mantenimiento
* Actualiza dependencias regularmente.
* Elimina ramas obsoletas tras el merge.
* Mantén el README actualizado.