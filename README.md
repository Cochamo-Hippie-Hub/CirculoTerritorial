# Círculo Territorial Cochamó

> Sistema de conocimiento y coordinación del Círculo Territorial de Cochamó — plataforma de gestión que articula comunidad, conservación, turismo sostenible y gobernanza local en el territorio de Cochamó.

**Organización:** [Cochamó Hippie Hub](https://github.com/Cochamo-Hippie-Hub)  
**Territorio:** Cochamó, Región de Los Lagos, Chile  
**Operado por:** Corporación Puelo Patagonia (CPP)

---

## Qué es el Círculo Territorial

El Círculo Territorial es la instancia de articulación entre la Corporación Puelo Patagonia y los actores del territorio de Cochamó: comunidades locales, escaladores, organizaciones vecinales, instituciones de conservación y autoridades. Este repositorio documenta y coordina ese trabajo.

## Estructura del repositorio

```
CirculoTerritorial/
├── docs/                  # Documentos de referencia
│   ├── minutas/           # Minutas de actividades y reuniones
│   ├── contactos/         # Registros de contactos relevantes
│   ├── legal/             # Documentos legales y jurídicos
│   └── estrategia/        # Documentos estratégicos
├── programas/             # Descripción de cada programa estratégico (M1–M8)
├── registros/             # Datos estructurados
│   ├── actividades/       # Registro de actividades por período
│   ├── participantes/     # Directorio de actores
│   └── cronologia/        # Línea de tiempo del proyecto
└── data/                  # Datos crudos y procesados
    ├── raw/               # Datos sin procesar
    └── processed/         # Datos limpios para análisis
```

## Programas estratégicos

| # | Programa | Descripción |
|---|----------|-------------|
| M1 | Educación Ambiental Territorial | Talleres en Cochamó y Puelo, formación comunitaria |
| M2 | Vinculación Comunitaria y Participación | Relación con JJVV, adultos mayores, actores locales |
| M3 | Uso Público y Escalada Sostenible | Gestión de visitantes, escaladores, clubes de montaña |
| M4 | Conservación y Áreas Protegidas | Articulación con TNC, corredor biológico |
| M5 | Gobernanza Territorial e Institucional | Estatutos OVC, estructura organizacional |
| M6 | Fundraising y Alianzas Estratégicas | Fondos concursables, propuestas a donantes |
| M7 | Conocimiento Territorial e Investigación | Entrevistas, mapeo de actores, historia oral |
| M8 | Infraestructura y Operaciones | Habilitación oficina Base Camp |

## Navegación por issues

- **Epic Issues (#1–#10):** Proyectos estratégicos. Etiqueta `epic`.
- **Issues operativos (#11–#21):** Problemas y registros derivados de actividades.
- Usa las etiquetas de tipo (`tipo: comunidad`, `tipo: legal`, etc.) y estado (`estado: desarrollo`, etc.) para filtrar.

## Convenciones

- **Minutas:** `YYYY-MM-DD_descripcion_breve.md`
- **Datos:** `YYYY_mes.csv`
- **Programas:** `MX_nombre_programa.md`
- **Issues:** Prefijo `[EPIC]`, `[PROBLEMA]` o `[REGISTRO]` en el título

## Relación con Cochamó Hippie Hub

Este repositorio es parte del ecosistema [Cochamó Hippie Hub](https://github.com/Cochamo-Hippie-Hub). Los issues técnicos y de innovación se gestionan en [Granite](https://github.com/Cochamo-Hippie-Hub/Granite). El Círculo Territorial aporta el contexto comunitario y territorial que alimenta las soluciones tecnológicas.

## Cómo contribuir

Lee [CONTRIBUTING.md](CONTRIBUTING.md) para conocer las reglas de contribución.

## Licencia

[MIT](LICENSE)
