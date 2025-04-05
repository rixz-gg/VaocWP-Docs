# Guía de Comandos de Configuracion

## `!setprefix` - Establecer un prefijo personalizado

**Uso básico:** `!setprefix <nuevo_prefijo>`

| Parámetro        | Descripción                                        | Ejemplo         |
|------------------|----------------------------------------------------|-----------------|
| `<nuevo_prefijo>` | El nuevo prefijo que deseas establecer (1-5 caracteres). | `!setprefix !`  |

**Ejemplos:**

- `!setprefix !` → Establece el prefijo del bot a `!`.

---

## `!clear` - Eliminar mensajes

**Uso básico:** `!clear <cantidad>`

| Parámetro   | Descripción                                            | Ejemplo             |
|-------------|--------------------------------------------------------|---------------------|
| `<cantidad>` | La cantidad de mensajes que deseas eliminar (1-100).    | `!clear 10`         |

**Ejemplos:**

- `!clear 10` → Elimina 10 mensajes del canal.

---

## Permisos Necesarios

| Comando            | Owner | Admin | Mod | Usuario |
|--------------------|-------|-------|-----|---------|
| `!setprefix`       | ✓     | ✓     | ✗   | ✗       |
| `!clear`           | ✓     | ✓     | ✓   | ✗       |
