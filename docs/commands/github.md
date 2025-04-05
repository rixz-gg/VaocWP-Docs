# Guía de Comandos del bot con integracion de Github

## `!gitactivity` - Actividad de Repositorio de GitHub

**Uso básico:** `!gitactivity <usuario/repositorio>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `usuario/repositorio`  | Ruta del repositorio en GitHub (obligatorio)                     | `octocat/Hello-World`          |

**Ejemplos:**

- `!gitactivity torvalds/linux` → Muestra los últimos commits del repositorio de Linux  
- `!gitactivity facebook/react` → Muestra la actividad reciente del repositorio de React  

---

## ¿Qué hace este comando?

- Muestra los últimos 5 commits públicos del repositorio especificado.  
- Incluye el mensaje del commit, autor, fecha y enlace directo.  
- También muestra estadísticas básicas del repositorio:
  - ⭐ Estrellas
  - 🍴 Forks
  - 🐞 Issues abiertos  

---

## `!gitbranches` - Ver Ramas del Repositorio

**Uso básico:** `!gitbranches <usuario/repositorio>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `usuario/repositorio`  | Ruta del repositorio en GitHub (obligatorio)                     | `octocat/Hello-World`          |

**Ejemplos:**

- `!gitbranches vercel/next.js` → Muestra las ramas disponibles en el repositorio de Next.js  
- `!gitbranches nodejs/node` → Muestra todas las ramas del repositorio oficial de Node.js  

---

## ¿Qué hace este comando?

- Muestra una lista de todas las ramas (`branches`) disponibles de un repositorio público de GitHub.
- Cada rama se muestra con su nombre en una lista simple con íconos.  
- Incluye enlace directo a la sección de ramas del repositorio en GitHub.

---

## `!gitcommits` - Ver Últimos Commits del Repositorio

**Uso básico:** `!gitcommits <usuario/repositorio>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `usuario/repositorio`  | Ruta del repositorio en GitHub (obligatorio)                     | `octocat/Hello-World`          |

**Ejemplos:**

- `!gitcommits facebook/react` → Muestra los 5 commits más recientes del repositorio de React  
- `!gitcommits torvalds/linux` → Lista los últimos commits del kernel de Linux

---

## ¿Qué hace este comando?

- Obtiene y muestra los **últimos 5 commits** de un repositorio público en GitHub.
- Para cada commit se incluye:
  - Mensaje resumido
  - Autor
  - Fecha
  - Enlace directo al commit

---

## `!gitcontributors` - Ver Contribuidores del Repositorio

**Uso básico:** `!gitcontributors <usuario/repositorio>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `usuario/repositorio`  | Ruta del repositorio en GitHub (obligatorio)                     | `vercel/next.js`               |

**Ejemplos:**

- `!gitcontributors nodejs/node` → Muestra los 5 contribuidores más activos del repositorio de Node.js  
- `!gitcontributors microsoft/vscode` → Lista los principales aportantes al código de VS Code

---

## ¿Qué hace este comando?

- Muestra una lista de los **5 contribuidores principales** de un repositorio público.
- Incluye:
  - Nombre de usuario
  - Enlace al perfil de GitHub
  - Número total de contribuciones

---

## `!gitfollowing` - Ver Usuarios Seguidos de una Cuenta de GitHub

**Uso básico:** `!gitfollowing <usuario>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `usuario`              | Nombre de usuario de GitHub (obligatorio)                        | `octocat`                      |

**Ejemplos:**

- `!gitfollowing torvalds` → Muestra los 5 usuarios que Linus Torvalds sigue en GitHub  
- `!gitfollowing google` → Muestra los 5 usuarios que la cuenta oficial de Google sigue

---

## ¿Qué hace este comando?

- Muestra una lista de los **5 usuarios** que una cuenta de GitHub sigue.
- Incluye:
  - Nombre de usuario
  - Enlace al perfil de GitHub

---

## `!gitissue` - Ver Issues Abiertas de un Repositorio de GitHub

**Uso básico:** `!gitissue <repositorio>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `repositorio`          | Nombre del repositorio de GitHub en formato `usuario/repositorio` | `octocat/Hello-World`          |

