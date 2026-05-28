# Protocolos Cuánticos de Seguridad y Cifrado: Posicionamiento, Puntos Fuertes y Debilidades

Trabajo fin de máster que presenta un análisis comparativo sistemático de **8 protocolos QKD de variable discreta** (BB84, B92, E91, seis estados, SARG04, BB84 con estados señuelo, LM05, MDI-QKD) bajo un marco uniforme de 5 criterios.

## Estructura del repositorio

```
├── main.tex                # Documento raíz
├── estilo_unir-1.sty       # Estilo UNIR
├── bibliografia.tex        # Referencias
├── logo_unir.png           # Logotipo universidad
├── figuras/                # Imágenes
├── capitulos/
│   ├── 00_resumen.tex
│   ├── 01_abstract.tex
│   ├── 02_introduccion.tex
│   ├── 03_objetivos.tex
│   ├── 04_enunciado.tex
│   ├── 05_desarrollo.tex
│   ├── 06_conclusiones.tex
│   └── desarrollo/         # Análisis de protocolos
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
└── README.es.md
```

## Protocolos

| Protocolo | Año | Eficiencia | Característica principal |
|-----------|------|-----------|-------------------------|
| BB84 | 1984 | ~50 % | Referencia DV-QKD, 4 estados, 2 bases |
| B92 | 1992 | ~25 % | Simplificado, 2 estados no ortogonales |
| E91 | 1991 | Baja | Basado en entrelazamiento, CHSH |
| Seis estados | 1998 | ~33 % | 3 MUB, estimación simétrica de error |
| SARG04 | 2004 | ~25 % | Anuncio modificado, resistente a PNS |
| BB84 + señuelo | 2005 | ~50 % | Mejor protección PNS, larga distancia |
| LM05 | 2005 | Hasta ~100 % | Bidireccional, determinista |
| MDI-QKD | 2012 | Baja | Elimina canales laterales del detector |

Cada protocolo incluye un diagrama TikZ y un ejemplo práctico ronda a ronda con tablas de sifting.
