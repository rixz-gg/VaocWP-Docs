# Guía de Comandos de Auto-moderacion

## `!antilinks` - Sistema Anti-Links

**Uso básico:** `/antilinks set` | `/antilinks toggle`

### Descripción:

El comando `antilinks` permite configurar un sistema anti-links en el servidor. Este sistema detectará y gestionará los enlaces compartidos en el chat, con diferentes acciones según la configuración. Puedes configurar el canal de logs, los canales o roles ignorados, y el castigo para los usuarios que compartan enlaces.

---

### Subcomandos:

- **`/antilinks set`**
  - **Descripción:** Configura el sistema anti-links.
  - **Opciones:**
    - `channel`: Canal para los logs del sistema anti-links.

- **`/antilinks toggle`**
  - **Descripción:** Activa o desactiva el sistema anti-links.

---

### Respuesta:

- **Configuración exitosa:** Cuando configures el sistema, recibirás un embed con la información actual del sistema anti-links, incluyendo:
  - Estado (activado o desactivado)
  - Canal de logs
  - Castigo asignado (eliminar mensaje, advertencia, expulsar, banear)
  - Canales y roles ignorados
  - Dominios permitidos
  
- **Activación/Desactivación:** Al usar el subcomando `toggle`, podrás activar o desactivar el sistema.

---

## `!antispam` - Sistema Anti-Spam

**Uso básico:** `/antispam set`

### Descripción:

El comando `antispam` permite configurar el sistema anti-spam en el servidor. Este sistema ayudará a detectar y gestionar el envío de mensajes repetitivos o no deseados, con la opción de aplicar advertencias, expulsiones o baneos dependiendo de la cantidad de infracciones. Puedes configurar los límites de mensajes, las menciones, los canales de alerta y más.

---

### Subcomandos:

- **`/antispam set`**
  - **Descripción:** Configura el sistema anti-spam.
  - **Opciones:**
    - `channel`: Canal donde se enviarán las alertas del sistema anti-spam.

---

### Respuesta:

- **Configuración exitosa:** Se enviará un embed con la configuración actual del sistema anti-spam, que incluye:
  - Estado (activado o desactivado)
  - Canal de logs
  - Límites para advertencias, expulsiones y baneos
  - Parámetros de detección (ventana de tiempo, límite de mensajes, menciones)
  - Mensaje de advertencia personalizado

- **Botones de configuración:** Al configurar el sistema, se proporcionarán botones para ajustar:
  - Activar o desactivar el sistema
  - Límites de infracciones
  - Parámetros de detección
  - Mensajes
  - Inmunidades
  - Imagen de logs

---

### Permisos Necesarios

| Comando            | Owner | Admin | Mod | Usuario |
|--------------------|-------|-------|-----|---------|
| `/antilinks set`   | ✓     | ✓     |     |         |
| `/antilinks toggle`| ✓     | ✓     |     |         |
| `/antispam set`    | ✓     | ✓     |     |         |
