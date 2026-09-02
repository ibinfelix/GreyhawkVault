# Guía de Colaboración para IAs — Vault de Greyhawk (576 CY)

> Este archivo contiene las instrucciones operativas para cualquier agente de inteligencia artificial que colabore en el mantenimiento, expansión y corrección de esta bóveda de Obsidian. Léelo **completamente antes de hacer cualquier modificación.**

---

## 1. Contexto del Proyecto

Esta bóveda es un **compendio enciclopédico de referencia canónica** del mundo de **Greyhawk (Oerth)**, enfocado en el año canónico **576 CY (Common Year)**. No es una wiki de uso general ni una recopilación de wikis en línea: es un segundo cerebro de worldbuilding diseñado para uso en campañas de rol, con énfasis en:

- **Fidelidad al canon de Gary Gygax** (TSR, 1980-1983).
- **Consistencia interna** entre todas las notas de la bóveda.
- **Interconectividad relacional** mediante wikilinks de Obsidian.

El propietario es quien aprueba todo cambio significativo de contenido. No tomes decisiones editoriales de gran alcance sin consultar.

---

## 2. Fuentes de Información — Orden de Prioridad

> [!IMPORTANT]
> Siempre consulta las fuentes locales **antes** de recurrir a búsquedas en línea. Las fuentes en línea son complementarias y de respaldo, nunca primarias.

### 2.1 Fuentes Primarias (Máxima Autoridad)

Todos los archivos PDF de las fuentes fundacionales de Gary Gygax están disponibles **localmente** en el vault:

| Archivo | Ubicación | Contenido |
| :--- | :--- | :--- |
| `WorldofGreyhawk_I.pdf` | `World of Greyhawk by Gary Gygax/` | Gazetteer original (1980/1983): descripción de reinos, política, geografía, demografía y recursos. **Fuente #1.** |
| `WorldofGreyhawk_II.pdf` | `World of Greyhawk by Gary Gygax/` | Glossography (1983): tablas monetarias, heráldica, índice de coordenadas de ciudades, listas de gobernantes. **Fuente #1.** |
| `WorldofGreyhawk_III.pdf` | `World of Greyhawk by Gary Gygax/` | Suplemento adicional de Gygax con material de campaña y detalles expandidos. **Fuente #1.** |
| `Encyclopedia Greyhawkania Index.pdf` | `Resources/Sources/` | Índice enciclopédico completo de toda la obra de Greyhawk; útil para rastrear referencias cruzadas y ortografía canónica de nombres propios. |
| `World of Greyhawk Timeline.pdf` | `Resources/Sources/` | Cronología completa del Flanaess desde antes de la migración hasta 576 CY y más allá. |
| `the-hateful-wars.pdf` | `Resources/Sources/` | Módulo detallado sobre las Guerras Odiosas: historia de los elfos y humanoides del Pomarj, con implicaciones para Ulek y el sur. |
| `fuentes_links.md` | `Resources/Sources/` | Documento de referencia rápida con los links y páginas clave de las fuentes primarias. |

### 2.2 Fuentes Secundarias (Respaldo y Complemento)

Solo cuando la información no pueda encontrarse en las fuentes primarias locales:

- **Living Greyhawk Gazetteer (2000)**, Erik Mona et al. — útil para información expandida post-Gygax, pero verificar que no contradiga la era 576 CY.
- **The Adventure Begins (1998)** — útil para la Ciudad Libre de Greyhawk.
- **Módulos clásicos de TSR**: *T1-4 Temple of Elemental Evil*, *G1-3 Against the Giants*, *D1-3 Descent into the Depths*, *S1-4*.

### 2.3 Búsquedas en Línea y Sitios de Referencia

