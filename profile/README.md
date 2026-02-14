# haletheia - Honest AI Ecosystem

<div align="center">

```
  ╦ ╦  ╔═╗  ╦    ╔═╗  ╔╦╗  ╦ ╦  ╔═╗  ╦  ╔═╗
  ╠═╣  ╠═╣  ║    ║╣    ║   ╠═╣  ║╣   ║  ╠═╣
  ╩ ╩  ╩ ╩  ╩═╝  ╚═╝   ╩   ╩ ╩  ╚═╝  ╩  ╩ ╩
  ———————————————————————————————————————————
  ἀλήθεια (alḗtheia) · "Desvelamiento de la verdad"
```

**El humano es el cerebro. Los LLMs son herramientas. Construimos la infraestructura para usarlas con conciencia.**

</div>

---

## Qué es Haletheia

Llevamos más de 2 años construyendo algo que empezó como herramientas y se convirtió en una tesis.

La tesis: **la IA actual oculta demasiado**. Oculta sus errores (alucinaciones), oculta cómo piensa (black box), oculta qué no sabe (no detecta gaps), oculta tus datos (cloud obligatorio), oculta tu cultura (modelo único para todos).

Haletheia es un ecosistema de proyectos que hace lo contrario: **desoculta**. Y lo hemos materializado en código funcional, no en un paper.

**No construimos LLMs. Construimos la infraestructura para que los humanos usen IA de forma consciente, ética y sostenible.**

| Lo que NO construimos | Lo que SÍ construimos |
|---|---|
| LLMs (los modelos ya existen) | **Memoria coherente** — más allá de context window |
| Servicios cloud (ya existen) | **Orquestación resiliente** — circuit breakers, no chains frágiles |
| Sustitutos del humano | **Trazabilidad completa** — debugging posible, no black box |
| | **Ética ingenierizada** — pre-validación, no filtros opacos post-hoc |
| | **Protocolo de contexto** — sostenible a largo plazo |
| | **Ecosistema local-first** — tus datos son tuyos |

---

## Proyectos del Ecosistema

**15 repositorios** organizados en 3 capas.

### Núcleo cognitivo

Librerías y frameworks que forman el stack de inteligencia. Todos se integran en o giran alrededor de **LiiaDA**.

<table>
<tr>
<td width="50%">

#### [LiiaDA](https://github.com/haletheia/liiada)
**Orquestador central — el esqueleto del ecosistema**

Router multi-LLM, RAG multi-dominio, puente a todos los módulos. No es un LLM: es la infraestructura que los orquesta.

`Python` · `FastAPI` · `ChromaDB` · `Ollama`

</td>
<td width="50%">

#### [GAIA](https://github.com/haletheia/gaia)
**Arquitectura cognitiva — 6 capas de validación**

Entropía (Shannon), Narrativa (Bruner), Recursión (Hofstadter), Verificación, Eficiencia, Identidad (z_core). Anti-alucinación por diseño.

`Python` · `NumPy` · `SciPy` · 50+ tests

</td>
</tr>
<tr>
<td width="50%">

#### [Halexandria](https://github.com/haletheia/halexandria)
**Motor de conocimiento cognitivo**

Búsqueda vectorial (ChromaDB) + grafo de conocimiento (NetworkX) + trazas de razonamiento + detección de gaps + drift tracking. Local-first, aislamiento per-agente.

`Python` · `ChromaDB` · `NetworkX` · 66 tests

</td>
<td width="50%">

#### [Ethilia](https://github.com/haletheia/ethilia)
**Gobernanza ética pre-validada**

Validators configurables (YAML), detección de bias (8 categorías), sensibilidad cultural. Pre-validación, no filtros post-hoc.

`Python` · `Pydantic` · `YAML`

</td>
</tr>
<tr>
<td width="50%">

#### [HCP Memory Engine](https://github.com/haletheia/hcp-mem-engine)
**Memoria multi-escala (CIPP)**

Fast/Mid/Slow con consolidación tipo sueño (NREM/REM). EWC + GEM para evitar olvido catastrófico. Científicamente fundado.

`Python` · `NumPy` · ~50 tests

</td>
<td width="50%">

#### [Micra](https://github.com/haletheia/micra)
**Framework de deep learning desde cero en Rust**

10 crates: autograd escalar → tensores ND → capas NN → transformer GPT → runtime CPU/GPU → kernels CUDA propios. Progresión pedagógica con 440+ tests. Se integra con LiiaDA vía PyO3 como LLM provider local.

`Rust` · `CUDA/C++` · `PyO3` · 440+ tests

</td>
</tr>
<tr>
<td width="50%">

#### [HCP Observatory](https://github.com/haletheia/hcp-observatory)
**Observabilidad para servicios IA**

Logging estructurado (structlog), métricas HTTP, tracking de tokens, <5ms overhead. Observable Reasoning: traza completa de decisiones.

`Python` · `FastAPI` · `structlog` · 253 tests

</td>
<td width="50%">

#### [UnderCtrl](https://github.com/haletheia/underctrl)
**Patrones de resiliencia**

