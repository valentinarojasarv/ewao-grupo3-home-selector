# EWAO · Home y selector de rutas (Grupo 3)

Prototipo académico del Grupo 3, Estrategia global e integración, para el proyecto UDD × EWAO con la Asociación Keweriono (pueblo Waorani, Ecuador). Curso Marketing Internacional, Universidad del Desarrollo, noviembre de 2026.

**Sitio publicado:** https://dry-thunder-cffa.valentinarojas-arv.workers.dev/

## Qué es

Una puerta de entrada común al ecosistema EWAO. El home pregunta "¿Cómo quieres conectar con EWAO?", deriva a cada persona al área correcta y deja su contacto en un solo CRM.

- Selector con siete intenciones: visitar, comprar, colaborar, empresa, universidad o investigación, financiar y conocer.
- Puntaje de afinidad sobre las 22 iniciativas del Plan de Vida Keweriono. Muestra hasta tres resultados. Una coincidencia no es una aprobación.
- Página marco: las landings de los Grupos 1, 6 y 8 se muestran sin modificar dentro de una barra de EWAO.
- Estado, avance y colaboración buscada de las 22 iniciativas, informados por EWAO el 16 de noviembre de 2026.
- Español e inglés.
- Aviso de cookies: la analítica se activa solo con consentimiento.

## Contenido del repositorio

| Ruta | Contenido |
|---|---|
| `index.html` | El prototipo completo en un solo archivo (HTML, CSS y JavaScript). |
| `docs/Documento_Respaldo_Grupo_3_-_Rojas_Sepulveda_Molina_Iglesias.pdf` | Documento marco de respaldo, con anexo de evidencia. |
| `docs/Documento_Respaldo_Grupo_3_-_Rojas_Sepulveda_Molina_Iglesias.docx` | El mismo documento en Word. |
| `docs/Presentacion_Grupo3.pdf` | Presentación del pitch final. |
| `docs/evidencia_evento_clave.pdf` | Captura de Google Analytics con form_submit marcado como evento clave. |

## Cómo usarlo

Abrir `index.html` en el navegador, o entrar al sitio publicado. No necesita instalación.

## Integraciones

- **HubSpot (plan gratuito).** El formulario "Solicitar información" envía el contacto con su ruta, puntaje e iniciativas sugeridas. Hay un correo de confirmación automático. El dominio del sitio publicado está registrado en HubSpot; si el archivo se abre desde otro dominio, HubSpot puede clasificar el envío como spam.
- **Google Tag Manager y Google Analytics 4.** Solo se cargan si la persona acepta el aviso de cookies. El home emite eventos al dataLayer: `page_view`, `quiz_start`, `quiz_step_complete`, `quiz_complete`, `project_recommendation_view`, `form_submit`, `outbound_landing_click` y `route_change_click`.

Los identificadores que aparecen en `index.html` (portal y formulario de HubSpot, contenedor de GTM) son públicos por diseño. El archivo no contiene contraseñas ni claves.

## Pendientes declarados

- EWAO debe confirmar el permiso de uso de la fotografía de portada.
- Falta que los Grupos 1, 6 y 8 confirmen que aceptan mostrar su landing dentro de EWAO.
- No hubo contacto con el Grupo 7. La integración con su CRM queda como siguiente paso.
- El titular "La mayor biodiversidad del planeta sigue viva" necesita fuente o una redacción más acotada antes de producción.
- Siguiente paso pedido por EWAO: ficha por iniciativa con próximos pasos y donaciones.

## Equipo

Francisca Sepúlveda, Antonia Iglesias, Isabel Molina y Valentina Rojas.

## Créditos

Fotografía de portada: EWAO Project (2026). Las landings integradas pertenecen a sus grupos: Pasaporte WEMA (G1), Open Collaboration (G6) y Sistema de Aliados (G8).

Este es un prototipo académico. No representa una oferta comercial ni una comunicación oficial de EWAO o de la Asociación Keweriono.
