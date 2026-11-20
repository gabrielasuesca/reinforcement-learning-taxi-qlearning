# Proyecto de Reinforcement Learning: Taxi Autónomo con Q-Learning

Proyecto académico de **Introducción a Machine Learning** (Semana 14), desarrollado por Gabriela Suesca Castillo y María Isabel Hernández Bello.

## Descripción

Se implementa un agente de aprendizaje por refuerzo para el entorno Taxi de Gymnasium. El agente aprende mediante **Q-Learning** a recoger un pasajero y llevarlo a su destino en una cuadrícula urbana simplificada. Se compara el desempeño del agente entrenado con una política aleatoria.

## Estructura del repositorio

```text
.
├── notebooks/
│   └── Reinforcement_Learning_Taxi_QLearning.ipynb
├── informe/
│   └── Informe_Reinforcement_Learning_APA7.docx
├── README.md
├── requirements.txt
└── .gitignore
```

## Resultados principales

Resultados obtenidos en la ejecución del notebook:

| Métrica | Agente aleatorio | Q-Learning |
|---|---:|---:|
| Recompensa promedio | -773.19 | 7.92 |
| Pasos promedio | 197.03 | 13.08 |
| Tasa de éxito | 3.60 % | 100 % |

Durante el entrenamiento, en los últimos 1.000 episodios se obtuvo una recompensa promedio de **5.32**, un promedio de **13.86 pasos** y una tasa de éxito del **100 %**. El valor final de epsilon fue **0.05**.

## Cómo ejecutar

### Opción recomendada: Google Colab

1. Descarga o abre el archivo ubicado en `notebooks/`.
2. Entra a Google Colab y selecciona **Archivo → Subir notebook**.
3. Sube `Reinforcement_Learning_Taxi_QLearning.ipynb`.
4. Ejecuta las celdas en orden, desde la primera hasta la última.

No es necesario montar Google Drive para ejecutar el notebook.

### Ejecución local

1. Instala Python 3.10 o una versión compatible con las dependencias.
2. Instala las librerías:

   ```bash
   pip install -r requirements.txt
   ```
3. Abre el notebook con Jupyter Notebook o JupyterLab y ejecuta las celdas en orden.

## Tecnologías utilizadas

- Python
- Gymnasium
- NumPy
- Matplotlib
- Pandas
- Seaborn
- Jupyter Notebook / Google Colab

## Archivos

- **Notebook:** contiene la implementación, entrenamiento, evaluación, comparación y visualizaciones.
- **Informe:** documento académico con metodología, resultados, análisis y conclusiones.

## Autoras

- Gabriela Suesca Castillo
- María Isabel Hernández Bello

**Asignatura:** Introducción a Machine Learning  
**Docente:** Mónica Fonseca  
**Actividad:** Tarea – Reinforcement Learning (Semana 14)

## Referencias

Farama Foundation. (s. f.). *Gymnasium documentation: Taxi*. https://gymnasium.farama.org/

Sutton, R. S., & Barto, A. G. (2018). *Reinforcement learning: An introduction* (2nd ed.). MIT Press.
