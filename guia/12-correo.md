# 12. Correo

[← Volver al índice](../README.md)

Las casillas del dominio se crean y se administran en el hosting (Hostinger), en **hPanel → Emails**, no en el panel del sitio.

## Las casillas

| Dirección | Tipo | Para qué |
|---|---|---|
| `ventas@boggianofiambrerias.com.ar` | Casilla | **La que usa el sitio para enviar los avisos.** También recibe Contacto y Proveedores |
| `administracion@boggianofiambrerias.com.ar` | Casilla | Uso interno |
| `empleos@boggianofiambrerias.com.ar` | Alias de `administracion@` | Recibe los CV de las postulaciones |

> **Importante:** la contraseña de `ventas@` está cargada en la configuración del sitio. **Si la cambiás en Hostinger, hay que cambiarla también en el archivo `privado/config.php`** del hosting. Si no coinciden, los mensajes y CV siguen llegando al panel, pero no salen los avisos por mail.

Las casillas que vienen con el plan son gratis el primer año. Después hay que pagarlas o mover el correo a otro servicio.

## Dónde leer el correo

### Webmail de Hostinger (lo más simple)

Entrá a **[mail.hostinger.com](https://mail.hostinger.com)** con la dirección completa y su contraseña.

### App de Gmail en el celular

1. En la app tocá tu foto y elegí **Agregar otra cuenta → Otra**.
2. Escribí la dirección completa. Si te pide los datos a mano:

| | Servidor | Puerto | Seguridad |
|---|---|---|---|
| Entrada (IMAP) | `imap.hostinger.com` | 993 | SSL |
| Salida (SMTP) | `smtp.hostinger.com` | 465 | SSL |

En los dos, el usuario es **la dirección completa**, con la contraseña de la casilla. Lo mismo sirve para Outlook, Apple Mail o cualquier programa de correo.

### Gmail en la computadora

Si tu Gmail ya no tiene la opción de traer mails de otras cuentas (Google la estaba quitando en 2026):
1. En hPanel → **Emails**, creá un **reenvío** de la casilla a tu Gmail. El plan trae 1.
2. En Gmail, entrá a **Configuración → Cuentas → Enviar como** y agregá la casilla con los datos de salida de la tabla, para poder responder como `ventas@` o `administracion@`.
