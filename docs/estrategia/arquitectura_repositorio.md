# Arquitectura de Repositorio GitHub — Círculo Territorial Cochamó

> **Proyecto**: Círculo Territorial — Corporación Puelo Patagonia (CPP)
> **Territorio**: Cochamó, Región de Los Lagos, Chile
> **Período datos fuente**: Octubre 2024
> **Generado**: Marzo 2026
> **Arquitecto**: Claude × Andrés Amengual

---

## TABLA DE CONTENIDOS

1. [Modelo Conceptual del Repositorio](#1-modelo-conceptual-del-repositorio)
2. [Estructura de Carpetas](#2-estructura-de-carpetas)
3. [Sistema de Etiquetas](#3-sistema-de-etiquetas)
4. [Lista de Participantes](#4-lista-de-participantes)
5. [Lista de Issues Generados](#5-lista-de-issues-generados)

---

## 1. MODELO CONCEPTUAL DEL REPOSITORIO

### 1.1 Nombre del repositorio

```
Cochamo-Hippie-Hub/CirculoTerritorial
```

### 1.2 Descripción

Sistema de conocimiento y coordinación del Círculo Territorial de Cochamó — plataforma de gestión que articula comunidad, conservación, turismo sostenible y gobernanza local en el territorio de Cochamó.

### 1.3 Jerarquía conceptual

```
PROGRAMAS (Milestones)
  └── PROYECTOS (Epic Issues)
        └── PROBLEMAS (Issues)
              └── TAREAS (Checklists dentro de Issues)
                    └── REGISTROS (archivos en /docs, /data, o referencias)
```

### 1.4 Programas identificados (→ Milestones)

| # | Programa (Milestone) | Descripción | Issues asociados |
|---|----------------------|-------------|------------------|
| M1 | **Educación Ambiental Territorial** | Talleres de educación ambiental en Cochamó y Puelo, formación comunitaria, autocuidado | 3 |
| M2 | **Vinculación Comunitaria y Participación** | Relación con JJVV, adultos mayores, actores locales, conflictos comunitarios | 5 |
| M3 | **Uso Público y Escalada Sostenible** | Gestión de visitantes, escaladores, clubes de montaña, Base Camp | 4 |
| M4 | **Conservación y Áreas Protegidas** | Articulación con TNC, áreas protegidas, corredor biológico | 2 |
| M5 | **Gobernanza Territorial e Institucional** | Estatutos OVC, estructura organizacional, convenios | 2 |
| M6 | **Fundraising y Alianzas Estratégicas** | Fondos concursables, propuestas a donantes, Kaya United | 2 |
| M7 | **Conocimiento Territorial e Investigación** | Entrevistas, contactos, mapeo de actores, historia oral | 5 |
| M8 | **Infraestructura y Operaciones** | Habilitación oficina Base Camp, instalaciones | 1 |

### 1.5 Proyectos identificados (→ Epic Issues)

| # | Proyecto (Epic) | Milestone | Descripción |
|---|-----------------|-----------|-------------|
| E1 | Programa de Talleres de Educación Ambiental | M1 | Ciclo de talleres en Cochamó y Puelo, incluyendo autocuidado y primeros auxilios |
| E2 | Red Comunitaria Cochamó–Puelo | M2 | Articulación con JJVV, dirigentes, adultos mayores y comunidad local |
| E3 | Conflicto Planta Chancadora | M2 | Seguimiento y gestión de problemática ambiental comunitaria |
| E4 | Gestión de Escalada y Uso Público | M3 | Conversatorios con clubes, regulación, seguridad en montaña |
| E5 | Habilitación Base Camp | M3/M8 | Inspección, habilitación de oficina y centro operativo |
| E6 | Articulación Áreas Protegidas | M4 | Coordinación con TNC y actores de conservación |
| E7 | Reforma Estatutos OVC | M5 | Modificación estatutaria de la Organización de Vecinos de Cochamó |
| E8 | Estrategia de Financiamiento | M6 | Fondos concursables y propuesta Kaya United |
| E9 | Mapeo de Actores Territoriales | M7 | Entrevistas, contactos, historia oral del territorio |
| E10 | Caso Jurídico Cayún – Segundo Corral | M7/M5 | Seguimiento legal del conflicto del camino militar en Segundo Corral |

---

## 2. ESTRUCTURA DE CARPETAS

```
CirculoTerritorial/
│
├── README.md                          # Descripción del proyecto y guía de navegación
├── CONTRIBUTING.md                    # Cómo contribuir al repositorio
├── LICENSE                            # Licencia MIT
│
├── docs/                              # Documentos de referencia y minutas
│   ├── minutas/                       # Minutas de actividades y reuniones
│   │   ├── 2024-10-08_conversatorio_jjvv_puelo.md
│   │   ├── 2024-10-08_charla_pucon.md
│   │   ├── 2024-10-09_visita_lonco_cayun.md
│   │   ├── 2024-10-09_entrevista_medrano_puelo.md
│   │   ├── 2024-10-14_encuentro_areas_protegidas.md
│   │   ├── 2024-10-15_encuentro_tnc.md
│   │   ├── 2024-10-17_entrevista_daniel_san.md
│   │   ├── 2024-10-21_problematica_chancadora.md
│   │   ├── 2024-10-23_inspeccion_base_camp.md
│   │   ├── 2024-10-23_visita_chancadora.md
│   │   ├── 2024-10-28_propuesta_kaya_united.md
│   │   ├── 2024-10-29_modificacion_estatutos_ovc.md
│   │   ├── 2024-10-30_conversatorio_clubes_montana.md
│   │   └── 2024-10-31_habilitacion_oficina_base_camp.md
│   │
│   ├── contactos/                     # Registros de contactos relevantes
│   │   ├── 2024-10-08_leticia_contreras.md
│   │   └── 2024-10-16_leticia_contreras_seguimiento.md
│   │
│   ├── legal/                         # Documentos legales y jurídicos
│   │   ├── caso_cayun_segundo_corral.md
│   │   └── estatutos_ovc_propuesta.md
│   │
│   └── estrategia/                    # Documentos estratégicos
│       ├── propuesta_kaya_united.md
│       └── fondos_concursables_2024.md
│
├── programas/                         # Descripción de cada programa estratégico
│   ├── M1_educacion_ambiental.md
│   ├── M2_vinculacion_comunitaria.md
│   ├── M3_uso_publico_escalada.md
│   ├── M4_conservacion_areas_protegidas.md
│   ├── M5_gobernanza_institucional.md
│   ├── M6_fundraising_alianzas.md
│   ├── M7_conocimiento_territorial.md
│   └── M8_infraestructura_operaciones.md
│
├── registros/                         # Datos estructurados y registros
│   ├── actividades/                   # Registro de actividades por período
│   │   └── 2024_octubre.csv
│   ├── participantes/                 # Directorio de actores
│   │   └── directorio_actores.csv
│   └── cronologia/                    # Línea de tiempo del proyecto
│       └── timeline_2024.md
│
├── data/                              # Datos crudos y procesados
│   ├── raw/                           # Datos sin procesar (planillas originales)
│   └── processed/                     # Datos limpios para análisis
│
└── .github/                           # Configuración GitHub
    ├── ISSUE_TEMPLATE/
    │   ├── epic.md                    # Template para Epic Issues (proyectos)
    │   ├── problema.md                # Template para problemas
    │   └── registro.md                # Template para registros/antecedentes
    └── labels.json                    # Definición de etiquetas
```

### 2.1 Convenciones de nombrado

- **Minutas**: `YYYY-MM-DD_descripcion_breve.md`
- **Datos**: `YYYY_mes.csv` o `YYYY_periodo.csv`
- **Programas**: `MX_nombre_programa.md` (X = número de milestone)
- **Issues**: Título descriptivo + prefijo de tipo `[EPIC]`, `[PROBLEMA]`, `[REGISTRO]`

---

## 3. SISTEMA DE ETIQUETAS

### 3.1 Etiquetas por tipo

| Etiqueta | Color | Descripción |
|----------|-------|-------------|
| `tipo: investigación` | `#0E8A16` verde | Levantamiento de información, entrevistas, mapeo |
| `tipo: gestión` | `#1D76DB` azul | Coordinación, logística, administración |
| `tipo: gobernanza` | `#5319E7` púrpura | Estatutos, normativa, estructura organizacional |
| `tipo: tecnología` | `#006B75` teal | Sistemas, datos, plataformas digitales |
| `tipo: territorio` | `#B60205` rojo | Acciones directas en terreno |
| `tipo: comunidad` | `#FBCA04` amarillo | Vinculación con actores locales |
| `tipo: legal` | `#D93F0B` naranja | Asuntos jurídicos, conflictos legales |
| `tipo: educación` | `#C2E0C6` verde claro | Talleres, formación, capacitación |

### 3.2 Etiquetas por estado

| Etiqueta | Color | Descripción |
|----------|-------|-------------|
| `estado: idea` | `#F9D0C4` rosa claro | Identificado pero sin análisis |
| `estado: análisis` | `#FEF2C0` crema | En proceso de análisis y diseño |
| `estado: desarrollo` | `#BFD4F2` celeste | En ejecución activa |
| `estado: implementación` | `#0E8A16` verde | Implementado, operando |
| `estado: cerrado` | `#CCCCCC` gris | Finalizado o archivado |

### 3.3 Etiquetas por prioridad

| Etiqueta | Color | Descripción |
|----------|-------|-------------|
| `prioridad: alta` | `#B60205` rojo | Requiere atención inmediata |
| `prioridad: media` | `#FBCA04` amarillo | Importante pero sin urgencia crítica |
| `prioridad: baja` | `#0E8A16` verde | Puede esperar, no bloquea otros procesos |

### 3.4 Etiquetas por área temática

| Etiqueta | Color | Descripción |
|----------|-------|-------------|
| `área: biodiversidad` | `#0E8A16` verde | Flora, fauna, ecosistemas, especies invasoras |
| `área: turismo` | `#1D76DB` azul | Visitantes, escaladores, uso recreativo |
| `área: acceso` | `#D93F0B` naranja | Caminos, senderos, conectividad |
| `área: seguridad` | `#B60205` rojo | Seguridad en montaña, emergencias, rescate |
| `área: infraestructura` | `#006B75` teal | Instalaciones, oficinas, equipamiento |
| `área: datos` | `#5319E7` púrpura | Información, registros, monitoreo |
| `área: agua` | `#1D76DB` azul | Recursos hídricos, cuencas |
| `área: cultura` | `#FBCA04` amarillo | Patrimonio cultural, pueblos originarios |

### 3.5 Etiquetas especiales

| Etiqueta | Color | Descripción |
|----------|-------|-------------|
| `epic` | `#000000` negro | Marca un issue como proyecto/epic |
| `minuta pendiente` | `#E4E669` amarillo pálido | Actividad sin minuta documentada |
| `requiere seguimiento` | `#D93F0B` naranja | Necesita acción de seguimiento |
| `vinculado a CHH` | `#006B75` teal | Conexión con Cochamó Hippie Hub |
| `conflicto activo` | `#B60205` rojo | Situación conflictiva en curso |

---

## 4. LISTA DE PARTICIPANTES

### 4.1 Directorio de actores identificados

| # | Nombre | Rol inferido | Tipo de participación | Frecuencia (oct-2024) | Asignación sugerida |
|---|--------|-------------|----------------------|----------------------|---------------------|
| 1 | **Tatiana Sandoval** | Coordinadora territorial CPP | Ejecución directa: talleres, comunidad, gestión, escalada | 14 actividades | Issues de comunidad, educación ambiental, escalada |
| 2 | **Andrés Amengual** | Asesor legal CPP / Secretario | Legal, gobernanza, fundraising, contactos, inspecciones | 13 actividades | Issues legales, gobernanza, estrategia, fundraising |
| 3 | **Andrés Diez** | Director / líder estratégico CPP | Visitas territoriales, charlas, articulación institucional | 7 actividades | Issues estratégicos, territorio, áreas protegidas |
| 4 | **Bernardita Ortiz** | Contacto / vinculación | Contactos comunitarios, JJVV | 2 actividades | Issues de vinculación comunitaria |
| 5 | **Nicolás Amadori** | Operaciones / logística | Inspección Base Camp, habilitación oficina | 2 actividades | Issues de infraestructura |
| 6 | **Carmen Gallardo** | Dirigenta comunitaria | Conversatorio JJVV Puelo | 1 actividad | Issues de comunidad Puelo |
| 7 | **Gabriel Gómez** | Apoyo gestión | Fondos concursables | 1 actividad | Issues de fundraising |
| 8 | **Josefina Vigoroux** | Vinculación escalada | Conversatorio clubes de montaña | 1 actividad | Issues de escalada/uso público |

### 4.2 Actores externos mencionados (sin participación directa registrada)

| # | Nombre | Contexto | Relación |
|---|--------|----------|----------|
| 1 | **Eliecer Cayún** | Lonco en Segundo Corral | Caso jurídico conflicto camino militar |
| 2 | **Juan Medrano** | Entrevistado en Puelo – Las Hualas | Conocimiento territorial / historia oral |
| 3 | **Leticia Contreras** | Contacto comunitario (dos registros) | Vinculación comunitaria |
| 4 | **Daniel San** | Entrevistado | Conocimiento territorial |
| 5 | **José Datoli** | Preparación conversatorio escaladores | Actor del mundo de la escalada |
| 6 | **Abogado Millamán** | Representante legal familia Cayún | Caso jurídico Segundo Corral |

### 4.3 Instituciones mencionadas

| Institución | Contexto | Issues relacionados |
|-------------|----------|---------------------|
| **TNC (The Nature Conservancy)** | Encuentro de articulación | #14 |
| **Kaya United** | Propuesta de financiamiento | #18 |
| **OVC (Org. Vecinos Cochamó)** | Modificación de estatutos | #16 |
| **JJVV Puelo** | Conversatorio con directivas | #8 |
| **Cuerpo Militar del Trabajo** | Construcción camino en Segundo Corral | #20 |
| **Clubes de Montaña** | Conversatorio sobre escalada | #12 |

---

## 5. LISTA DE ISSUES GENERADOS

### Convención de numeración

- `#1–#10`: Epic Issues (proyectos)
- `#11–#30`: Issues operativos (problemas y registros derivados de actividades)

---

### EPIC ISSUES (Proyectos)

---

#### Issue #1 — [EPIC] Programa de Talleres de Educación Ambiental

**Contexto:**
El Círculo Territorial ejecuta un ciclo de talleres de educación ambiental en las localidades de Cochamó y Puelo. En octubre 2024 se realizaron tres talleres: dos segundos talleres (Cochamó y Puelo) y uno específico sobre autocuidado y primeros auxilios en Puelo.

**Objetivo:**
Consolidar un programa permanente de educación ambiental territorial que fortalezca la conciencia ecológica de las comunidades de Cochamó y Puelo.

**Tareas:**
- [ ] Sistematizar contenidos de talleres realizados (oct 2024)
- [ ] Documentar minutas pendientes de los 3 talleres
- [ ] Diseñar programa curricular 2025
- [ ] Evaluar impacto y participación de talleres anteriores
- [ ] Identificar financiamiento para continuidad del programa
- [ ] Coordinar con establecimientos educacionales locales

**Participantes:** Tatiana Sandoval (líder), Andrés Amengual (apoyo)

**Referencias:**
- Actividad 2/10/2024: 2do Taller Educación Ambiental Cochamó
- Actividad 4/10/2024: 2do Taller Educación Ambiental Puelo
- Actividad 18/10/2024: Taller autocuidado y primeros auxilios Puelo

**Etiquetas:** `epic`, `tipo: educación`, `tipo: comunidad`, `área: biodiversidad`, `estado: desarrollo`, `prioridad: alta`

**Milestone:** M1 — Educación Ambiental Territorial

---

#### Issue #2 — [EPIC] Red Comunitaria Cochamó–Puelo

**Contexto:**
El Círculo Territorial desarrolla vinculación activa con organizaciones comunitarias del territorio: Juntas de Vecinos de Puelo, adultos mayores de Cochamó, dirigentes locales y contactos estratégicos. En octubre 2024 se realizaron conversatorios con directivas de JJVV, encuentros con adultos mayores y contactos con actores comunitarios clave.

**Objetivo:**
Construir una red comunitaria articulada que permita participación efectiva de los habitantes del territorio en las decisiones de conservación y desarrollo local.

**Tareas:**
- [ ] Mapear todas las organizaciones comunitarias activas en Cochamó y Puelo
- [ ] Sistematizar contactos realizados (Leticia Contreras, Carmen Gallardo, Bernardita Ortiz)
- [ ] Establecer calendario de encuentros periódicos con JJVV
- [ ] Documentar necesidades y preocupaciones comunitarias expresadas
- [ ] Crear directorio digital de dirigentes y organizaciones
- [ ] Diseñar mecanismo de retroalimentación permanente

**Participantes:** Tatiana Sandoval, Bernardita Ortiz, Carmen Gallardo, Andrés Amengual

**Referencias:**
- Actividad 8/10/2024: Conversatorio Directivas JJVV Puelo — [minuta](https://docs.google.com/document/d/19YF8kg0c10hUZ8lWBfUgcZnVhF1rHYZI/edit)
- Actividad 8/10/2024: Contacto Leticia Contreras — [minuta](https://docs.google.com/document/d/1NL8Ec6WjANWwKKZcOaZ22r374XYATx1WysP-IP_7g6A/edit)
- Actividad 12/10/2024: Encuentro Adulto Mayor Sede Cochamó (minuta pendiente)
- Actividad 16/10/2024: Contacto Leticia Contreras seguimiento

**Etiquetas:** `epic`, `tipo: comunidad`, `tipo: gestión`, `área: datos`, `estado: desarrollo`, `prioridad: alta`

**Milestone:** M2 — Vinculación Comunitaria y Participación

**Relaciones:** Relacionado con #3 (Planta Chancadora)

---

#### Issue #3 — [EPIC] Conflicto Planta Chancadora

**Contexto:**
Se identifica una problemática ambiental comunitaria vinculada a una planta chancadora en el territorio. Hubo al menos dos actividades en octubre 2024: una reunión inicial sobre la problemática y una visita directa a la planta.

**Objetivo:**
Documentar, dar seguimiento y gestionar la resolución del conflicto ambiental vinculado a la planta chancadora, protegiendo los intereses de la comunidad y el ecosistema.

**Tareas:**
- [ ] Consolidar registro documental de la problemática (minutas 21/10 y 23/10)
- [ ] Identificar actores involucrados: empresa, comunidad, autoridad ambiental
- [ ] Evaluar impacto ambiental observado
- [ ] Definir estrategia de acción (legal, administrativa, comunitaria)
- [ ] Coordinar con comunidad afectada
- [ ] Evaluar pertinencia de denuncia ante SMA o Tribunal Ambiental

**Participantes:** Tatiana Sandoval, Andrés Amengual

**Referencias:**
- Actividad 21/10/2024: Comunidad problemática planta chancadora — [minuta](https://docs.google.com/document/d/1ooDnrYVzEN8uzwoF0s6rhWrYSXXpcLhzqL7iCeVkiA4/edit)
- Actividad 23/10/2024: Visita planta chancadora — [misma minuta](https://docs.google.com/document/d/1ooDnrYVzEN8uzwoF0s6rhWrYSXXpcLhzqL7iCeVkiA4/edit)

**Etiquetas:** `epic`, `tipo: comunidad`, `tipo: legal`, `tipo: territorio`, `conflicto activo`, `prioridad: alta`

**Milestone:** M2 — Vinculación Comunitaria y Participación

**Relaciones:** Relacionado con #2 (Red Comunitaria), Vinculado a M5 Gobernanza

---

#### Issue #4 — [EPIC] Gestión de Escalada y Uso Público

**Contexto:**
Cochamó es un destino mundial de escalada en roca ("Yosemite de Sudamérica"). El Círculo Territorial gestiona la relación con la comunidad de escaladores a través de conversatorios con clubes de montaña, preparación de regulaciones y articulación con operadores como José Datoli. En octubre 2024 se realizó un conversatorio con clubes de montaña y se preparó un conversatorio con escaladores.

**Objetivo:**
Desarrollar un modelo de uso público sostenible para la escalada en Cochamó que equilibre conservación, seguridad y acceso.

**Tareas:**
- [ ] Sistematizar resultados del conversatorio clubes de montaña (30/10/2024)
- [ ] Completar preparación del conversatorio con escaladores (José Datoli)
- [ ] Diseñar protocolo de registro de escaladores (check-in/check-out)
- [ ] Evaluar capacidad de carga de sectores de escalada
- [ ] Articular con CONAF y administradores de áreas protegidas
- [ ] Diseñar sistema de información para visitantes

**Participantes:** Tatiana Sandoval, Andrés Diez, Josefina Vigoroux, Andrés Amengual, José Datoli (externo)

**Referencias:**
- Actividad 8/10/2024: Prep. conversatorio escaladores con José Datoli (minuta pendiente)
- Actividad 30/10/2024: Conversatorio Clubes de Montaña — [minuta](https://docs.google.com/document/d/1SPwunHF4NnOtXD57mY33I6V9W4vDe03y/edit)

**Etiquetas:** `epic`, `tipo: gestión`, `tipo: territorio`, `área: turismo`, `área: seguridad`, `estado: desarrollo`, `prioridad: alta`, `vinculado a CHH`

**Milestone:** M3 — Uso Público y Escalada Sostenible

**Relaciones:** Relacionado con #5 (Base Camp), Amplía issues de Granite/CHH sobre seguridad escaladores

---

#### Issue #5 — [EPIC] Habilitación Base Camp

**Contexto:**
El Círculo Territorial gestiona la habilitación de un centro operativo en Base Camp. En octubre 2024 se realizó una inspección con revisión de instalaciones y gestiones para habilitar una oficina permanente.

**Objetivo:**
Establecer un centro operativo funcional en Base Camp que sirva como punto de coordinación territorial, atención a visitantes y base logística del Círculo Territorial.

**Tareas:**
- [ ] Completar inventario de condiciones actuales de instalaciones
- [ ] Definir requerimientos mínimos de la oficina
- [ ] Gestionar permisos y autorizaciones necesarias
- [ ] Presupuestar adecuaciones e implementación
- [ ] Instalar equipamiento básico (comunicaciones, mobiliario)
- [ ] Definir protocolo de operación del centro

**Participantes:** Tatiana Sandoval, Nicolás Amadori, Andrés Amengual

**Referencias:**
- Actividad 23/10/2024: Inspección y visita a Base Camp — [minuta](https://docs.google.com/document/d/1lpK0kfj2_m3Up2vlU9zTva_ogd_3GxtG-2DbX_QhdKk/edit)
- Actividad 31/10/2024: Gestiones habilitación oficina — [minuta](https://docs.google.com/document/d/1yFn0z-IWV-xCoQkE397c9Z9qho5eVQ8w-8anWX7MX4I/edit)

**Etiquetas:** `epic`, `tipo: gestión`, `área: infraestructura`, `estado: desarrollo`, `prioridad: media`

**Milestone:** M3 — Uso Público y Escalada Sostenible / M8 — Infraestructura y Operaciones

**Relaciones:** Relacionado con #4 (Escalada y Uso Público)

---

#### Issue #6 — [EPIC] Articulación con Áreas Protegidas y TNC

**Contexto:**
El Círculo Territorial mantiene coordinación con The Nature Conservancy (TNC) y participa en encuentros sobre áreas protegidas. TNC Chile es cofundadora de la Fundación Conserva Pucheguín. La articulación busca alinear la gestión territorial de Cochamó con las estrategias regionales de conservación.

**Objetivo:**
Consolidar la articulación institucional entre el Círculo Territorial, TNC y los administradores de áreas protegidas para una gestión territorial coherente.

**Tareas:**
- [ ] Sistematizar acuerdos del encuentro con TNC (15/10/2024)
- [ ] Sistematizar resultados del encuentro áreas protegidas (14/10/2024)
- [ ] Mapear áreas protegidas existentes y propuestas en el territorio
- [ ] Identificar brechas de protección y oportunidades de complementariedad
- [ ] Definir agenda de trabajo conjunto con TNC
- [ ] Evaluar sinergias con proyecto Conserva Pucheguín (FCP)

**Participantes:** Andrés Diez, Tatiana Sandoval

**Referencias:**
- Actividad 14/10/2024: Encuentro Áreas Protegidas — [minuta](https://docs.google.com/document/d/1oSXc9xplA08u2n9rpY52DRLrpIACW9y9tIWiREgyq0k/edit)
- Actividad 15/10/2024: Encuentro TNC — [minuta](https://docs.google.com/document/d/1_UzJy69_AZWu92lx_5yD03U7xkkKYbsCv0WfPdMtNJE/edit)

**Etiquetas:** `epic`, `tipo: gestión`, `tipo: territorio`, `área: biodiversidad`, `estado: análisis`, `prioridad: alta`

**Milestone:** M4 — Conservación y Áreas Protegidas

**Relaciones:** Amplía contexto de proyecto Conserva Pucheguín (FCP)

---

#### Issue #7 — [EPIC] Reforma de Estatutos OVC

**Contexto:**
El 29 de octubre de 2024 se asumió formalmente la tarea de modificar los estatutos de la Organización de Vecinos de Cochamó (OVC). Esta reforma es clave para la gobernanza territorial porque define las reglas de participación comunitaria.

**Objetivo:**
Completar la modificación estatutaria de la OVC para adecuarla a las necesidades actuales de gobernanza territorial participativa.

**Tareas:**
- [ ] Revisar estatutos vigentes de la OVC
- [ ] Identificar artículos que requieren modificación
- [ ] Proponer texto de reforma
- [ ] Consultar con directiva de la OVC
- [ ] Validar legalmente la propuesta de modificación
- [ ] Acompañar proceso de aprobación en asamblea
- [ ] Inscribir estatutos reformados

**Participantes:** Andrés Amengual (líder legal), Tatiana Sandoval

**Referencias:**
- Actividad 29/10/2024: Modificación estatutos OVC — [minuta](https://docs.google.com/document/d/1Ije-Eo6j2DlUCyiwC58DMrWi5y5x-ODTAe8wca5CAhE/edit)

**Etiquetas:** `epic`, `tipo: gobernanza`, `tipo: legal`, `estado: análisis`, `prioridad: media`

**Milestone:** M5 — Gobernanza Territorial e Institucional

**Relaciones:** Relacionado con #2 (Red Comunitaria)

---

#### Issue #8 — [EPIC] Estrategia de Financiamiento

**Contexto:**
El Círculo Territorial gestiona dos líneas de financiamiento identificadas en octubre 2024: fondos concursables (gestión iniciada el 4/10) y una propuesta específica para Kaya United (redactada el 28/10).

**Objetivo:**
Asegurar financiamiento sostenible para las operaciones y programas del Círculo Territorial.

**Tareas:**
- [ ] Completar postulación a fondos concursables identificados
- [ ] Finalizar y enviar propuesta Kaya United
- [ ] Mapear fuentes de financiamiento adicionales (FPA, FNDR, internacionales)
- [ ] Diseñar presupuesto operacional del Círculo Territorial
- [ ] Evaluar modelo de ingresos propios (ecoturismo, servicios, carbono)
- [ ] Crear banco de propuestas reutilizables

**Participantes:** Andrés Amengual (líder), Tatiana Sandoval, Gabriel Gómez

**Referencias:**
- Actividad 4/10/2024: Gestión fondos concursables (minuta pendiente)
- Actividad 28/10/2024: Propuesta Kaya United — [documento](https://docs.google.com/document/d/15XMl8C46yBGhJdpcih-_z6FJGyYwojN0Xz0NVGya_qk/edit)

**Etiquetas:** `epic`, `tipo: gestión`, `estado: desarrollo`, `prioridad: alta`

**Milestone:** M6 — Fundraising y Alianzas Estratégicas

---

#### Issue #9 — [EPIC] Mapeo de Actores Territoriales

**Contexto:**
Durante octubre 2024, el Círculo Territorial realizó un intenso trabajo de levantamiento territorial: entrevistas a habitantes de Puelo (Juan Medrano, Daniel San), visita al lonco Eliecer Cayún en Segundo Corral, charla en Pucón, y múltiples contactos con actores locales. Este trabajo construye la base de conocimiento del territorio.

**Objetivo:**
Construir un mapeo completo de actores territoriales de Cochamó que documente la historia oral, las relaciones sociales y las dinámicas del territorio.

**Tareas:**
- [ ] Consolidar todas las entrevistas realizadas en un formato estándar
- [ ] Crear fichas de actores territoriales
- [ ] Mapear relaciones entre actores (mapa de poder/influencia)
- [ ] Identificar actores faltantes por entrevistar
- [ ] Documentar historia oral recopilada
- [ ] Georreferenciar actores cuando sea posible
- [ ] Clasificar actores por tipo: comunidad, institucional, productivo, cultural

**Participantes:** Andrés Amengual, Andrés Diez, Bernardita Ortiz

**Referencias:**
- Actividad 8/10/2024: Charla en Pucón — [minuta](https://docs.google.com/document/d/1RihrxHDSrkxmmSOMKuof6nLodHgwk4Lenzpzt9onIgA/edit)
- Actividad 9/10/2024: Visita lonco Cayún — [minuta](https://docs.google.com/document/d/1xGKtq41U_fSkjK64HumTMe9nG0ZxxxJMDJF55H8xxBE/edit)
- Actividad 9/10/2024: Entrevista Medrano — [minuta](https://docs.google.com/document/d/10eSr8lGuov7sNWXomaG7wXiF3-kgYJQ0e7si5YbGuGc/edit)
- Actividad 17/10/2024: Entrevista Daniel San — [minuta](https://docs.google.com/document/d/17p6dWhglOu-PIT9Zw_twwGyA8JEdNGLzMfj9sFZwsxw/edit)

**Etiquetas:** `epic`, `tipo: investigación`, `tipo: territorio`, `área: datos`, `área: cultura`, `estado: desarrollo`, `prioridad: alta`, `vinculado a CHH`

**Milestone:** M7 — Conocimiento Territorial e Investigación

**Relaciones:** Alimenta #2 (Red Comunitaria), Alimenta #10 (Caso Cayún)

---

#### Issue #10 — [EPIC] Caso Jurídico Cayún – Segundo Corral

**Contexto:**
En Segundo Corral, el Cuerpo Militar del Trabajo construye un camino que ha generado un conflicto con la comunidad indígena local (familia/comunidad Cayún). El lonco Eliecer Cayún fue visitado el 9/10/2024. El 28/10/2024, Andrés Diez solicita antecedentes al abogado Millamán sobre las acciones judiciales interpuestas por los Cayún contra la construcción del camino.

**Objetivo:**
Hacer seguimiento informado del conflicto jurídico-territorial en Segundo Corral, documentar los antecedentes y evaluar la posición del Círculo Territorial frente al caso.

**Tareas:**
- [ ] Recopilar antecedentes judiciales (acciones interpuestas por familia Cayún)
- [ ] Obtener respuesta del abogado Millamán
- [ ] Documentar cronología del conflicto
- [ ] Evaluar impacto ambiental y territorial del camino
- [ ] Definir posición institucional del Círculo Territorial / CPP
- [ ] Evaluar pertinencia de intervención como tercero interesado
- [ ] Monitorear avance de la causa judicial

**Participantes:** Andrés Diez (líder), Andrés Amengual (legal)

**Referencias:**
- Actividad 9/10/2024: Visita a lonco Eliecer Cayún — [minuta](https://docs.google.com/document/d/1xGKtq41U_fSkjK64HumTMe9nG0ZxxxJMDJF55H8xxBE/edit)
- Actividad 28/10/2024: Solicitud antecedentes abogado Millamán — texto de registro directo

**Etiquetas:** `epic`, `tipo: legal`, `tipo: territorio`, `área: acceso`, `área: cultura`, `conflicto activo`, `estado: análisis`, `prioridad: alta`

**Milestone:** M5 — Gobernanza Territorial e Institucional / M7 — Conocimiento Territorial

**Relaciones:** Relacionado con #9 (Mapeo de Actores)

---

### ISSUES OPERATIVOS (derivados de actividades específicas)

---

#### Issue #11 — [PROBLEMA] Minutas pendientes de documentar (octubre 2024)

**Contexto:**
De las 23 actividades registradas en octubre 2024, al menos 6 figuran con minuta "PENDIENTE": talleres de educación ambiental (2/10, 4/10, 18/10), fondos concursables (4/10), encuentro adulto mayor (12/10), y preparación conversatorio escaladores (8/10).

**Objetivo:**
Completar la documentación de todas las actividades que carecen de minuta para no perder memoria institucional.

**Tareas:**
- [ ] 2/10/2024 — 2do Taller Educación Ambiental Cochamó (Tatiana)
- [ ] 4/10/2024 — 2do Taller Educación Ambiental Puelo (Tatiana)
- [ ] 4/10/2024 — Gestión fondos concursables (Tatiana/Andrés A./Gabriel)
- [ ] 8/10/2024 — Prep. Conversatorio Escaladores con José Datoli
- [ ] 12/10/2024 — Encuentro Adulto Mayor Sede Cochamó (Andrés D./Tatiana)
- [ ] 18/10/2024 — Taller Educación Ambiental Puelo: autocuidado (Tatiana)

**Participantes:** Tatiana Sandoval (principal), Andrés Amengual, Andrés Diez

**Etiquetas:** `tipo: gestión`, `minuta pendiente`, `prioridad: alta`, `estado: idea`

**Milestone:** Transversal (afecta M1, M2, M3, M6)

**Relaciones:** Bloquea documentación de #1, #2, #4, #8

---

#### Issue #12 — [PROBLEMA] Preparación conversatorio con escaladores

**Contexto:**
El 8/10/2024 se registra un contacto entre Tatiana Sandoval y José Datoli para preparar un conversatorio con escaladores. No hay minuta y el estado de avance no está documentado. El conversatorio con clubes de montaña (30/10) ya se realizó, pero el conversatorio específico con escaladores parece pendiente.

**Objetivo:**
Concretar el conversatorio con escaladores del valle de Cochamó para levantar sus necesidades, preocupaciones y propuestas de coexistencia.

**Tareas:**
- [ ] Contactar a José Datoli para estado actual de la preparación
- [ ] Definir fecha, lugar y formato del conversatorio
- [ ] Identificar escaladores clave a invitar
- [ ] Preparar temario (seguridad, impacto, regulación, check-in/out)
- [ ] Sistematizar resultados del conversatorio de clubes de montaña (30/10) como insumo
- [ ] Ejecutar conversatorio
- [ ] Documentar resultados

**Participantes:** Tatiana Sandoval, José Datoli (externo)

**Etiquetas:** `tipo: gestión`, `tipo: comunidad`, `área: turismo`, `área: seguridad`, `requiere seguimiento`, `prioridad: media`

**Milestone:** M3 — Uso Público y Escalada Sostenible

**Relaciones:** Depende de #4 (Escalada y Uso Público), Relacionado con #11 (Minutas pendientes)

---

#### Issue #13 — [REGISTRO] Contacto Leticia Contreras — seguimiento bilateral

**Contexto:**
Se registran dos contactos con Leticia Contreras en octubre 2024: el primero el 8/10 a través de Bernardita Ortiz y el segundo el 16/10 directamente con Andrés Amengual. Ambos apuntan al mismo documento en Google Docs, lo que sugiere un seguimiento activo del vínculo.

**Objetivo:**
Documentar y dar continuidad a la relación con Leticia Contreras como actora comunitaria relevante.

**Tareas:**
- [ ] Consolidar registro de ambos contactos
- [ ] Identificar acuerdos o compromisos asumidos
- [ ] Definir próximos pasos de vinculación
- [ ] Incorporar a directorio de actores territoriales

**Participantes:** Bernardita Ortiz, Andrés Amengual

**Referencias:**
- [Documento de contacto](https://docs.google.com/document/d/1NL8Ec6WjANWwKKZcOaZ22r374XYATx1WysP-IP_7g6A/edit)

**Etiquetas:** `tipo: comunidad`, `tipo: investigación`, `área: datos`, `estado: desarrollo`, `prioridad: baja`

**Milestone:** M7 — Conocimiento Territorial e Investigación

**Relaciones:** Alimenta #9 (Mapeo de Actores), Alimenta #2 (Red Comunitaria)

---

#### Issue #14 — [REGISTRO] Encuentro con TNC — articulación institucional

**Contexto:**
El 15/10/2024 se realizó un encuentro con TNC Chile. TNC es cofundadora de la Fundación Conserva Pucheguín junto con CPP y Freyja Foundation. La articulación con TNC es estratégica para la conservación del territorio de Cochamó.

**Objetivo:**
Documentar acuerdos del encuentro con TNC y definir agenda de trabajo conjunto.

**Tareas:**
- [ ] Sistematizar minuta del encuentro
- [ ] Identificar compromisos asumidos por cada parte
- [ ] Alinear con agenda de FCP y proyecto Conserva Pucheguín
- [ ] Definir próximo hito de coordinación

**Participantes:** Tatiana Sandoval

**Referencias:**
- [Minuta del encuentro](https://docs.google.com/document/d/1_UzJy69_AZWu92lx_5yD03U7xkkKYbsCv0WfPdMtNJE/edit)

**Etiquetas:** `tipo: gestión`, `área: biodiversidad`, `estado: análisis`, `prioridad: media`

**Milestone:** M4 — Conservación y Áreas Protegidas

**Relaciones:** Amplía #6 (Articulación Áreas Protegidas)

---

#### Issue #15 — [REGISTRO] Encuentro Áreas Protegidas — 14/10/2024

**Contexto:**
El 14/10/2024 se realizó un encuentro sobre áreas protegidas con participación de Andrés Diez y Tatiana Sandoval.

**Objetivo:**
Documentar el estado de las áreas protegidas en el territorio y las oportunidades de articulación.

**Tareas:**
- [ ] Sistematizar contenido de la minuta
- [ ] Mapear áreas protegidas discutidas
- [ ] Identificar brechas de protección territorial
- [ ] Vincular con estrategia de corredor biológico

**Participantes:** Andrés Diez, Tatiana Sandoval

**Referencias:**
- [Minuta](https://docs.google.com/document/d/1oSXc9xplA08u2n9rpY52DRLrpIACW9y9tIWiREgyq0k/edit)

**Etiquetas:** `tipo: investigación`, `tipo: territorio`, `área: biodiversidad`, `estado: análisis`, `prioridad: media`

**Milestone:** M4 — Conservación y Áreas Protegidas

**Relaciones:** Amplía #6 (Articulación Áreas Protegidas)

---

#### Issue #16 — [PROBLEMA] Modificación estatutos OVC — ejecución

**Contexto:**
El 29/10/2024 se asume formalmente la tarea de modificar los estatutos de la Organización de Vecinos de Cochamó (OVC).

**Objetivo:**
Ejecutar el proceso de reforma estatutaria.

**Tareas:**
- [ ] Obtener copia vigente de los estatutos
- [ ] Identificar artículos a reformar con justificación
- [ ] Redactar propuesta de reforma
- [ ] Presentar a directiva OVC para validación
- [ ] Convocar asamblea de aprobación
- [ ] Protocolizar y registrar

**Participantes:** Andrés Amengual (redacción legal), Tatiana Sandoval (coordinación comunitaria)

**Referencias:**
- [Minuta](https://docs.google.com/document/d/1Ije-Eo6j2DlUCyiwC58DMrWi5y5x-ODTAe8wca5CAhE/edit)

**Etiquetas:** `tipo: gobernanza`, `tipo: legal`, `estado: análisis`, `prioridad: media`

**Milestone:** M5 — Gobernanza Territorial e Institucional

**Relaciones:** Depende de #7 (Epic Reforma Estatutos)

---

#### Issue #17 — [REGISTRO] Conversatorio Clubes de Montaña — 30/10/2024

**Contexto:**
El 30/10/2024 se realizó un conversatorio con clubes de montaña con participación de Andrés Diez, Tatiana Sandoval, Josefina Vigoroux y Andrés Amengual. Este es un hito clave para la gestión del uso público en el territorio.

**Objetivo:**
Sistematizar los resultados del conversatorio y convertirlos en insumos para la política de uso público.

**Tareas:**
- [ ] Extraer acuerdos y compromisos de la minuta
- [ ] Identificar clubes participantes y sus posiciones
- [ ] Mapear preocupaciones comunes
- [ ] Identificar propuestas concretas surgidas
- [ ] Vincular con diseño de sistema check-in/check-out

**Participantes:** Andrés Diez, Tatiana Sandoval, Josefina Vigoroux, Andrés Amengual

**Referencias:**
- [Minuta](https://docs.google.com/document/d/1SPwunHF4NnOtXD57mY33I6V9W4vDe03y/edit)

**Etiquetas:** `tipo: gestión`, `tipo: comunidad`, `área: turismo`, `área: seguridad`, `estado: desarrollo`, `prioridad: alta`, `vinculado a CHH`

**Milestone:** M3 — Uso Público y Escalada Sostenible

**Relaciones:** Alimenta #4 (Escalada y Uso Público), Alimenta #12 (Conversatorio escaladores)

---

#### Issue #18 — [REGISTRO] Propuesta Kaya United — redacción y envío

**Contexto:**
El 28/10/2024, Andrés Amengual redactó una propuesta de financiamiento para Kaya United.

**Objetivo:**
Completar, revisar y enviar la propuesta de financiamiento.

**Tareas:**
- [ ] Revisar borrador actual de la propuesta
- [ ] Validar cifras y presupuesto
- [ ] Obtener aprobación institucional para el envío
- [ ] Enviar propuesta
- [ ] Hacer seguimiento de respuesta

**Participantes:** Andrés Amengual

**Referencias:**
- [Documento](https://docs.google.com/document/d/15XMl8C46yBGhJdpcih-_z6FJGyYwojN0Xz0NVGya_qk/edit)

**Etiquetas:** `tipo: gestión`, `estado: desarrollo`, `prioridad: alta`

**Milestone:** M6 — Fundraising y Alianzas Estratégicas

**Relaciones:** Depende de #8 (Estrategia de Financiamiento)

---

#### Issue #19 — [REGISTRO] Entrevistas territoriales — Juan Medrano y Daniel San

**Contexto:**
En octubre 2024 se realizaron dos entrevistas clave para el conocimiento territorial: Juan Medrano en Puelo – Las Hualas (9/10) y Daniel San (17/10). Estas entrevistas construyen la base de historia oral del territorio.

**Objetivo:**
Documentar y preservar el conocimiento territorial recopilado a través de las entrevistas.

**Tareas:**
- [ ] Sistematizar entrevista Juan Medrano en formato estándar
- [ ] Sistematizar entrevista Daniel San en formato estándar
- [ ] Extraer datos geográficos, históricos y sociales mencionados
- [ ] Vincular con mapeo de actores territoriales
- [ ] Identificar temas para entrevistas de profundización

**Participantes:** Andrés Amengual, Andrés Diez

**Referencias:**
- [Entrevista Medrano](https://docs.google.com/document/d/10eSr8lGuov7sNWXomaG7wXiF3-kgYJQ0e7si5YbGuGc/edit)
- [Entrevista Daniel San](https://docs.google.com/document/d/17p6dWhglOu-PIT9Zw_twwGyA8JEdNGLzMfj9sFZwsxw/edit)

**Etiquetas:** `tipo: investigación`, `tipo: territorio`, `área: cultura`, `área: datos`, `estado: desarrollo`, `prioridad: media`

**Milestone:** M7 — Conocimiento Territorial e Investigación

**Relaciones:** Alimenta #9 (Mapeo de Actores)

---

#### Issue #20 — [PROBLEMA] Caso Cayún — obtención de antecedentes judiciales

**Contexto:**
El 28/10/2024, Andrés Diez solicita al abogado Millamán los antecedentes de las acciones judiciales interpuestas por la familia Cayún contra la construcción del camino del Cuerpo Militar del Trabajo en Segundo Corral.

**Objetivo:**
Obtener y documentar los antecedentes judiciales del caso para informar la posición del Círculo Territorial.

**Tareas:**
- [ ] Confirmar recepción de solicitud por abogado Millamán
- [ ] Obtener copia de las acciones judiciales
- [ ] Analizar fundamentos y estado procesal
- [ ] Elaborar informe de situación para el equipo
- [ ] Evaluar opciones de intervención

**Participantes:** Andrés Diez (gestor), Andrés Amengual (análisis legal)

**Etiquetas:** `tipo: legal`, `conflicto activo`, `requiere seguimiento`, `prioridad: alta`

**Milestone:** M5 — Gobernanza Territorial e Institucional

**Relaciones:** Depende de #10 (Epic Caso Cayún), Relacionado con #9 (Mapeo de Actores)

---

#### Issue #21 — [REGISTRO] Charla en Pucón — 8/10/2024

**Contexto:**
Andrés Diez y Tatiana Sandoval participaron en una charla en Pucón, probable espacio de difusión del trabajo territorial de Cochamó ante audiencia externa.

**Objetivo:**
Documentar la participación y los contactos generados.

**Tareas:**
- [ ] Sistematizar contenido de la charla
- [ ] Identificar contactos generados
- [ ] Evaluar oportunidades de colaboración surgidas
- [ ] Documentar retroalimentación recibida

**Participantes:** Andrés Diez, Tatiana Sandoval

**Referencias:**
- [Minuta](https://docs.google.com/document/d/1RihrxHDSrkxmmSOMKuof6nLodHgwk4Lenzpzt9onIgA/edit)

**Etiquetas:** `tipo: gestión`, `tipo: comunidad`, `estado: cerrado`, `prioridad: baja`

**Milestone:** M7 — Conocimiento Territorial e Investigación

---

### MAPA DE RELACIONES ENTRE ISSUES

```
#1 (Educación Ambiental) ←→ #11 (Minutas pendientes)
#2 (Red Comunitaria) ←→ #3 (Chancadora) ←→ #13 (Leticia Contreras)
#2 (Red Comunitaria) ←→ #7 (Estatutos OVC) → #16 (Ejecución reforma)
#4 (Escalada) → #12 (Conv. escaladores) ← #17 (Conv. clubes montaña)
#4 (Escalada) ←→ #5 (Base Camp)
#6 (Áreas Protegidas) ← #14 (Encuentro TNC) + #15 (Encuentro AP)
#8 (Financiamiento) → #18 (Propuesta Kaya)
#9 (Mapeo Actores) ← #19 (Entrevistas) + #13 (Leticia) + #21 (Pucón)
#9 (Mapeo Actores) → #10 (Caso Cayún) → #20 (Antecedentes judiciales)
#11 (Minutas pendientes) → bloquea documentación de #1, #2, #4, #8
```

---

## APÉNDICES

### A. Archivo `labels.json` para GitHub

```json
[
  {"name": "epic", "color": "000000", "description": "Proyecto/epic issue"},
  {"name": "tipo: investigación", "color": "0E8A16", "description": "Levantamiento de información"},
  {"name": "tipo: gestión", "color": "1D76DB", "description": "Coordinación y administración"},
  {"name": "tipo: gobernanza", "color": "5319E7", "description": "Normativa y estructura organizacional"},
  {"name": "tipo: tecnología", "color": "006B75", "description": "Sistemas y datos"},
  {"name": "tipo: territorio", "color": "B60205", "description": "Acciones en terreno"},
  {"name": "tipo: comunidad", "color": "FBCA04", "description": "Vinculación comunitaria"},
  {"name": "tipo: legal", "color": "D93F0B", "description": "Asuntos jurídicos"},
  {"name": "tipo: educación", "color": "C2E0C6", "description": "Talleres y formación"},
  {"name": "estado: idea", "color": "F9D0C4", "description": "Identificado sin análisis"},
  {"name": "estado: análisis", "color": "FEF2C0", "description": "En proceso de diseño"},
  {"name": "estado: desarrollo", "color": "BFD4F2", "description": "En ejecución activa"},
  {"name": "estado: implementación", "color": "0E8A16", "description": "Operando"},
  {"name": "estado: cerrado", "color": "CCCCCC", "description": "Finalizado"},
  {"name": "prioridad: alta", "color": "B60205", "description": "Atención inmediata"},
  {"name": "prioridad: media", "color": "FBCA04", "description": "Importante sin urgencia"},
  {"name": "prioridad: baja", "color": "0E8A16", "description": "Puede esperar"},
  {"name": "área: biodiversidad", "color": "0E8A16", "description": "Flora, fauna, ecosistemas"},
  {"name": "área: turismo", "color": "1D76DB", "description": "Visitantes y uso recreativo"},
  {"name": "área: acceso", "color": "D93F0B", "description": "Caminos y conectividad"},
  {"name": "área: seguridad", "color": "B60205", "description": "Seguridad en montaña"},
  {"name": "área: infraestructura", "color": "006B75", "description": "Instalaciones y equipamiento"},
  {"name": "área: datos", "color": "5319E7", "description": "Información y monitoreo"},
  {"name": "área: agua", "color": "1D76DB", "description": "Recursos hídricos"},
  {"name": "área: cultura", "color": "FBCA04", "description": "Patrimonio y pueblos originarios"},
  {"name": "minuta pendiente", "color": "E4E669", "description": "Sin documentación"},
  {"name": "requiere seguimiento", "color": "D93F0B", "description": "Necesita acción"},
  {"name": "vinculado a CHH", "color": "006B75", "description": "Conexión con Cochamó Hippie Hub"},
  {"name": "conflicto activo", "color": "B60205", "description": "Situación conflictiva en curso"}
]
```

### B. Template para Epic Issues (`.github/ISSUE_TEMPLATE/epic.md`)

```markdown
---
name: Epic — Proyecto
about: Issue para proyectos/iniciativas estratégicas
title: "[EPIC] "
labels: epic
---

## Contexto
<!-- Descripción del contexto y antecedentes -->

## Objetivo
<!-- Qué se busca lograr -->

## Tareas
- [ ] Tarea 1
- [ ] Tarea 2

## Participantes
<!-- Personas involucradas y sus roles -->

## Referencias
<!-- Links a minutas, documentos, otros issues -->

## Relaciones
<!-- Relacionado con #XX / Depende de #XX / Amplía #XX -->
```

### C. Template para Problema (`.github/ISSUE_TEMPLATE/problema.md`)

```markdown
---
name: Problema
about: Situación que requiere solución
title: "[PROBLEMA] "
labels: ""
---

## Contexto
<!-- Descripción de la situación -->

## Objetivo
<!-- Resultado esperado -->

## Tareas
- [ ] Tarea 1
- [ ] Tarea 2

## Participantes

## Referencias

## Relaciones
```

### D. Estadísticas del dataset

| Métrica | Valor |
|---------|-------|
| Total de actividades procesadas | 23 |
| Actividades con minuta documentada | 16 |
| Actividades con minuta pendiente | 6 |
| Actividades sin participante registrado | 1 |
| Participantes únicos identificados | 8 directos + 6 externos |
| Instituciones mencionadas | 6 |
| Programas (milestones) definidos | 8 |
| Epic issues generados | 10 |
| Issues operativos generados | 11 |
| Total de issues | 21 |
| Relaciones mapeadas | 23 |
| Etiquetas diseñadas | 29 |

---

> **Nota**: Este documento es el blueprint del repositorio. Para implementarlo en GitHub, se recomienda:
> 1. Crear el repositorio bajo `Cochamo-Hippie-Hub/CirculoTerritorial`
> 2. Cargar la estructura de carpetas
> 3. Crear las labels usando el archivo `labels.json` y la GitHub CLI
> 4. Crear los milestones en el orden M1–M8
> 5. Crear los issues en orden (#1–#21) para que las referencias cruzadas funcionen
> 6. Descargar las minutas de Google Docs y convertirlas a Markdown en `/docs/minutas/`
