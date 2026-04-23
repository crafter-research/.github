### Crafter Research

Tecnología cívica, gov-tech y evaluación de LLMs open-source para LATAM. Un laboratorio donde cada paper tiene un prototipo funcional.

#### Civic Tech — Elecciones Perú 2026

| Proyecto | Descripción | Estado |
|----------|-------------|--------|
| [actas-peru-2026](https://actas.crafter.ing) | Radiografía estadística de 88K+ actas electorales — 8 tests forenses, mapa interactivo, verificación de claims | Live |
| [onpe-cli](https://github.com/crafter-research/onpe-cli) | CLI agent-first para la API de resultados electorales ONPE — consulta mesas, actas, ubigeos | Live |
| [candidatos](https://candidatos.crafter.ing) | Explorador de candidatos para Elecciones Generales Perú 2026 — cruza datos JNE + peru-financia + political-graph | Live |
| [peru-financia](https://peru-financia.crafter.ing) | Mapa de financiamiento político peruano — datos ONPE 1995-2026 | Live |
| [political-graph](https://political-graph.crafter.ing) | Grafo interactivo de relaciones entre políticos y casos de corrupción | Live |
| [timeline-peru](https://github.com/crafter-research/timeline-peru) | Línea de tiempo pública de la historia peruana | WIP |

#### Andenar — Plataforma de compliance gov LATAM

[Andenar](https://andenar.com) orquesta adapters CLI agent-first por cada entidad gubernamental. Un adapter por portal. Todos convergen en un dashboard unificado.

| Adapter | Entidad | Caso | Estado |
|---------|---------|------|--------|
| [sunat-cli](https://github.com/crafter-station/sunat-cli) | SUNAT | RHE, F616, RUC, deuda tributaria | `npm`, live |
| [bcrp-cli](https://github.com/crafter-research/bcrp-cli) | BCRP | Tipo de cambio, inflación, series macro oficiales | `beta`, listo |
| [jne-cli](https://github.com/crafter-research/jne-cli) | JNE | Candidatos, expedientes, autoridades electorales | `dogfood` |
| [osce-seace-cli](https://github.com/crafter-research/osce-seace-cli) | OSCE/SEACE | Sanciones, proveedores, datos abiertos | `dogfood` |
| [sunarp-cli](https://github.com/crafter-research/sunarp-cli) | SUNARP | KYB registral, vehicular, partidas | `recon`, captcha |
| [sunedu-cli](https://github.com/crafter-research/sunedu-cli) | SUNEDU | Verificación grados y títulos | `recon`, Turnstile |
| [mtc-sutran-cli](https://github.com/crafter-research/mtc-sutran-cli) | MTC/SUTRAN | Licencias, papeletas, infracciones | `recon` |

**Estados**: `npm` publicado · `beta` listo para primer release · `dogfood` funciona con real data, faltan endpoints · `recon` bloqueos de captcha/Turnstile documentados.

#### Otros Gov-Tech Tools

| Proyecto | Descripción | Estado |
|----------|-------------|--------|
| [sunat-cli.crafter.ing](https://sunat-cli.crafter.ing) | Demo site del adapter SUNAT | Live |
| [onpe-cli](https://github.com/crafter-research/onpe-cli) | CLI agent-first para datos electorales ONPE — sec-fetch bypass, dual output JSON/human | Live |
| [legalize-pe](https://github.com/crafter-research/legalize-pe) | Herramienta para consultar y entender legislación peruana — inspirado en legalize-es | WIP |

#### LLM Research

| Proyecto | Descripción | Estado |
|----------|-------------|--------|
| [latambench](https://latambench.org) | Benchmark generation-first para LLMs en español latinoamericano | Live |

**Website**: [research.crafter.ing](https://github.com/crafter-research/website)

Parte de [Crafter Station](https://crafterstation.com).
