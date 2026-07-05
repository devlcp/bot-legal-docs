# Política de Privacidad

**Última actualización:** [05/07/2026]

Esta Política de Privacidad describe cómo MossBot ("nosotros", "nuestro" o "el Bot") recopila, utiliza y protege la información de los usuarios ("tú", "usuario") en la plataforma Discord. Al añadir el Bot a tu servidor o interactuar con él, aceptas las prácticas descritas en este documento.

### 1. Información que Recopilamos
Para funcionar correctamente y ofrecer sus características de automatización, el Bot procesa exclusivamente los datos necesarios proporcionados por la API oficial de Discord:
* **Identificadores de Discord:** IDs únicos numéricos de usuario, IDs de canales y IDs de servidores (Guild IDs).
* **Datos de Perfil Público:** Nombre de usuario, avatar y roles del servidor (únicamente para validar permisos en la ejecución de comandos).
* **Contenido de Mensajes:** Contenido de los mensajes dirigidos explícitamente al bot mediante comandos de barra (*Slash Commands*) o prefijos configurados. Estos datos se procesan en memoria RAM de forma efímera para ejecutar la acción solicitada y **no** se escriben en discos persistentes.

### 2. Uso de la Información
Los datos recopilados se utilizan estrictamente para los siguientes propósitos:
* Procesar y responder a las solicitudes y comandos invocados por los usuarios.
* Mantener configuraciones personalizadas específicas por servidor (por ejemplo, canales de registro o preferencias del sistema).
* Garantizar la estabilidad, seguridad y prevención de abusos dentro de la infraestructura local del Bot.

### 3. Almacenamiento y Retención de Datos
Nos comprometemos con la minimización de datos:
* No almacenamos registros de conversaciones completas ni metadatos de comportamiento de los usuarios.
* Las configuraciones básicas de los servidores se guardan de forma segura en bases de datos locales protegidas.
* Cualquier registro técnico de depuración (*logs*) se destruye automáticamente en un plazo máximo de 30 días.

### 4. Derechos del Usuario y Eliminación de Datos
Los usuarios tienen pleno derecho a solicitar la eliminación de cualquier dato persistente que el Bot conserve sobre ellos. 
* **Para servidores:** Expulsar (*Kick/Ban*) al Bot del servidor eliminará de forma inmediata o en el próximo ciclo automático las configuraciones del servidor de la base de datos.
* **Para usuarios individuales:** Puedes solicitar la purga completa de tus datos enviando un mensaje directo a los medios de contacto listados al final de este documento.

---
**Contacto:** Discord: devlcp#8342
