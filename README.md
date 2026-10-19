# Skills Octubre

Inventario y guía de uso de las Skills personales instaladas de Michael Cruz.

**Corte:** 3 de octubre de 2026, hora de Nueva York. **34 paquetes respaldados, 33 nombres únicos.** Estado verificado contra el checkout de Skills personales y sus rutas remotas; la lista visible del chat puede estar desactualizada.

## Consultar y usar

1. Abre el [catálogo](CATALOGO.md) y elige por resultado buscado.
2. En ChatGPT selecciona la Skill con @, o indícala por nombre.
3. Proporciona objetivo, ubicación/periodo cuando corresponda, documentos y datos disponibles.
4. Indica modo, formato, destinatario y restricciones. Sustituye los campos entre corchetes de los ejemplos.
5. Revisa fuentes, cálculos, supuestos y pendientes. Distingue borrador de ejecución externa.

Cada ficha dentro de GUIA_DE_USO.md explica cuándo usar la Skill, qué darle, un prompt adaptable, qué entrega, cómo evaluar el resultado y sus límites.

## Contenido

- [Catálogo de las 33 capacidades por nombre](CATALOGO.md).
- [Guía completa de uso](GUIA_DE_USO.md).
- [Inventario verificable](inventory.json): IDs, nombres, descripción, modos y hash del controlador.
- [Respaldo de los 34 paquetes](Skills-Octubre.zip): controladores, referencias, scripts y assets propios de cada paquete.

Las copias de `skills/` dentro del ZIP son un respaldo. Estar en GitHub no instala automáticamente una Skill en ChatGPT. Los métodos internos de paquetes consolidados se conservan; no se presentan como nuevas instalaciones independientes.

El ZIP también conserva las 33 fichas individuales y la estructura completa de carpetas. Los documentos Markdown de este repositorio permiten consultar la guía sin descargar el respaldo.

## Estado de la limpieza

El inventario conserva lo realmente instalado, aunque figure como candidato a desinstalar:

- **Antigravity Orchestrator v2:** dos copias activas con el mismo nombre.
- **Real Estate Listing Copy:** versión anterior; preferir Listing Intelligence Launch System.
- **Neighborhood Analysis:** versión anterior; preferir Community Intelligence.


## Rutas de trabajo recomendadas

| Objetivo | Ruta |
|---|---|
| Evaluar una compra/inversión | Strategy Orchestrator → Analyze/Comps/CMA → Invest/Buyer Strategy/DSCR → Community según la decisión |
| Priorizar propietarios | Seller Opportunity Intelligence → CMA cuando haya comparables → Script Engine para borradores |
| Lanzar un listing | Listing Intelligence Launch System → Content Engine/Meta Housing según canal → Funnel/Landing/ManyChat según implementación |

No es obligatorio ejecutar toda una ruta: usa el mínimo método que resuelva el pedido y reutiliza datos ya verificados.

## Alcance de verificación

Se verificaron instalación, existencia de paquetes, correspondencia de nombres y respaldo de archivos. Las guías describen funciones declaradas en los controladores actuales. No certifican que todas las integraciones estén configuradas ni que cada modo haya sido probado en producción. Una Skill no aporta credenciales, APIs o autorización por sí sola. La presencia de datos históricos en referencias no los convierte en información vigente.

Los KPIs se interpretan con periodo y denominador. No se fijan metas comerciales, presupuestos o resultados sin datos y autorización pertinentes. No se incluyen paquetes desinstalados como entradas del catálogo.

## Organización de repositorios

Separación de paquetes realizada el 19 de octubre de 2026. Los paquetes personales trasladados se consultan en [Michael-Personal-Skills](https://github.com/mikopr32/Michael-Personal-Skills). La fecha de corte anterior describe el respaldo original; esta organización no desinstala skills de ChatGPT.
