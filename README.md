# Quantum Security and Encryption Protocols: Positioning, Strengths, and Weaknesses

Master's thesis presenting a systematic comparative analysis of **8 discrete-variable QKD protocols** (BB84, B92, E91, six-state, SARG04, decoy-state BB84, LM05, MDI-QKD) under a uniform 5-criterion framework.

## Repository structure

```
├── main.tex                # Root document
├── estilo_unir-1.sty       # UNIR thesis style
├── bibliografia.tex        # References
├── logo_unir.png           # University logo
├── figuras/                # Images
├── capitulos/
│   ├── 00_resumen.tex
│   ├── 01_abstract.tex
│   ├── 02_introduccion.tex
│   ├── 03_objetivos.tex
│   ├── 04_enunciado.tex
│   ├── 05_desarrollo.tex
│   ├── 06_conclusiones.tex
│   └── desarrollo/         # Protocol analyses
│       ├── 01_plantilla_analisis.tex
│       ├── 02_conceptos_basicos.tex
│       ├── 03_protocolo_bb84.tex
│       ├── 04_protocolo_b92.tex
│       ├── 05_protocolo_e91.tex
│       ├── 06_protocolo_seis_estados.tex
│       ├── 07_protocolo_sarg04.tex
│       ├── 08_bb84_estados_senuelo.tex
│       ├── 09_protocolo_lm05.tex
│       └── 10_mdi_qkd.tex
└── README.md
```

## Protocols

| Protocol | Year | Efficiency | Key feature |
|----------|------|-----------|-------------|
| BB84 | 1984 | ~50% | Reference DV-QKD, 4 states, 2 bases |
| B92 | 1992 | ~25% | Simplified, 2 non-orthogonal states |
| E91 | 1991 | Low | Entanglement-based, CHSH inequality |
| Six-state | 1998 | ~33% | 3 MUBs, symmetric error estimation |
| SARG04 | 2004 | ~25% | Modified announcement, PNS-resistant |
| Decoy-state BB84 | 2005 | ~50% | Best PNS protection, long-distance |
| LM05 | 2005 | Up to ~100% | Bidirectional, deterministic |
| MDI-QKD | 2012 | Low | Eliminates detector side-channels |

Each protocol includes a TikZ flow diagram and a worked round-by-round example with sifting tables.
