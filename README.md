# landing-campana

> ⚠️ **REPOSITORIO DE EJEMPLO PARA AUDITORÍA — uso docente**
> Código de ejemplo con áreas de mejora plantadas a propósito para practicar auditoría asistida por IA.
> No es código de producción.

Landing de marketing de ejemplo, con textos e imágenes generados por IA.

## Diseño (lo que está BIEN hecho a propósito)

- El formulario pide **consentimiento explícito** y enlaza la política de privacidad.
- El texto no hace afirmaciones falsas ni antropomorfiza la IA.

## Cómo usar este repo en la clase

Es el repo de **menor riesgo**: no hay secretos, ni datos sin consentimiento, ni claims engañosos. Quedan solo **observaciones** de transparencia (etiquetar el contenido generado por IA) e higiene (anti-bot, política genérica). Audítalo: deberías llegar a **APTO CON OBSERVACIONES** — se puede publicar, con correcciones menores.

## Carpeta `copilot-studio/` — para la práctica en Microsoft Copilot Studio

La carpeta [`copilot-studio/`](copilot-studio/) contiene **copias de los archivos a auditar**, listas para subir a la base de conocimiento (Knowledge) de Copilot Studio.

Sube a Knowledge **todos los archivos de esa carpeta, tal cual** — y nada más. ¿Ruta aún más rápida? El archivo [`copilot-studio/evidencia-completa.md`](copilot-studio/evidencia-completa.md) concatena toda la evidencia en un solo documento: sube solo ese archivo, o copia su contenido y pégalo directamente en el chat del agente. En particular, **no subas este README**: contiene pistas sobre los hallazgos y el veredicto esperado, y sesgaría al auditor (no le des la hoja de respuestas).
