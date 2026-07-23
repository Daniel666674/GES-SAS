# GES SST — Maqueta de rediseño (riesgoslaborales.com.co)

Maqueta de propuesta de **3 secciones** para la reconstrucción del sitio de
**Gestionamos Soluciones SST SAS**, orientada a convertir tráfico frío en
pipeline. Un solo archivo autocontenido: [`index.html`](./index.html)
(fuentes incrustadas, sin dependencias externas).

## Las 3 secciones = el funnel de la propuesta

| # | Sección | Nivel del funnel | Qué hace |
|---|---------|------------------|----------|
| 1 | **Hero + Test de cumplimiento** | Frío | Gatillo emocional (multa hasta 1.000 SMLMV) + widget interactivo "Índice de cumplimiento SG-SST" que diagnostica y captura al visitante que aún no decide. |
| 2 | **Funnel + Servicios + FAQ** | Tibio | Ruta de 3 momentos (frío/tibio/caliente), servicios con keywords, y FAQ de normatividad (Decreto 1072, Res. 0312, psicosocial, PESV). |
| 3 | **Prueba social + Conversión** | Caliente | 20 años de trayectoria, métricas, testimonios y CTA final + lead magnet descargable. |

## SEO — estructura maximizada

- `<title>`, meta description y keywords ricos en intención de búsqueda.
- `lang="es-CO"`, canonical y `hreflang` sobre el dominio antiguo con autoridad.
- HTML semántico con jerarquía correcta `h1 → h2 → h3` y `aria-label`.
- Open Graph + Twitter Card para compartir en redes.
- **3 bloques JSON-LD schema.org**: `ProfessionalService`, `FAQPage`, `ItemList` de servicios.

## GEO — optimización para motores de respuesta con IA

- Bloque FAQ con preguntas y respuestas directas y citables sobre la
  normatividad SG-SST colombiana, marcado con `FAQPage` para que buscadores
  y asistentes de IA lo extraigan como respuesta.
- Entidades claras (Decreto 1072, Resolución 0312, SMLMV, PESV) y datos
  estructurados de la organización que refuerzan su identidad ante los LLM.

## Gatillos emocionales

- Titular de riesgo/alivio en lugar de un genérico "bienvenidos".
- Diagnóstico interactivo que hace visible el riesgo propio del visitante.
- Prueba social de 20 años, métricas y testimonios ilustrativos.

## Notas

- Diseño responsive y con soporte de tema claro/oscuro.
- Testimonios y métricas son **ilustrativos**: se reemplazan por datos
  reales verificados antes de producción.
