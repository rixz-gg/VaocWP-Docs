# Guía de Comandos Customizables

## `/welcome` - Sistema de Bienvenida

**Uso básico:** `/welcome set`

### Descripción:

El comando `welcome` permite configurar un mensaje de bienvenida personalizado para los nuevos miembros del servidor. El mensaje se puede configurar para incluir autor, título, descripción, pie de página, imágenes, color y si está habilitado o no.

---

### Subcomandos:

- **`/welcome set`**
  - **Descripción:** Configura el mensaje de bienvenida en un canal específico.
  - **Opciones:**
    - `channel`: Canal donde se enviarán los mensajes de bienvenida.

---

### Funcionalidad:

- **Vista Previa:**
  - Se generará una vista previa del mensaje de bienvenida, incluyendo el título, descripción y otros detalles personalizados.
  - Los usuarios podrán usar los botones para personalizar elementos como el autor, título, descripción, pie de página, imágenes y color.

- **Botones de Configuración:**
  - **Autor**: Cambia la información del autor del embed.
  - **Título**: Modifica el título del embed.
  - **Descripción**: Modifica la descripción.
  - **Footer**: Cambia el pie de página.
  - **Imágenes**: Permite cambiar las imágenes (thumbnail, imagen principal).
  - **Color**: Cambia el color del embed.

- **Activar/Desactivar:**
  - Cambia el estado de la bienvenida, activando o desactivando el sistema.

- **Botón de Test:**
  - Permite probar cómo quedará el mensaje de bienvenida en el canal configurado.

---

### Respuestas:

- **Configurar el mensaje de bienvenida:**
  - Después de configurar el sistema, se enviará el mensaje de bienvenida al canal especificado.

---

### Permisos Necesarios

| Comando          | Owner | Admin | Mod | Usuario |
|------------------|-------|-------|-----|---------|
| `/welcome set`   | ✓     | ✓     |     |         |

---

## `/goodbye` - Sistema de Despedida

**Uso básico:** `/goodbye set`

### Descripción:

El comando `goodbye` permite configurar el sistema de despedida en tu servidor. Cuando un miembro abandona el servidor, se enviará un mensaje de despedida al canal seleccionado, con opciones personalizables como el autor del mensaje, título, descripción, pie de página, entre otros.

---

### Subcomandos:

- **`/goodbye set`**
  - **Descripción:** Configura el sistema de despedida.
  - **Opciones:**
    - `channel`: Canal donde se enviarán los mensajes de despedida.

---

### Respuesta:

- **Configuración exitosa:** Se enviará una vista previa del mensaje de despedida, con la siguiente información:
  - Canal de despedida
  - Campos personalizables:
    - **Author**: Nombre y URL del autor
    - **Título**: Título del mensaje de despedida
    - **Descripción**: Descripción que aparece en el mensaje
    - **Footer**: Pie de página que muestra el número de miembros
    - **Thumbnail**: Imagen pequeña del miembro que abandona
    - **Imagen**: Imagen principal del mensaje
    - **Color**: Color de fondo del mensaje

- **Botones de configuración:** Los botones permitirán ajustar los diferentes parámetros del sistema de despedida:
  - Configuración del autor, título, descripción, footer, thumbnail, imagen y color
  - Activar o desactivar el sistema
  - Realizar un test del mensaje

---

### Permisos Necesarios

| Comando              | Owner | Admin | Mod | Usuario |
|----------------------|-------|-------|-----|---------|
| `/goodbye set`       | ✓     | ✓     |     |         |

---

## `/rolereaction` - Sistema de Reacción de Roles

**Uso básico:** `/rolereaction set`

### Descripción:

El comando `rolereaction` permite configurar un sistema de reacción de roles. Los usuarios pueden reaccionar con emojis en un mensaje específico para obtener roles dentro del servidor.

---

### Subcomandos:

- **`/rolereaction set`**
  - **Descripción:** Configura un nuevo sistema de reacción de roles.
  - **Opciones:**
    - `channel`: Canal donde se enviará el mensaje de reacción de roles.
    - `name` (opcional): Nombre identificativo para el embed.

- **`/rolereaction list`**
  - **Descripción:** Muestra todos los sistemas de reacción de roles configurados en el servidor.

- **`/rolereaction delete`**
  - **Descripción:** Elimina un sistema de reacción de roles previamente configurado.

---

### Respuestas:

- **Configurar sistema de reacción de roles:**
  - El sistema de reacción de roles será configurado en el canal seleccionado.
  - El sistema incluirá botones para personalizar el mensaje, añadir o eliminar roles, cambiar configuraciones y finalmente enviar el mensaje.

- **Listar sistemas configurados:**
  - Se mostrará un listado de los sistemas de reacción de roles configurados, con opciones para editarlos.

- **Eliminar sistema de reacción de roles:**
  - Se presentará un menú para seleccionar el sistema de reacción de roles que se desea eliminar.

---

### Permisos Necesarios

| Comando                | Owner | Admin | Mod | Usuario |
|------------------------|-------|-------|-----|---------|
| `/rolereaction set`    | ✓     | ✓     |     |         |
| `/rolereaction list`   | ✓     | ✓     |     |         |
| `/rolereaction delete` | ✓     | ✓     |     |         |

---

## `/tickets` - Sistema de Tickets

**Uso básico:** `/tickets set`

### Descripción:

El comando `tickets` permite configurar un sistema de tickets dentro de un servidor, donde los usuarios pueden crear tickets para recibir soporte del equipo. El sistema es completamente personalizable con una vista previa antes de ser enviado al canal seleccionado.

---

### Subcomandos:

- **`/tickets set`**
  - **Descripción:** Configura el sistema de tickets en un canal especificado.
  - **Opciones:**
    - `channel`: Canal donde se enviará el sistema de tickets.

---

### Funcionalidad:

- **Vista Previa:**
  - Se generará una vista previa del sistema de tickets, incluyendo el título, descripción, color y otros detalles.
  - Se mostrará una serie de botones para personalizar configuraciones como el autor, título, descripción, pie de página, imágenes y color.

- **Botones de Configuración:**
  - **Autor**: Cambia la información del autor del embed.
  - **Título**: Modifica el título del embed.
  - **Descripción**: Modifica la descripción.
  - **Pie de página**: Cambia el pie de página.
  - **Imágenes**: Permite cambiar las imágenes (thumbnail, imagen principal).
  - **Color**: Cambia el color del embed.

- **Botones del Ticket:**
  - **Crear Ticket**: Permite a los usuarios crear un ticket en el canal especificado.

- **Guardar y Enviar:**
  - Una vez que se haya configurado todo, se puede hacer clic en el botón **"Guardar y Enviar"** para finalizar la configuración y enviarlo al canal seleccionado.

---

### Respuestas:

- **Configurar el sistema de tickets:**
  - Después de configurar el sistema, se enviará el mensaje con el sistema de tickets al canal seleccionado.

---

### Permisos Necesarios

| Comando          | Owner | Admin | Mod | Usuario |
|------------------|-------|-------|-----|---------|
| `/tickets set`   | ✓     | ✓     |     |         |
