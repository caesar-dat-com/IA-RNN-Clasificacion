# IA-RNN-Clasificacion

## Clasificación de Series de Tiempo con Redes Recurrentes

**Profesores:** Jesús Alfonso López – Jose Luis Paniagua  
**Vence:** 2026-05-08 23:59  
**Estado:** 🟡 En progreso

---

## Enunciado

Clasificación de series de tiempo con redes recurrentes, aplicada a captura de movimientos con aceleración.

### Objetivos

| # | Objetivo | Estado |
|---|----------|--------|
| a) | Contextualizar aplicación de captura de movimientos con aceleración de al menos 5 clases | ⬜ |
| b) | Construir dataset con acelerómetro móvil + Edge Impulse, exportar para Python | ⬜ |
| c) | Entrenar modelo RNN simple | ⬜ |
| d) | Entrenar modelo LSTM | ⬜ |
| e) | Validar y comparar con métricas adecuadas | ⬜ |
| f) | Diagramas de modelos y cálculo de parámetros por capa | ⬜ |

## Entregables

- [ ] Códigos Colab comentados (RNN simple + LSTM)
- [ ] Dataset (Edge Impulse export)
- [ ] Video presentación (máx 20 min)

## Estructura del Proyecto

```
IA-RNN-Clasificacion/
├── README.md           # Este archivo
├── requirements.txt    # Dependencias Python
├── .gitignore
├── data/               # Dataset Edge Impulse
├── notebooks/          # Scripts Python → Colab
├── models/             # Modelos entrenados (.h5)
└── docs/               # Diagramas de arquitectura
```

## Stack

- **TensorFlow/Keras** — Entrenamiento RNN y LSTM
- **Edge Impulse** — Captura y exportación de dataset
- **Scikit-learn** — Métricas de validación
- **Matplotlib** — Visualización
- **Pydot + Graphviz** — Diagramas de modelos