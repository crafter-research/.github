### Crafter Research

Tecnología cívica, gov-tech y evaluación de LLMs open-source para LATAM. Un laboratorio donde cada paper tiene un prototipo funcional.

#### Datos públicos e índices

| Proyecto | Descripción | Estado |
|----------|-------------|--------|
| [muniscan](https://github.com/crafter-research/muniscan) | Índice automático y censal de la superficie digital que declaran las 1,794 municipalidades del Perú en gob.pe | Live |
| [sismo-abierto](https://github.com/crafter-research/sismo-abierto) | Sismos oficiales de Perú y Colombia con datos trazables del IGP y el SGC: mapas, catálogos, API, CLI, ondas, volcanes y salud de fuentes | Live |
| [static-index-poc](https://github.com/crafter-research/static-index-poc) | Índices binarios de solo lectura servidos como archivos inmutables. Mide disponibilidad de fuentes oficiales contra copias estáticas | PoC |
| [legalize-pe](https://github.com/crafter-research/legalize-pe) | Corpus peruano para la federación legalize.dev: 21,244 normas en Markdown, versionadas en Git, tier nacional del SPIJ más 26 jurisdicciones regionales | Live |

#### Civic Tech — Elecciones Perú 2026

| Proyecto | Descripción | Estado |
|----------|-------------|--------|
| [candidatos](https://candidatos.crafter.ing) | Explorador de candidatos para Elecciones Generales Perú 2026 — cruza datos JNE + peru-financia + political-graph | Live |
| [peru-financia](https://peru-financia.crafter.ing) | Mapa de financiamiento político peruano — datos ONPE 1995-2026 | Live |
| [political-graph](https://political-graph.crafter.ing) | Grafo interactivo de relaciones entre políticos y casos de corrupción | Live |
| [onpe-cli](https://github.com/crafter-research/onpe-cli) | CLI agent-first para la API de resultados electorales ONPE — consulta mesas, actas, ubigeos | Live |
| actas-peru-2026 | Radiografía estadística de 88K+ actas electorales — 8 tests forenses, mapa interactivo, verificación de claims | Privado |
| [timeline-peru](https://github.com/crafter-research/timeline-peru) | Línea de tiempo pública de la historia peruana | WIP |

#### Andenar — Plataforma de compliance gov LATAM

[Andenar](https://andenar.crafter.ing) orquesta adapters CLI agent-first por cada entidad gubernamental. Un adapter por portal. Todos convergen en un dashboard unificado. El producto está en línea; su código es privado.

| Adapter | Entidad | Caso | Estado |
|---------|---------|------|--------|
| [sunat-cli](https://github.com/crafter-research/sunat-cli) | SUNAT | RHE, F616, RUC, deuda tributaria | `npm`, live |
| [bcrp-cli](https://github.com/crafter-research/bcrp-cli) | BCRP | Tipo de cambio, inflación, series macro oficiales | `beta`, listo |
| [jne-cli](https://github.com/crafter-research/jne-cli) | JNE | Candidatos, expedientes, autoridades electorales | `dogfood` |
| [osce-seace-cli](https://github.com/crafter-research/osce-seace-cli) | OSCE/SEACE | Sanciones, proveedores, datos abiertos | `dogfood` |
| [sunarp-cli](https://github.com/crafter-research/sunarp-cli) | SUNARP | KYB registral, vehicular, partidas | `recon`, captcha |
| [sunedu-cli](https://github.com/crafter-research/sunedu-cli) | SUNEDU | Verificación grados y títulos | `recon`, Turnstile |
| [mtc-sutran-cli](https://github.com/crafter-research/mtc-sutran-cli) | MTC/SUTRAN | Licencias, papeletas, infracciones | `recon` |

**Estados**: `npm` publicado · `beta` listo para primer release · `dogfood` funciona con real data, faltan endpoints · `recon` bloqueos de captcha/Turnstile documentados.

Salvo `sunat-cli`, los adapters no reciben commits desde abril de 2026.

#### LLM Research

| Proyecto | Descripción | Estado |
|----------|-------------|--------|
| [latambench](https://latambench.org) | Benchmark generation-first para LLMs en español latinoamericano | Live |
| [amicus-eval](https://github.com/crafter-research/amicus-eval) | Benchmark abierto de recuperación legal sobre el corpus legalize-pe: gold set, ablaciones, métricas reproducibles | Live |

**Website**: [crafter.ing](https://crafter.ing)

Maintained by [Shiara](https://shiara.design) & [Railly](https://railly.dev)
Parte de [Crafter Station](https://crafterstation.com).
