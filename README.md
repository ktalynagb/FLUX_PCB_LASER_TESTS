# FLUX PCB Laser Tests

Pruebas de confiabilidad para el proceso de fabricación de PCB mediante corte/grabado láser en **FLUX Solutions Cali**.

## 📋 Descripción

Este repositorio contiene los diseños de PCB utilizados para evaluar la confiabilidad del proceso láser bajo distintas condiciones de fabricación. Los diseños fueron tomados de proyectos open source disponibles en la comunidad y modificados para adaptarlos a los objetivos específicos de estas pruebas, incluyendo variaciones en el ancho de pista y la incorporación del logo de la empresa.

## 🎯 Objetivo

Evaluar el comportamiento y la confiabilidad del proceso de fabricación láser frente a diferentes tipos de montaje y configuraciones de PCB, con el fin de identificar limitaciones, tolerancias y parámetros óptimos de producción.

## 🧪 Diseños incluidos

El repositorio contiene un total de **6 diseños**, agrupados según el tipo de montaje y la configuración de capas:

| # | Diseño | Tipo de montaje | Caras |
|---|--------|------------------|-------|
| 1 | SMD una cara | Superficial (SMD) | 1 cara |
| 2 | SMD una cara | Superficial (SMD) | 1 cara |
| 3 | SMD dos caras | Superficial (SMD) | 2 caras |
| 4 | SMD dos caras | Superficial (SMD) | 2 caras |
| 5 | THT | Through-Hole (THT) | 1-2 caras |
| 6 | THT | Through-Hole (THT) | 1-2 caras |

> Nota: actualizar esta tabla con los nombres definitivos de cada diseño una vez estén organizados en sus carpetas correspondientes.

## ⚙️ Variaciones evaluadas

Cada diseño contempla modificaciones puntuales respecto al original, principalmente:

- **Ancho de pista (track width):** se generaron variantes con distintos anchos para evaluar el límite de resolución del láser.
- **Tipo de montaje:** SMD (una y dos caras) y Through-Hole (THT), para comparar el comportamiento del proceso frente a distintas geometrías de pad y footprint.

## 🏷️ Branding

Todos los diseños incluyen el logotipo de FLUX Solutions integrado en la capa de serigrafía (Silkscreen) como parte de las pruebas de fidelidad de grabado del láser.

## 📁 Estado actual del proyecto

- ✅ Diseños base seleccionados y adaptados
- ✅ Variaciones de ancho de pista definidas
- ✅ Logo de FLUX integrado en los 6 diseños
- ⏳ **Archivos Gerber:** aún no generados — pendientes para la siguiente fase
- ⏳ Fabricación y pruebas físicas: pendiente

## 🗂️ Estructura del repositorio

```
FLUX_PCB_LASER_TESTS/
├── 01_SMD_una_cara/
│   └── (archivos .kicad_pro, .kicad_sch, .kicad_pcb)
├── 02_SMD_dos_caras/
│   └── (archivos .kicad_pro, .kicad_sch, .kicad_pcb)
├── 03_THT/
│   └── (archivos .kicad_pro, .kicad_sch, .kicad_pcb)
├── assets/
│   └── (logo FLUX y recursos gráficos)
└── README.md
```

## 🛠️ Herramientas utilizadas

- **KiCad** — diseño de esquemáticos y PCB
- **Inkscape** — preparación de logo para serigrafía

## 📌 Origen de los diseños

Los diseños base fueron obtenidos de repositorios open source de la comunidad de electrónica y modificados específicamente para este propósito de prueba. Los créditos y enlaces originales se documentarán en cada subcarpeta correspondiente.

## 👤 Autoría / Mantenimiento

Proyecto desarrollado por el equipo de **FLUX Solutions Cali**, en colaboración con Universidad Autónoma de Occidente.

---

*Este repositorio se encuentra en fase de pruebas. Los archivos de fabricación (Gerbers) serán incorporados en una próxima actualización.*
