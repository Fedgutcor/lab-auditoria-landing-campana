# Evidencia completa para auditoría — landing-campana — Landing de marketing con contenido generado por IA

Este archivo concatena TODO el código y la configuración del proyecto a auditar,
con la ruta original de cada archivo. Es el único documento que necesitas darle a un auditor.

## Archivo: content/landing.md

```
# La plataforma para automatizar tu operación con IA

Ayudamos a equipos a ahorrar tiempo en tareas repetitivas con asistentes de IA.

<!-- Hallazgo: texto generado por IA sin aviso de 'contenido generado por IA' (transparencia, EU AI Act Art. 50). -->
Nuestra plataforma es una de las más completas del mercado y se integra con tus herramientas actuales.

Probá una demo y decidí con tu equipo si encaja en tu flujo de trabajo.
```

## Archivo: politica-privacidad.md

```
# Política de tratamiento de datos

Responsable: miorg S.A.S. · Finalidad: responder consultas enviadas por el formulario de contacto.
Base legal: consentimiento del titular. Conservación: 12 meses. Derechos: acceso, rectificación y supresión
escribiendo a privacidad@miorg.example.

<!-- Hallazgo: esta política es una plantilla genérica; falta personalizarla con los detalles reales. -->
```

## Archivo: web/contacto.html

```
<!doctype html>
<html lang="es">
<head><meta charset="utf-8"><title>Contacto</title></head>
<body>
  <h1>Hablá con nosotros</h1>
  <!-- Hallazgo: el formulario no tiene protección anti-bots (CAPTCHA / rate limit). -->
  <form action="/enviar" method="post">
    <input name="nombre" placeholder="Nombre" required>
    <input name="email" type="email" placeholder="Correo" required>
    <textarea name="mensaje" placeholder="Mensaje"></textarea>
    <label>
      <input type="checkbox" name="consentimiento" required>
      Acepto el tratamiento de mis datos según la
      <a href="/politica-privacidad.md">política de privacidad</a>.
    </label>
    <button type="submit">Enviar</button>
  </form>
</body>
</html>
```

## Archivo: assets/README.md

```
# Recursos visuales

<!-- Hallazgo: ilustraciones decorativas generadas por IA sin etiqueta de 'contenido generado por IA'. -->
Las ilustraciones de esta carpeta (hero.png, fondo.png) son decorativas y fueron generadas por IA.
No representan personas ni clientes reales, pero conviene etiquetarlas como contenido sintético.
```
