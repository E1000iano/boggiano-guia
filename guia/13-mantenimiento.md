# 13. Mantenimiento y respaldos

[← Volver al índice](../README.md)

## Respaldos

- **Catálogo:** de vez en cuando, en **Importar / Exportar → Exportar productos**. Es tu copia en Excel de todos los productos.
- **Del hosting:** Hostinger hace una copia **semanal** del sitio y de la base de datos. Está en **hPanel → Archivos → Copias de seguridad**.
- **Fotos originales:** guardalas en tu computadora o en Drive. El sitio guarda una versión achicada.
- **Logo oficial:** los archivos de diseño (AI, EPS, PDF, PNG) los conservás aparte. Son los que se usan para imprimir.

## Qué no tocar en el hosting

El sitio vive en el hosting en dos carpetas. Desde el panel del sitio no hace falta entrar a ninguna.

| Carpeta | Qué es | Regla |
|---|---|---|
| `public_html/` | El sitio | No borres ni muevas archivos. **`public_html/uploads/`** tiene las fotos que subiste desde el panel |
| `privado/` | La configuración con las contraseñas, los CV y la papelera de fotos borradas (se vacía sola al año) | **Nunca la muevas adentro de `public_html`** ni la compartas. Tiene la contraseña de la base de datos y la del correo |

- **No instales** WordPress, el "Creador con IA" ni ninguna plantilla de Hostinger sobre `boggianofiambrerias.com.ar`: pisarían el sitio.
- **Versión de PHP:** el sitio usa **PHP 8.3**. Si Hostinger avisa que hay que actualizarla, conviene probar antes.
- **La contraseña de `ventas@`:** si la cambiás, actualizala también en `privado/config.php` ([Correo](12-correo.md)).

## Cada tanto

- **Postulaciones:** borrá las que ya no necesites (Ley 25.326).
- **Fotos:** revisá en el panel los productos **sin foto** y ocultá los que ya no vendés.
- **Búsquedas laborales:** cerrá las que ya cubriste.
- **Horarios:** el cartel "Abierto ahora" **no sabe de feriados**. Para un feriado o una fecha especial, cambiá ese día en el **horario por día** de [Sucursales](06-sucursales.md) (dejalo vacío si cierran) y volvé a ponerlo después. Si hace falta avisarlo, sumalo al texto de la portada desde [Textos](10-textos-e-imagenes.md).

## Vencimientos

- **Hosting:** el plan está pagado por 48 meses. Al renovar, el precio puede subir.
- **Dominio `.com.ar`:** se renueva en **nic.ar**, con la clave fiscal. Si vence, el sitio y el correo dejan de andar.
- **Correo:** las casillas gratis del plan duran el primer año ([Correo](12-correo.md)).