Circuit breaker, retry exponencial, timeouts, fallback, pipelines resilientes. Production-ready.

`Python` · `Pydantic` · 42 tests

</td>
</tr>
</table>

---

### Productos

Aplicaciones de usuario construidas sobre el núcleo.

<table>
<tr>
<td width="50%">

#### [MEIA](https://github.com/haletheia/meia)
**Manifiesto Ético de la IA — Libro-Web-Foro**

PDF descargable (129 documentos) + web Astro (50+ casos éticos con contenido completo) + foro de discusión por caso ético. Backend Go con API REST + SQLite. Docker orchestration.

`Astro` · `Go` · `Docker` · `SQLite`

</td>
<td width="50%">

#### [Waito Back](https://github.com/haletheia/waito-back)
**Backend del IDE nativo**

LSP, Git, terminal, sistema de archivos, servicios IA, resolución visual de conflictos. 11 crates Rust. Privacy-first.

`Rust` · 11 crates · `LSP`

</td>
</tr>
<tr>
<td width="50%">

#### [Waito Front](https://github.com/haletheia/waito-front)
**Frontend del IDE nativo**

UI reactiva con FAARA (framework propio), 50+ componentes, rendering egui, GUI-agnóstico.

`Rust` · `egui` · `FAARA` · `Tauri`

</td>
<td width="50%">

#### [AIR Platform](https://github.com/haletheia/ai-package-registry)
**Registry de agentes — "npm para IA"**

Búsqueda avanzada, integraciones GitHub/HuggingFace/PyPI/npm. CLI + API REST + Web UI. Usa Halexandria como backend de conocimiento.

`Python` · `FastAPI` · `Angular`

</td>
</tr>
<tr>
<td width="50%">

#### [Hyddren Assistant](https://github.com/haletheia/hyddren-assistant)
**Asistente de voz 100% offline**

STT (Vosk), TTS nativo, LiiaDA como backend, 8 skills modulares (sistema, archivos, procesos, paquetes, red). Sin cloud, sin telemetría.

`Rust` · `Tokio` · `Vosk` · 96 tests

</td>
<td width="50%">

#### [LiiaDA MCP](https://github.com/haletheia/liiada-mcp)
**Servidor Model Context Protocol**

Expone herramientas de LiiaDA via MCP: análisis de código (estructura, smells, dependencias), búsqueda de docs, búsqueda de paquetes. Compatible con Claude Desktop y Cursor.

`Python` · `FastMCP` · `MCP SDK`

</td>
</tr>
</table>

---

### Protocolo

<table>
<tr>
<td>

#### [Human-Code-AI Protocol](https://github.com/haletheia/human-code-ai-protocol)
**Protocolo de colaboración humano-IA — como Git, pero para el contexto**

Workflow RPI+ (Research → Plan → Implement → Verify → Compact), roles modulares, vibes, contexto persistente (`.procontext/`). Validado 7 meses en producción. Agnóstico de herramienta.

`Markdown` · `YAML` · agnóstico de lenguaje

</td>
</tr>
</table>

---

## Cómo encaja todo

```
                        ┌──────────────────┐
                        │   TÚ (el humano) │
                        └────────┬─────────┘
                                 │ decide, valida, aprende
                                 ▼
                    ┌────────────────────────┐
                    │     HCP Protocol       │  contexto persistente
                    └────────────┬───────────┘
                                 │
                                 ▼
    ┌──────────────────────────────────────────────────────────┐
    │                    LiiaDA (orquestador)                   │
    │                                                          │
    │  ├── GAIA            (validación cognitiva)              │
    │  ├── Halexandria     (conocimiento + grafos)             │
    │  ├── Ethilia         (gobernanza ética)                  │
    │  ├── HCP Memory      (memoria multi-escala)              │
    │  ├── Observatory     (observabilidad)                    │
    │  ├── UnderCtrl       (resiliencia)                       │
    │  └── Micra           (LLM provider local vía PyO3)      │
    └──────────────────┬───────────────────────────────────────┘
                       │
        ┌──────────────┼──────────────┬──────────────┐
        ▼              ▼              ▼              ▼
   ┌─────────┐  ┌───────────┐  ┌──────────┐  ┌──────────┐
   │   AIR   │  │  Waito    │  │ Hyddren  │  │   MEIA   │
   │Platform │  │  (IDE)    │  │  (voz)   │  │(libro-   │
   │(agentes)│  │front+back │  │ offline  │  │ web-foro)│
   └─────────┘  └───────────┘  └──────────┘  └──────────┘
```

---

## Ingeniería de conceptos abstractos

Lo que diferencia a Haletheia: tomar conceptos abstractos — filosóficos, psicológicos, físicos — e **ingenierizarlos** en código de producción.

