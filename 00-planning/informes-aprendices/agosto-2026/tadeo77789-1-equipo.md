# Informe 1 — Commits en el repositorio de documentación y en los repositorios de tu equipo

**Periodo:** del 11 de agosto al 30 de septiembre de 2026 (hora Colombia, UTC-5)
**Repositorio principal de la ficha:** https://github.com/code-sena/ADSO-3145556

| Campo | Valor |
|---|---|
| Aprendiz | Luis Alejandro Duarte Aldana |
| Usuario de GitHub | tadeo77789 |
| Ficha | ADSO-3145556 |
| Proyecto (equipo) | translates-sign-language (Traduce Señas) |
| Prefijo de los repositorios del equipo | `trans-sl-` |
| Correo(s) con el que haces commit | aleosea777@gmail.com · 150394398+tadeo77789@users.noreply.github.com |
| Fecha de elaboración | 2026-10-06 |

## 1. Resumen

| Repositorio | Enlace | Commits |
|---|---|---|
| `trans-sl-docs` | https://github.com/code-sena/trans-sl-docs | 3 |
| `backendTS` | https://github.com/mauro-1508/backendTS | 5 |
| `frontendTS` | https://github.com/tadeo77789/frontendTS | 6 |
| **Total** | | **14** |

## 2. Repositorio de documentación

### 2.1 `trans-sl-docs`

- **Enlace:** https://github.com/code-sena/trans-sl-docs
- **Total de commits en el periodo:** 3
- **Qué hice (2 a 3 líneas):** Completé la sección de contexto (visión general, alcance y glosario) a partir de los documentos fuente. En UX/UI añadí 17 mockups, el mapa de navegación y el sistema de diseño, y los adapté a pantallas estrechas con scripts para generarlos y verificarlos. Son pocos commits porque subí cada bloque de trabajo completo en un solo commit (ver Observaciones).