**Ejemplos:**

- `!gitissue torvalds/linux` → Muestra las 5 issues abiertas en el repositorio `linux` de Linus Torvalds  
- `!gitissue facebook/react` → Muestra las 5 issues abiertas en el repositorio `react` de Facebook

---

## ¿Qué hace este comando?

- Muestra las **5 issues abiertas** más recientes de un repositorio de GitHub.
- Incluye:
  - Título de la issue
  - Enlace a la issue
  - Usuario que abrió la issue

---

## `!gitissues` - Ver Issues Abiertas y Cerradas de un Repositorio de GitHub

**Uso básico:** `!gitissues <repositorio>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `repositorio`          | Nombre del repositorio de GitHub en formato `usuario/repositorio` | `octocat/Hello-World`          |

**Ejemplos:**

- `!gitissues torvalds/linux` → Muestra las **5 issues abiertas y cerradas** en el repositorio `linux` de Linus Torvalds  
- `!gitissues facebook/react` → Muestra las **5 issues abiertas y cerradas** en el repositorio `react` de Facebook

---

## ¿Qué hace este comando?

- Muestra las **5 issues abiertas y 5 issues cerradas** más recientes de un repositorio de GitHub.
- Incluye:
  - Título de la issue
  - Enlace a la issue
  - Usuario que abrió la issue

---

## `!gitprofile` - Ver Información de un Perfil de GitHub

**Uso básico:** `!gitprofile <usuario>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `usuario`              | Nombre de usuario de GitHub.                                       | `octocat`                      |

**Ejemplos:**

- `!gitprofile torvalds` → Muestra la información del perfil de Linus Torvalds en GitHub  
- `!gitprofile facebook` → Muestra la información del perfil de la cuenta oficial de GitHub de Facebook

---

## ¿Qué hace este comando?

- Muestra la información del perfil de un usuario de GitHub, incluyendo:
  - Nombre de usuario
  - Biografía
  - Empresa
  - Ubicación
  - Enlace al blog (si tiene)
  - Repositorios públicos
  - Número de seguidores
  - Número de seguidos
  - Fecha de creación del perfil

---

## `!gitpullrequests` - Ver Pull Requests Abiertas de un Repositorio de GitHub

**Uso básico:** `!gitpullrequests <repositorio>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `repositorio`          | Nombre del repositorio de GitHub en formato `dueño/repositorio`.    | `octocat/Hello-World`          |

**Ejemplos:**

- `!gitpullrequests torvalds/linux` → Muestra las pull requests abiertas en el repositorio `linux` de Linus Torvalds  
- `!gitpullrequests facebook/react` → Muestra las pull requests abiertas en el repositorio `react` de Facebook

---

## ¿Qué hace este comando?

- Muestra las **pull requests abiertas** en un repositorio de GitHub.
  - Título de cada pull request
  - Enlace a cada pull request
  - Usuario que creó la pull request

---

## `!gitreadme` - Ver el contenido del README.md de un Repositorio de GitHub

**Uso básico:** `!gitreadme <repositorio>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `repositorio`          | Nombre del repositorio de GitHub en formato `dueño/repositorio`.    | `octocat/Hello-World`          |

**Ejemplos:**

- `!gitreadme torvalds/linux` → Muestra el contenido del archivo README.md en el repositorio `linux` de Linus Torvalds  
- `!gitreadme facebook/react` → Muestra el contenido del archivo README.md en el repositorio `react` de Facebook

---

## ¿Qué hace este comando?

- Muestra las primeras líneas del archivo `README.md` de un repositorio de GitHub.
- Si el README tiene más de 1000 caracteres, se truncará y se añadirá `...` al final.

---

## `!gitrepo` - Ver Información Detallada sobre un Repositorio de GitHub