Usar cuando las fuentes locales sean insuficientes o se requiera contrastar detalles específicos. Sitios de referencia recomendados:
- [Greyhawk Online Wiki (Great Library of Greyhawk)](https://greyhawkonline.com) — Fuente enciclopédica altamente confiable, detallada y completa.
- [Canonfire!](https://www.canonfire.com) — Excelente repositorio de artículos de lore canónico y análisis geográfico/histórico.

> [!WARNING]
> **Precaución Temporal con Greyhawk Online y wikis externas:**
> Aunque [Greyhawk Online](https://greyhawkonline.com) es una fuente sumamente precisa y fidedigna, gran parte de sus artículos recopilan la historia completa del escenario, incluyendo los eventos posteriores a las **Guerras de Greyhawk (582–584 CY)**, *From the Ashes* (585 CY) y la era *Living Greyhawk* (591+ CY).
> 
> Al consultar estas fuentes, **debes filtrar rigurosamente la línea temporal**:
> - Verifica qué gobernantes, fronteras, alianzas y estados existían **exactamente en o antes de 576 CY**.
> - No asumas como presente el estado de reinos caídos, conquistados o transformados durante o después de las guerras (ej. invasiones de Iuz, caída de Geoff o las Tierras del Escudo, fractura de Aerdy posterior, etc.).
> - Siempre contrasta las fechas y nombres con las fuentes primarias locales (`World of Greyhawk by Gary Gygax`).

---

## 3. Reglas de Edición y Consistencia

### 3.1 No Usar Scripts de Lote

> [!CAUTION]
> **Prohibido usar scripts de Python u otras herramientas de generación masiva en lote.** Todas las modificaciones y creaciones de archivos deben hacerse **directamente** sobre los archivos individuales mediante las herramientas de edición disponibles (`replace_file_content`, `multi_replace_file_content`, `write_to_file`). Esto con motivo de que modificaciones en masa suelen ser peligrosas y ofrecen poco o nada de detalle enciclopédico. Solo pueden usarse en caso que el usuario especifique lo contrario y proporcione una justificación. 

### 3.2 Revisar el Contexto Antes de Editar

Antes de crear o modificar cualquier nota, realiza los siguientes pasos:

1. **Leer la nota existente completa** si ya existe.
2. **Revisar la nota del Hub correspondiente** (`00 Hubs & Overview/`) para entender cómo está indexada.
3. **Revisar notas de artículos vecinos** (reino vecino, ciudad hermana, personaje relacionado) para asegurar coherencia narrativa y terminológica.
4. **Revisar la plantilla correspondiente** en `Resources/Templates/` antes de crear un artículo nuevo.

### 3.3 Respetar el Año Canónico

Todo el contenido describe el estado del mundo en **576 CY**. No incorporar eventos posteriores (Guerras de Greyhawk, 585 CY, etc.) salvo que se mencionen como algo futuro o especulativo. El estado político de reinos, gobernantes y fronteras debe corresponder al Gazetteer de 1983.

### 3.4 Idioma

- El contenido narrativo de las notas se escribe en **español**.
- Los nombres propios de lugares, personajes y facciones se mantienen en su forma canónica en inglés entre paréntesis en el título y como alias: `Nombre en Español (English Name)`.
- Las citas y referencias a fuentes originales se incluyen en inglés.

---

## 4. Wikilinks — Reglas de Enlazado

### 4.1 Principio Fundamental

> [!IMPORTANT]
> **Cada entidad significativa mencionada debe enlazarse a su nota canónica** usando el nombre exacto del archivo de destino. Un artículo bien escrito conecta todo su contenido relevante al grafo de la bóveda.

### 4.2 Entidades que Siempre Deben Enlazarse

Cuando menciones cualquiera de estas entidades en el cuerpo de una nota, añade un wikilink:

| Tipo de Entidad | Ejemplo Correcto |
| :--- | :--- |
| **Reinos y Naciones** | `[[Gran Marcha (Gran March)]]` |
| **Ciudades y Asentamientos** | `[[Ciudad de Hookhill (Hookhill)]]` |
| **Personajes Notables** | `[[Mordenkainen]]`, `[[Rey Belvor IV (King Belvor IV of Furyondy)]]` |
| **Deidades** | `[[Heironeous (Dios de la Justicia y el Valor)]]` |
| **Facciones y Órdenes** | `[[Liga de Hierro (Iron League)]]`, `[[El Círculo de los Ocho (Circle of Eight)]]` |
| **Ríos, Mares, Montañas, Bosques** | `[[Río Sheldomar (Sheldomar River)]]`, `[[Montañas Lortmil (Lortmil Mountains)]]` |
| **Culturas y Razas** | `[[Humanos Oeridios (Oeridians)]]`, `[[Elfos del Flanaess (Elves)]]` |
| **Eventos Históricos** | `[[Las Guerras Gemelas]]`, `[[La Guerra Corta (438 CY)]]` |
| **Planos y Cosmología** | `[[Monte Celestia (Mount Celestia - Los Siete Cielos)]]` |

### 4.3 Sintaxis Correcta de Wikilinks

```markdown
# Enlace simple (cuando el nombre del archivo = texto deseado)
[[Gran Marcha (Gran March)]]

# Enlace con texto alternativo (cuando el texto a mostrar difiere del nombre del archivo)
[[Gran Marcha (Gran March)|Gran Marcha]]
[[Caballeros de la Atalaya (Knights of the Watch)|Caballeros de la Guardia]]

# Nunca usar nombres que NO coincidan con el archivo real
# INCORRECTO: [[Knights of the Watch]]   ← no existe ese archivo
# CORRECTO:   [[Caballeros de la Atalaya (Knights of the Watch)]]
```

### 4.4 Verificar Que el Archivo de Destino Existe

Antes de crear un wikilink, verifica que el archivo de destino existe en la bóveda. Si no existe, tienes dos opciones:
- **Crear el archivo** si el tema justifica un artículo propio.
- **Mencionar en prosa** sin crear un wikilink roto.

> Un wikilink roto es peor que no tener enlace.

---

## 5. Estructura de Carpetas del Vault

```
Greyhawk/
├── 00 Hubs & Overview/     → Portales temáticos de acceso rápido (8 hubs)
├── 01 Atlas/               → Accidentes geográficos: ríos, montes, bosques, dungeons
├── 02 Realms/              → Reinos, estados y naciones soberanas del Flanaess
├── 03 Dramatis Personae/   → Personajes notables: archimagos, monarcas, villanos
├── 04 History & Timeline/  → Eventos históricos y cronología del Flanaess
├── 05 Peoples & Cultures/  → Etnias, razas, idiomas y culturas
├── 06 Religion & Cosmology/→ Deidades, cosmología, planos exteriores (Gran Rueda)
├── 07 Systems & Middle Layers/ → Facciones, órdenes, gremios, casas nobles
├── 08 Cities & Settlements/→ Ciudades, puertos, fortalezas y aldeas
├── 09 Maps/                → Notas con mapas interactivos (plugin Leaflet)
├── Resources/
│   ├── Img/                → Imágenes de personajes, ciudades, eventos
│   ├── Shields/            → Escudos heráldicos de reinos y facciones
│   ├── Sources/            → PDFs de fuentes secundarias y enciclopedias
│   ├── Templates/          → Plantillas para nuevos artículos
│   └── flanaeass.png       → Mapa base del Flanaess para el plugin Leaflet
├── World of Greyhawk by Gary Gygax/  → PDFs de las fuentes primarias (Vols. I, II, III)
└── Home.md                 → Página de inicio de la bóveda
```

---

## 6. Plantillas Disponibles

Antes de crear cualquier artículo nuevo, revisa la plantilla correspondiente en `Resources/Templates/`:

| Plantilla | Cuándo Usarla |
| :--- | :--- |
| `Template - Reino o Nación.md` | Estado soberano: monarquía, teocracia, república, confederación |
| `Template - Ciudad o Asentamiento.md` | Ciudad, puerto, fortaleza, aldea, bastión fronterizo |
| `Template - Personaje (NPC).md` | Monarca, archimago, villano, héroe o figura histórica notable |
| `Template - Deidad.md` | Gran deidad, deidad menor, semidios del panteón de Greyhawk |
| `Template - Pueblo o Cultura.md` | Etnia humana, raza demi-humana, raza humanoide, idioma |
| `Template - Accidente Geográfico.md` | Cordillera, bosque, río, mar, lago, marisma, dungeon, ruinas |
| `Template - Facción u Organización.md` | Liga, gremio, orden de caballería, culto, hermandad, consejo |
| `Template - Evento Histórico.md` | Guerra, tratado, catástrofe, fundación, golpe de estado |
| `Template - Mapa.md` | Notas con visor Leaflet de cartografía interactiva |

---

## 7. Formato del Frontmatter YAML

Toda nota debe comenzar con un bloque YAML que incluya al menos:

```yaml
---
tags:
  - greyhawk/[tipo]          # realm, city, npc, religion, culture, geography, etc.
  - greyhawk/[subtag]        # región, etnia, orden, etc.
aliases:
  - "Nombre en Español"
  - "English Name"
  - "Nombre en Español (English Name)"
type: [tipo]                 # realm, settlement, character, deity, culture, plane, etc.
region: "Región geográfica o política"
status_576CY: "Descripción del estado en el año canónico 576 CY."
sources:
  - "[[WorldofGreyhawk_I.pdf#page=N|World of Greyhawk Vol. I, p. N]]"
---
```

> Los aliases son críticos: permiten que los wikilinks con texto alternativo resuelvan correctamente en el grafo de Obsidian.

---

## 8. Sección de Navegación

Toda nota debe terminar con una sección de navegación que enlace a los hubs relevantes:

```markdown
#### Navegación
- [[Reinos y Naciones del Flanaess (Realms)|⬅ Directorio de Reinos del Flanaess]]
- [[Historia y Cronologia del Flanaess (History)|⬅ Historia del Flanaess]]
- [[Ciudades y Asentamientos del Flanaess (Cities)|⬅ Ciudades del Flanaess]]
- [[Geografia y Atlas del Flanaess (Atlas)|⬅ Atlas del Flanaess]]
```

Adapta los hubs según el tipo de nota (no todas las notas necesitan los cuatro).

---

## 9. El Archivo `broken links output.md`

> [!WARNING]
> El archivo `broken links output.md` en la raíz del vault es un **reporte automático generado por Obsidian**. **No editar, no borrar, no reescribir su contenido.** Es una herramienta de diagnóstico que el propietario gestiona directamente para identificar qué wikilinks necesitan corrección.

Cuando el propietario comparte su contenido, úsalo como lista de tareas de reparación de enlaces, pero **no lo modifiques**.

---

## 10. Buenas Prácticas de Redacción

1. **Profundidad narrativa**: Las notas ricas son preferibles a las notas esqueléticas. Una nota de reino debe tener política interior, geografía, ejército, historia y ciudades. Una nota de ciudad debe tener gobernante, importancia estratégica, puntos de interés y política feudal local.
2. **Contexto cruzado**: Al escribir sobre un reino, menciona y enlaza sus ciudades. Al escribir sobre una ciudad, menciona y enlaza su reino, sus vecinos y su geografía cercana.
3. **Coherencia terminológica**: Usa los mismos nombres y títulos que usan otras notas del vault para la misma entidad. Revisa las notas vecinas antes de escribir.
4. **Citas al pie**: Cada nota debe incluir una sección `### Appendix & Citations` con las referencias a las fuentes primarias concretas (número de página del PDF).
5. **No inventar**: Si la información no existe en las fuentes primarias ni secundarias, señalarlo como especulativo o no añadirlo. Preferir la omisión honesta a la fabricación.
6. **Imágenes y escudos**: Si existe un archivo en `Resources/Shields/` o `Resources/Img/` con el nombre del artículo, inclúyelo con `![[NombreArchivo.png]]` o con la ruta absoluta `![Alt Text](file:///ruta)`.

---

*Última actualización: Septiembre 2026. Propietario: chabo.*
