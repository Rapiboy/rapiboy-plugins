# Rapilog · UAT para Claude Code

Para clientes con cuenta activa de Rapilog. Conecta las herramientas de envíos de tu propia cuenta mediante OAuth. Las operaciones disponibles dependen de tu modalidad y permisos; las cotizaciones y cambios requieren confirmar los datos. Se mantienen las tarifas y facturación habituales, fuera del asistente. El plugin no incluye credenciales ni permite elegir cuentas ajenas.

Recurso de UAT: https://mcp-uat.rapilog.com.ar/mcp
Documentación: https://uat.rapilog.com.ar/documentacionapi/

## Conectar tu cuenta

1. Instalá el plugin de Rapilog en Claude Code.
2. Iniciá la autenticación del servidor `rapilog_uat` e ingresá con tu cuenta de cliente.
3. Revisá y autorizá los permisos solicitados. Comenzá con consultas de estados, vehículos o pedidos propios.
4. Podés retirar el acceso desde https://uat.rapilog.com.ar/oauth/mcp/conexiones.

La autenticación se realiza en el sitio de Rapilog; no pegues tu contraseña ni el token de API en el asistente.

## Ejemplos

- ¿Cuáles son los estados de pedido y los vehículos disponibles?
- Mostrame los pedidos recientes de mi cuenta.
- Ayudame a integrar mi sistema con la API de Rapilog.

## Documentación y soporte

Documentación: https://uat.rapilog.com.ar/documentacionapi/
Soporte: https://rapilog.com.ar/Home/Contacto5
Términos y privacidad: https://rapilog.com.ar/Home/TerminosCondicionesRapilog

## Licencia

MIT para los archivos del plugin. Consultá `LICENSE` y `NOTICE.md`; las marcas y los logos conservan sus derechos.

Consultar `skills/rapilog-uat-integracion/` para las instrucciones y referencias. El paquete Claude Code no sustituye al conector remoto de Claude web/Desktop, cuyo registro OAuth y presentación son independientes.

Ambiente exclusivo: UAT. Usá una cuenta de UAT y datos de ejemplo. El login OAuth compartido se abre en https://uat.rapiboy.com/Login. No cambiar a producción para resolver errores.
