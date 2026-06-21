<div align="center">

# Análisis de Rutas sobre Internet

![Networking](https://img.shields.io/badge/Networking-TCP/IP-0078D4?style=for-the-badge)
![Traceroute](https://img.shields.io/badge/Traceroute-Análisis-FF6B35?style=for-the-badge)
![BGP](https://img.shields.io/badge/BGP-Routing-2E86AB?style=for-the-badge)

> Diagnóstico de rutas de Internet con traceroute: análisis de latencia, saltos TTL y topología BGP.

## Descripción

</div>

---

Análisis de rutas de red sobre Internet empleando herramientas de trazado de ruta (`traceroute`/`tracert`): identificación de saltos TTL, medición de latencia por segmento, detección de cuellos de botella y estudio de las rutas BGP que siguen los paquetes entre diferentes sistemas autónomos (AS).

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `*.pdf` | Informe de análisis de rutas con capturas y tablas |
| `Tablas.xlsx` | Datos de latencia, TTL y rutas registradas |
| `*.docx` | Desarrollo del laboratorio |

## Arquitectura

```mermaid
flowchart TD
    A[Analisis de Rutas en Internet] --> B[Herramientas de Diagnostico]
    B --> C[traceroute - Trazado de rutas]
    B --> D[ping - Latencia y disponibilidad]
    B --> E[nslookup - Resolucion DNS]
    C --> F[Identificacion de saltos de red]
    D --> G[Metricas de latencia RTT]
    E --> H[Resolucion de nombres de dominio]
    F & G & H --> I[Analisis de topologia de red]
    I --> J[Informe de resultados - PDF/DOCX]
```

## Metodología aplicada

1. Ejecución de `traceroute` hacia destinos nacionales e internacionales
2. Registro de saltos, RTT (Round-Trip Time) y AS intermedios
3. Análisis de la topología de rutas y detección de anomalías
4. Comparativa de rutas desde distintos orígenes

## Contexto académico

**Asignatura:** Redes de Computadores · **Institución:** Ingeniería Informática
**Autor:** Alejandro De Mendoza — Ingeniero Informático · Máster Arquitectura de Software

---

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Especialista en Ingeniería de Software · Máster en Arquitectura de Software

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github)](https://github.com/AlejoTechEngineer)