| Concepto abstracto | Problema de software | Nuestra ingeniería |
|---|---|---|
| **Entropía de Shannon** | "¿Está seguro el modelo?" | Entropy Layer: si entropía > threshold → suspender juicio |
| **Epoché de Husserl** | LLM inventa con confianza | GAIA Identity: si conflicto ontológico → "No sé" |
| **Memoria episódica de Tulving** | Context window = límite duro | HCP Memory: Fast/Mid/Slow + consolidación tipo sueño |
| **Narrativa coherente de Bruner** | Respuestas contradictorias | Narrative Layer: valida consistencia vs historial |
| **Circuit breaker** | Cascade failures en agents | UnderCtrl: detecta fallos, aísla, retry exponencial |
| **Sleep cycles** | Olvido catastrófico | CIPP Consolidation: EWC + GEM + simulación NREM/REM |
| **Arco de compresión de Karpathy** | LLMs como caja negra | Micra: 10 crates que reconstruyen el stack desde autograd |

---

## Capas de valor

```
    ┌─────────────────────────────────────────────┐
    │    Capa 4: Consulting / Formación           │
    │  ┌───────────────────────────────────────┐  │
    │  │    Capa 3: LiiaDA (core — nunca se    │  │
    │  │            expone directamente)       │  │
    │  │  ┌─────────────────────────────────┐  │  │
    │  │  │  Capa 2: Plataformas            │  │  │
    │  │  │  MEIA · Waito · AIR · Hyddren   │  │  │
    │  │  │  ┌───────────────────────────┐  │  │  │
    │  │  │  │ Capa 1: Librerías PyPI    │  │  │  │
    │  │  │  │ GAIA · Halexandria ·      │  │  │  │
    │  │  │  │ Ethilia · UnderCtrl ·     │  │  │  │
    │  │  │  │ HCP Memory · Observatory  │  │  │  │
    │  │  │  │  ┌─────────────────────┐  │  │  │  │
    │  │  │  │  │ Capa 0: Filosofía   │  │  │  │  │
    │  │  │  │  │ HCP · MEIA · Micra  │  │  │  │  │
    │  │  │  │  └─────────────────────┘  │  │  │  │
    │  │  │  └───────────────────────────┘  │  │  │
    │  │  └─────────────────────────────────┘  │  │
    │  └───────────────────────────────────────┘  │
    └─────────────────────────────────────────────┘
```

Cada capa genera valor independiente. El core nunca se expone directamente — se monetiza a través de las capas exteriores. Las librerías funcionan solas (sin LiiaDA). Las plataformas las combinan en productos.

---

## Stack tecnológico

| Tecnología | Dónde | Para qué |
|---|---|---|
| **Python** | LiiaDA, GAIA, Halexandria, Ethilia, UnderCtrl, Observatory, HCP Memory, AIR, MCP | Core IA, frameworks, APIs |
| **Rust** | Waito (front+back), Hyddren, Micra | Rendimiento, productos nativos, seguridad de memoria |
| **Go** | MEIA (backend) | API REST ligera, binario único |
| **Astro** | MEIA (frontend) | SSG, Content Collections, SEO |
| **CUDA/C++** | Micra (kernels GPU) | Kernels propios vía FFI |

---

## Patrones que atraviesan el ecosistema

**Local-first**: todos los productos priorizan ejecución local sin cloud obligatorio (LiiaDA + Ollama, Hyddren + Vosk, Micra GPU local, MEIA + SQLite).

**Composición modular**: cada proyecto funciona solo y se ensambla con otros (GAIA + Halexandria + Ethilia → LiiaDA → Waito / AIR / Hyddren).

**Ética como principio de diseño**: no es un add-on. Ethilia pre-valida. MEIA cuestiona. HCP traza. GAIA verifica.

**Rust + Python como binomio**: Python para IA y agentes. Rust para rendimiento y productos nativos. Puente vía PyO3 (Micra → LiiaDA) y HTTP (LiiaDA → Waito).

---

## En números

```
15 repositorios en la organización
~140,000 líneas de código
~1,600 tests automatizados
5 lenguajes (Python, Rust, Go, TypeScript/Astro, CUDA)
3+ años de desarrollo (2023–2026)
0 modelos entrenados desde cero
0% de telemetría
100% open source (MIT)
```

---

## Para quién es esto

**No es para ti si** buscas el LLM más grande, quieres competir en entrenar modelos, o prefieres automatización sin conciencia.

**Es para ti si** valoras amplificación sobre reemplazo, necesitas infraestructura ética alrededor de LLMs, te importa la privacidad real, y crees en usar IA con conciencia.

---

## Por qué "Haletheia"

**Aletheia** (ἀλήθεια) = "Desvelamiento de la verdad" (Heidegger). La verdad no es estática: es un proceso activo de revelación. En IA: no buscamos sistemas con todas las respuestas. Buscamos sistemas que desvelen honestamente lo que saben y admitan lo que no. La **H** inicial rinde homenaje a Heidegger y al apodo del creador de los proyectos de **Haletheia**, Hidden.

---

<div align="center">

**El humano es el cerebro. Los LLMs son herramientas. Construimos la infraestructura para usarlas con conciencia.**

[Explora los Proyectos](https://github.com/orgs/haletheia/repositories) · [HCP Protocol](https://github.com/haletheia/human-code-ai-protocol) · [MEIA](https://github.com/haletheia/meia)

*Infraestructura para usar IA con conciencia — Amplificación, no reemplazo*

</div>
