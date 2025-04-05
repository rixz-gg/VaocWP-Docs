# Guía de Comandos de Servidor

## `!bans` - Ver Usuarios Baneados

**Uso básico:** `!bans`

| Parámetro   | Descripción                                     | Ejemplo                |
|-------------|-------------------------------------------------|------------------------|
| N/A         | Muestra la lista de usuarios baneados en el servidor. | `!bans`                |

**Ejemplos:**

- `!bans` → Muestra la lista de usuarios baneados en el servidor.

---

## Permisos Necesarios

| Comando   | Owner | Admin | Mod | Usuario |
|-----------|-------|-------|-----|---------|
| `!bans`   | ✓     | ✓     | ✓*  | ✗       |

\* *Solo moderadores con permiso "Banear Miembros"*

## `!channelinfo` - Ver Información de un Canal

**Uso básico:** `!channelinfo [canal]`

| Parámetro   | Descripción                                      | Ejemplo                    |
|-------------|--------------------------------------------------|----------------------------|
| `canal`     | Mención del canal del que se quiere obtener información (opcional). Si no se menciona, muestra información sobre el canal actual. | `!channelinfo #general`    |

**Ejemplos:**

- `!channelinfo` → Muestra información sobre el canal actual.  
- `!channelinfo #canal-de-voz` → Muestra información sobre el canal de voz especificado.

---

## Permisos Necesarios

| Comando         | Owner | Admin | Mod | Usuario |
|-----------------|-------|-------|-----|---------|
| `!channelinfo`  | ✓     | ✓     | ✓*  | ✗       |

\* *Solo moderadores con permiso "Gestionar Canales"*

## `!emojis` - Ver Emojis Personalizados

**Uso básico:** `!emojis`

| Parámetro   | Descripción                                      | Ejemplo                |
|-------------|--------------------------------------------------|------------------------|
| N/A         | Muestra una lista de los emojis personalizados en el servidor. | `!emojis`              |

**Ejemplos:**

- `!emojis` → Muestra una lista de los emojis personalizados en el servidor, separados por estáticos y animados.

---

## Permisos Necesarios

| Comando     | Owner | Admin | Mod | Usuario |
|-------------|-------|-------|-----|---------|
| `!emojis`   | ✓     | ✓     | ✓*  | ✗       |

\* *Solo moderadores con permiso "Gestionar Canales"*

---

## Detalles Adicionales

- Muestra los emojis estáticos y animados por separado.
- Si no hay emojis personalizados en el servidor, se enviará un mensaje indicando que no se encontraron.
- El comando incluye estadísticas de emojis en el servidor: total de emojis, cantidad de emojis estáticos y animados.

## `!membercount` - Ver Cantidad de Miembros

**Uso básico:** `!membercount`

| Parámetro   | Descripción                                      | Ejemplo                |
|-------------|--------------------------------------------------|------------------------|
| N/A         | Muestra la cantidad de miembros en el servidor.  | `!membercount`         |

**Ejemplos:**

- `!membercount` → Muestra la cantidad total de miembros en el servidor.

---

## Permisos Necesarios

| Comando       | Owner | Admin | Mod | Usuario |
|---------------|-------|-------|-----|---------|
| `!membercount` | ✓     | ✓     | ✓*  | ✗       |

\* *Solo moderadores con permiso "Ver el Registro de Auditoría"*

---

## Detalles Adicionales

- Este comando muestra la cantidad total de miembros en el servidor.
- Si el usuario no tiene el permiso adecuado, se enviará un mensaje de error.

## `!serverinfo` - Ver Información del Servidor

**Uso básico:** `!serverinfo`

| Parámetro   | Descripción                                      | Ejemplo                |
|-------------|--------------------------------------------------|------------------------|
| N/A         | Muestra información del servidor.                | `!serverinfo`          |

**Ejemplos:**

- `!serverinfo` → Muestra información detallada del servidor, incluyendo nombre, ID, dueño, cantidad de miembros, roles, canales, fecha de creación, etc.

---

## Permisos Necesarios

| Comando       | Owner | Admin | Mod | Usuario |
|---------------|-------|-------|-----|---------|
| `!serverinfo` | ✓     | ✓     | ✓*  | ✗       |

\* *Solo moderadores con permiso "Ver el Registro de Auditoría"*

---

## Detalles Adicionales

- Este comando muestra información clave del servidor, como nombre, ID, propietario, miembros, roles, canales y fecha de creación.
- Si el usuario no tiene el permiso adecuado, se enviará un mensaje de error.

## `!userinfo` - Ver Información del Usuario

**Uso básico:** `!userinfo [usuario]`

| Parámetro   | Descripción                                      | Ejemplo                |
|-------------|--------------------------------------------------|------------------------|
| `[usuario]` | El usuario sobre el que se mostrará la información. Si no se menciona, se mostrará la información del autor del mensaje. | `!userinfo @Usuario`  |

**Ejemplos:**

- `!userinfo @Usuario` → Muestra información detallada sobre el usuario mencionado.
- `!userinfo` → Muestra información sobre el usuario que ejecuta el comando.

---

## Permisos Necesarios

| Comando       | Owner | Admin | Mod | Usuario |
|---------------|-------|-------|-----|---------|
| `!userinfo`   | ✓     | ✓     | ✓   | ✓       |

---

## Detalles Adicionales

- Este comando muestra información relevante del usuario mencionado, como nombre, ID, fecha de ingreso al servidor, fecha de creación de la cuenta y roles.
- Si el usuario mencionado no está en el servidor, se enviará un mensaje de error.
