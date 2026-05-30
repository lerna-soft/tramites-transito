# Trámites Tránsito

Asistente de **trámites de tránsito en Colombia** (Lerna Soft): qué hacer y en qué orden, generación de **impugnaciones** y **derechos de petición** para multas mal puestas o injustas, y un **consultor de normas para la vía** ("derechos en la vía") cuando un agente te dice algo que no es.

## Qué incluye
- **Wizard de trámites** (impugnar, pedir pruebas, prescripción, recurso) con cálculo de plazos (días hábiles, ventana de descuentos, prescripción, fotomulta).
- **Consultor de derechos en la vía** (`js/normas.js`): fichas buscables por palabra, sinónimos, número de artículo/ley y código de infracción (grabar, requisa, no retención de licencia/llaves, bajar del carro, interrogatorio, embriaguez, etc.).
- **Catálogo de códigos de infracción** (`js/codigos.js`, ~103 códigos).
- **Visores de los códigos** y **PDF oficial descargable**:
  - Tránsito — Ley 769/2002: `codigo/ley-769.html` · `codigo/ley-769.pdf`
  - Policía — Ley 1801/2016: `codigo/ley-1801.html` · `codigo/ley-1801.pdf`

## Estructura
- `index.html` — entrada (carga los JS).
- `js/` — `app.js`, `normas.js`, `codigos.js`, `rules.js`, `templates.js`, `tramites.js`, `organismos.js`, `holidays.js`.
- `css/styles.css` — estilos (móvil-first).
- `codigo/` — visores HTML y PDF de los códigos.

## Despliegue
Sitio estático (sin backend). También se sirve como mini-app dentro del sitio público en `https://lerna-soft.github.io/tramites-transito/`.

## Aviso
Herramienta informativa de apoyo ciudadano. No sustituye asesoría jurídica. Los textos normativos son de referencia; ante cualquier duda, consulta la fuente oficial.
