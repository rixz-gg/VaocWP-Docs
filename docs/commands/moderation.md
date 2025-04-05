# Guía de Comandos de Moderación del Bot

## `!ban` - Banear Usuario

**Uso básico:** `!ban @usuario [razón]`

| Parámetro | Descripción | Ejemplo |
|-----------|-------------|---------| 
| `@usuario` | Mención del usuario a banear (obligatorio) | `@NombreUsuario` |
| `razón` | Motivo del baneo (opcional) | `Spam en el chat` |

**Ejemplos:**
- `!ban @Usuario` → Banea al usuario sin especificar razón
- `!ban @Usuario Comportamiento tóxico` → Banea al usuario con razón especificada

---

## `!kick` - Expulsar Usuario

**Uso básico:** `!kick @usuario [razón]`

| Parámetro | Descripción | Ejemplo |
|-----------|-------------|---------| 
| `@usuario` | Mención del usuario a expulsar (obligatorio) | `@NombreUsuario` |
| `razón` | Motivo de la expulsión (opcional) | `Comportamiento inapropiado` |

**Ejemplos:**
- `!kick @Usuario` → Expulsa al usuario sin especificar razón
- `!kick @Usuario Spam en canales de voz` → Expulsa al usuario con razón especificada

---

## `!lockchannel` - Bloquear Canal

**Uso básico:** `!lockchannel`

**Descripción:** Bloquea el canal donde se ejecuta el comando, impidiendo que los usuarios normales puedan enviar mensajes.

**Ejemplos:**
- `!lockchannel` → Bloquea el canal actual para envío de mensajes

---

## `!slowmode` - Establecer Modo Lento

**Uso básico:** `!slowmode [segundos]`

| Parámetro | Descripción | Ejemplo |
|-----------|-------------|---------| 
| `segundos` | Tiempo de espera en segundos entre mensajes (0-21600) | `5` |

**Ejemplos:**
- `!slowmode 5` → Establece un tiempo de espera de 5 segundos entre mensajes
- `!slowmode 0` → Desactiva el modo lento en el canal

---

## `!tempban` - Baneo Temporal

**Uso básico:** `!tempban @usuario duración [razón]`

| Parámetro | Descripción | Ejemplo |
|-----------|-------------|---------| 
| `@usuario` | Mención del usuario a banear temporalmente (obligatorio) | `@NombreUsuario` |
| `duración` | Tiempo en segundos que durará el baneo (obligatorio) | `3600` |
| `razón` | Motivo del baneo temporal (opcional) | `Spam excesivo` |

**Ejemplos:**
- `!tempban @Usuario 300` → Banea al usuario por 5 minutos sin especificar razón
- `!tempban @Usuario 86400 Comportamiento tóxico reiterado` → Banea al usuario por 24 horas con razón especificada

---

## `!unban` - Desbanear Usuario

**Uso básico:** `!unban ID_usuario`

| Parámetro | Descripción | Ejemplo |
|-----------|-------------|---------| 
| `ID_usuario` | ID del usuario a desbanear (obligatorio) | `123456789012345678` |

**Ejemplos:**
- `!unban 123456789012345678` → Desbanea al usuario con la ID especificada

---

## `!unlockchannel` - Desbloquear Canal

**Uso básico:** `!unlockchannel`

**Descripción:** Desbloquea el canal donde se ejecuta el comando, permitiendo que los usuarios normales puedan enviar mensajes nuevamente.

**Ejemplos:**
- `!unlockchannel` → Desbloquea el canal actual para permitir el envío de mensajes

---

## Permisos Necesarios

| Comando | Owner | Admin | Mod | Usuario |
|---------|-------|-------|-----|---------| 
| `!ban` | ✓ | ✓ | ✓ | ✗ |
| `!kick` | ✓ | ✓ | ✓ | ✗ |
| `!lockchannel` | ✓ | ✓ | ✓ | ✗ |
| `!slowmode` | ✓ | ✓ | ✓ | ✗ |
| `!tempban` | ✓ | ✓ | ✓ | ✗ |
| `!unban` | ✓ | ✓ | ✓ | ✗ |
| `!unlockchannel` | ✓ | ✓ | ✓ | ✗ |

> *Solo moderadores con los permisos necesarios ("Banear Miembros" para !ban, "Expulsar Miembros" para !kick, "Gestionar Canales" para !lockchannel)*





