# 15. Google y aviso si el sitio se cae

[← Volver al índice](../README.md)

Tres cosas gratuitas que se hacen **una sola vez**, con tu propia cuenta de Google y de UptimeRobot. El sitio ya está preparado para todas.

## 1. Google Search Console: cómo te encuentran en Google

Muestra con qué búsquedas aparece el sitio, cuántas personas entran desde Google y si Google encuentra algún error.

1. Entrá a **[search.google.com/search-console](https://search.google.com/search-console)** con tu cuenta de Google.
2. **Agregar propiedad → Prefijo de URL**, y escribí `https://boggianofiambrerias.com.ar/`.
3. En los métodos de verificación elegí **Etiqueta HTML** y copiala. Es algo como `<meta name="google-site-verification" content="…">`.
4. En el panel del sitio, en **Datos del negocio → Verificación de Google Search Console**, pegá la etiqueta entera y tocá **Guardar**.
5. Volvé a Search Console y tocá **Verificar**.
6. Ya verificado, entrá a **Sitemaps**, escribí `sitemap.xml` y tocá **Enviar**. El mapa del sitio se arma solo con todas las páginas y categorías.

Los primeros datos aparecen en unos días.

## 2. Perfil de Empresa en Google (Google Maps)

Es la ficha que aparece en Google Maps y a la derecha de las búsquedas, con dirección, horarios, fotos y opiniones. **Para un comercio de barrio, es lo que más clientes trae.**

1. Entrá a **[business.google.com](https://business.google.com)** con tu cuenta de Google.
2. **Agregar empresa:** el nombre ("Boggiano Fiambrerías") y la categoría más parecida, por ejemplo Fiambrería o Delicatessen.
3. Cargá la **dirección** del local, el **teléfono**, los **horarios** y el sitio web: `https://boggianofiambrerias.com.ar`.
4. Google pide **verificar** que el local es tuyo: por video, por teléfono o con una carta. Seguí sus pasos.
5. **Una ficha por sucursal**, cada una con su dirección y sus horarios.
6. Subí fotos del local y de los productos. Las fichas con fotos reciben muchas más visitas.

> Tené los mismos datos en el Perfil de Empresa y en [Sucursales](06-sucursales.md) del panel. Google confía más en un negocio cuando la dirección y los horarios coinciden en todos lados.

## 3. Aviso si el sitio se cae (UptimeRobot)

Un servicio gratuito que revisa el sitio cada 5 minutos y te manda un mail si deja de responder.

1. Creá una cuenta gratis en **[uptimerobot.com](https://uptimerobot.com)**.
2. Tocá **Add New Monitor** y completá:
   - **Monitor Type:** `HTTP(s)`
   - **URL:** `https://boggianofiambrerias.com.ar`
   - **Monitoring Interval:** 5 minutos
3. En **Alert Contacts**, tildá tu mail y guardá.

Si te llega un aviso, mirá primero si el sitio abre desde el celular con los datos, sin wifi. Si no abre, revisá en hPanel si hay algún aviso de Hostinger, o escribile a su soporte (24/7).
