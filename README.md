[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/weKLDxXt)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=21200713&assignment_repo_type=AssignmentRepo)
# 🌿 Proyecto 4 – Análisis de Condicionales en Python (JupyterLite)

Este proyecto forma parte del módulo de programación aplicada al análisis ambiental. 
El objetivo es **aplicar condicionales (`if`, `elif`, `else`) y herramientas de pandas** para clasificar la calidad del agua a partir de variables medidas en **10 sitios reales de Cundinamarca**.

## 🧩 Datos de referencia
Archivo base: `data/muestras_calidad_agua.csv`

| sitio | pH | oxígeno (mg/L) | temperatura (°C) |
|:---------------------------|:--:|:---------------:|:----------------:|
| Río Subachoque | 7.2 | 7.8 | 18.5 |
| Quebrada Honda (Facatativá) | 6.3 | 6.2 | 19.4 |
| Río Botello (Madrid) | 6.8 | 5.9 | 22.7 |
| Afluente San José (El Rosal) | 7.9 | 8.3 | 20.1 |
| Río Villeta | 8.7 | 6.1 | 28.3 |
| Quebrada Cune (San Francisco) | 6.0 | 4.5 | 25.2 |
| Río Tobia (Nocaima) | 7.4 | 5.2 | 26.9 |
| Quebrada Negra (La Vega) | 7.6 | 7.0 | 24.4 |
| Río Bahamón (Sasaima) | 8.1 | 6.7 | 27.6 |
| Río Guayuriba (La Mesa) | 5.9 | 4.8 | 30.5 |

**Notas de interpretación:** pH 6.5–8.5 ≈ neutro; O2 < 5 mg/L ≈ posible estrés; temperaturas altas reducen solubilidad del oxígeno.

## 📁 Estructura
```
4_condicionales/
├── data/
│   └── muestras_calidad_agua.csv
├── notebooks/
│   ├── 0_ejemplo_clase_condicionales.ipynb
│   ├── reto1_temperatura.ipynb
│   ├── reto2_ph.ipynb
│   ├── reto3_oxigeno.ipynb
│   └── reto4_integracion.ipynb
└── jupyter-lite.json
```

## 🚀 Usar en línea (JupyterLite + GitHub Pages)
1) Sube esta carpeta a un repositorio público llamado `4_condicionales`.
2) En **Settings → Pages**, elige **GitHub Actions (Deploy JupyterLite site)** como *Source*.
3) Abre: `https://TU_USUARIO.github.io/4_condicionales/` y navega a `notebooks/`.

## 🎯 Roles por grupo (4 estudiantes)
| Notebook | Descripción | Responsable |
|-----------|-------------|-------------|
| `0_ejemplo_clase_condicionales.ipynb` | Ejemplo completo de la clase | Todos |
| `reto1_temperatura.ipynb` | Clasificación térmica y riesgo | Estudiante 1 |
| `reto2_ph.ipynb` | Evaluación de pH y alerta química | Estudiante 2 |
| `reto3_oxigeno.ipynb` | Análisis biológico por oxígeno | Estudiante 3 |
| `reto4_integracion.ipynb` | Diagnóstico final integrando variables | Estudiante 4 |

**Entrega:** cada estudiante descarga su notebook (**File → Download**) y lo entrega por Moodle o lo sube a un fork.

---
**Elaborado por:**  
**M. Sc. Diego Ramírez** — *Universidad de Cundinamarca*