**Uso básico:** `!gitrepo <repositorio>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `repositorio`          | Nombre del repositorio de GitHub en formato `dueño/repositorio`.    | `octocat/Hello-World`          |

**Ejemplos:**

- `!gitrepo torvalds/linux` → Muestra información detallada sobre el repositorio `linux` de Linus Torvalds  
- `!gitrepo facebook/react` → Muestra información detallada sobre el repositorio `react` de Facebook

---

## ¿Qué hace este comando?

- Muestra información detallada sobre un repositorio de GitHub.
- Incluye detalles como el propietario, el número de estrellas, bifurcaciones, problemas abiertos, el lenguaje de programación utilizado, la licencia, y las fechas de creación y actualización.

---

## `!gitsearch` - Buscar Repositorios en GitHub por Término

**Uso básico:** `!gitsearch <término>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `término`              | Término de búsqueda para encontrar repositorios en GitHub.          | `nodejs`                       |

**Ejemplos:**

- `!gitsearch nodejs` → Busca repositorios relacionados con `nodejs` en GitHub y muestra los más populares.
- `!gitsearch discord bot` → Busca repositorios relacionados con bots de Discord.

---

## ¿Qué hace este comando?

- Busca repositorios en GitHub según un término de búsqueda.
- Muestra los 5 repositorios más populares relacionados con el término de búsqueda (ordenados por número de estrellas).
- Para cada repositorio, se muestra su nombre, enlace a GitHub, número de estrellas y bifurcaciones.

---

## `!gitstats` - Mostrar Estadísticas Generales de un Usuario de GitHub

**Uso básico:** `!gitstats <usuario>`

| Parámetro             | Descripción                                                       | Ejemplo                        |
|------------------------|-------------------------------------------------------------------|--------------------------------|
| `usuario`              | Nombre de usuario de GitHub para el que deseas mostrar las estadísticas. | `octocat`                      |

**Ejemplos:**

- `!gitstats octocat` → Muestra las estadísticas generales de usuario `octocat`.
- `!gitstats user123` → Muestra las estadísticas generales del usuario `user123`.

---

## ¿Qué hace este comando?

- Muestra estadísticas generales de un usuario de GitHub, como el número de repositorios, seguidores, siguiendo, y la fecha de creación de la cuenta.
- Para cada estadística, se muestra el valor correspondiente y un enlace a su perfil de GitHub.

---

## `!gittrending` - Mostrar Repositorios Más Populares en GitHub

**Uso básico:** `!gittrending`

Este comando muestra los repositorios más populares en GitHub en este momento, ordenados por los que tienen más estrellas.

---

## ¿Qué hace este comando?

- Muestra una lista de los 5 repositorios más populares en GitHub actualmente, basados en el número de estrellas (más de 5000 estrellas).
- Incluye el nombre del repositorio, las estrellas y una breve descripción.
- Los resultados están ordenados por la cantidad de estrellas, de mayor a menor.

---

## Ejemplos:

- `!gittrending` → Muestra los 5 repositorios más populares de GitHub.

## Permisos Necesarios

| Comando         | Owner | Admin | Mod | Usuario |
|------------------|-------|-------|-----|---------|
| `!gitactivity` | ✓     | ✓     | ✓   | ✓       |
| `!gitbranches`   | ✓     | ✓     | ✓   | ✓       |
| `!gitcommits`    | ✓     | ✓     | ✓   | ✓       |
| `!gitcontributors`   | ✓     | ✓     | ✓   | ✓       |
| `!gitfollowing`      | ✓     | ✓     | ✓   | ✓       |
| `!gitissue`          | ✓     | ✓     | ✓   | ✓       |
| `!gitissues`         | ✓     | ✓     | ✓   | ✓       |
| `!gitprofile`        | ✓     | ✓     | ✓   | ✓       |
| `!gitpullrequests`      | ✓     | ✓     | ✓   | ✓       |
| `!gitreadme`           | ✓     | ✓     | ✓   | ✓       |
| `!gitrepo`            | ✓     | ✓     | ✓   | ✓       |
| `!gitsearch`           | ✓     | ✓     | ✓   | ✓       |
| `!gitstats`            | ✓     | ✓     | ✓   | ✓       |
