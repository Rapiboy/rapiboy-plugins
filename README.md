# Rapiboy y Rapilog: plugins para clientes

Cuatro variantes por plataforma: Rapiboy, Rapilog, Rapiboy · UAT y Rapilog · UAT. Los paquetes sin sufijo apuntan a producción; los paquetes `-uat` apuntan exclusivamente a UAT para clientes que prueban integraciones con datos de ejemplo. Cada conexión opera sólo la cuenta autorizada mediante OAuth, según sus permisos y modalidad. La autorización de UAT es independiente de producción. Nunca pegar el token API o la contraseña en el chat.

Repositorio: https://github.com/Rapiboy/rapiboy-plugins

Cursor: catálogo `.cursor-plugin/marketplace.json` y paquetes `plugins/*-cursor`.
Claude Code: catálogo `.claude-plugin/marketplace.json` y paquetes `plugins/*-claude-code`.
Consultar el README de cada paquete para OAuth, instalación y documentación.

Claude web/Desktop utiliza un conector remoto independiente de los paquetes Claude Code. Cada directorio tiene su propio proceso de revisión; este repositorio no implica aprobación en esos directorios.

Licencia MIT para las instrucciones y archivos de los plugins. Consultar `LICENSE` y `NOTICE.md`; las marcas y los logos conservan sus derechos. Esta licencia no incluye el backend ni los datos de clientes.

Documentación: https://rapiboy.com/documentacionapi/ y https://rapilog.com.ar/documentacionapi/