| Commit ID | Fecha y hora | Mensaje |
|---|---|---|
| [5312873](https://github.com/code-sena/trans-sl-docs/commit/5312873) | 2026-09-03 13:30 | docs(01-context): complete overview, scope and glossary from source documents |
| [473c6bb](https://github.com/code-sena/trans-sl-docs/commit/473c6bb) | 2026-09-15 21:43 | docs(12-ux-ui): add 17 mockups, navigation map and design system |
| [1b8723e](https://github.com/code-sena/trans-sl-docs/commit/1b8723e) | 2026-09-15 22:35 | docs(12-ux-ui): offline mockups adapted to narrow screens, with build and verification scripts |

## 3. Repositorios del equipo

### 3.1 `backendTS`

- **Enlace:** https://github.com/mauro-1508/backendTS
- **Total de commits en el periodo:** 5
- **Qué hice (2 a 3 líneas):** Añadí la configuración de pruebas con Vitest, el dominio de roles y permisos (IAM) y el dominio de eventos de uso (analytics). También reforcé el manejo de correos y de los códigos de un solo uso, y exigí la verificación de correo para iniciar sesión.

| Commit ID | Fecha y hora | Mensaje |
|---|---|---|
| [1bdc195](https://github.com/mauro-1508/backendTS/commit/1bdc195) | 2026-09-28 21:58 | chore(test): add vitest setup |
| [401a995](https://github.com/mauro-1508/backendTS/commit/401a995) | 2026-09-28 22:25 | feat(iam): add rbac domain |
| [413ee51](https://github.com/mauro-1508/backendTS/commit/413ee51) | 2026-09-28 22:39 | feat(analytics): add usage events domain |
| [2a0f55e](https://github.com/mauro-1508/backendTS/commit/2a0f55e) | 2026-09-29 09:39 | fix(auth): harden email and one-time codes |
| [dc811d7](https://github.com/mauro-1508/backendTS/commit/dc811d7) | 2026-09-29 09:56 | feat(auth): require email verification |

### 3.2 `frontendTS`

- **Enlace:** https://github.com/tadeo77789/frontendTS
- **Total de commits en el periodo:** 6
- **Qué hice (2 a 3 líneas):** Subí la app Expo/React Native con su README y corregí los colores de gráficas y tarjetas de las estadísticas del administrador. Después conecté el inicio de sesión real con su sesión, añadí la pantalla de verificación de correo y la carga de permisos desde IAM.

| Commit ID | Fecha y hora | Mensaje |
|---|---|---|
| [737225a](https://github.com/tadeo77789/frontendTS/commit/737225a) | 2026-09-03 12:28 | Initial commit: app Expo/React Native Traduce Senas |
| [452f2af](https://github.com/tadeo77789/frontendTS/commit/452f2af) | 2026-09-03 12:34 | docs: README del proyecto Traduce Senas |
| [3957115](https://github.com/tadeo77789/frontendTS/commit/3957115) | 2026-09-08 10:30 | fix(admin): update chart and KPI card colors on the admin stats screen |
| [67a879a](https://github.com/tadeo77789/frontendTS/commit/67a879a) | 2026-09-29 08:51 | feat(auth): use real login and session |
| [ea328e4](https://github.com/tadeo77789/frontendTS/commit/ea328e4) | 2026-09-30 05:31 | feat(auth): add email verification screen |
| [f87fe11](https://github.com/tadeo77789/frontendTS/commit/f87fe11) | 2026-09-30 12:44 | feat(access): load permissions from iam |

## 4. Verificación del aprendiz

- [ ] Todos los commits listados los hice con mi cuenta (aparece mi foto de perfil en GitHub).
- [x] Incluí los commits de **todas las ramas**, no solo de `main`.
- [x] Todos los commits caen entre el 11 de agosto y el 30 de septiembre de 2026 (hora Colombia).
- [x] Cada enlace de commit abre en GitHub.
- [x] Los repositorios en los que no tengo commits quedaron en la tabla con 0.
- [ ] El total de cada repositorio coincide con el número de filas de su tabla.

## 5. Observaciones

- **Periodo:** del 11 de agosto al 30 de septiembre de 2026, hora Colombia. Se usa la fecha de autor de cada commit (la que muestra GitHub).
- **Repositorios del equipo:** el equipo trabaja en `code-sena/trans-sl-docs` (documentación), `mauro-1508/backendTS` (backend y base de datos) y `tadeo77789/frontendTS` (app móvil y web). Los repositorios `trans-sl-api`, `trans-sl-app`, `trans-sl-db` y `trans-sl-portal` no existen en `code-sena`.
- **Cómo se contó:** todas las ramas subidas a GitHub, sin commits de fusión (*Merge pull request…*). Un commit que está en varias ramas se cuenta una sola vez. Datos actualizados desde GitHub el 2026-10-06; los commits posteriores al 30 de septiembre no se incluyen.
- **Cuenta:** se comprobó en GitHub que los commits aparecen vinculados a mi cuenta `tadeo77789`.
- **Pocos commits en `trans-sl-docs`:** el número de commits no refleja la cantidad de trabajo, porque subí cada entrega completa en un solo commit en lugar de ir guardando por partes. Mis 3 commits suman 85 archivos y unas 8.600 líneas añadidas:
  - `5312873` (3 de septiembre): 4 archivos, 360 líneas (visión general, alcance y glosario).
  - `473c6bb` (15 de septiembre): 35 archivos, 7.159 líneas (17 mockups, mapa de navegación y sistema de diseño), todo en un solo commit.
  - `1b8723e` (15 de septiembre): 46 archivos, 1.077 líneas (mockups adaptados a pantallas estrechas y scripts de generación y verificación).
- **Visibilidad:** `trans-sl-docs` es privado (conviene confirmar que el instructor `ariel5253` puede abrir los enlaces); `backendTS` y `frontendTS` son públicos.


---

*Declaro que la información de este informe es veraz y que los commits listados son de mi autoría.*

**Aprendiz:** ______________________  **Fecha:** ______________
