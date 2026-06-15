# Análisis de la Educación Superior Universitaria en el Perú — 2023

Este proyecto analiza los datos de matrícula universitaria del Perú correspondientes al año 2023, usando el dataset público de MINEDU ESCALE disponible en Kaggle. El objetivo es identificar patrones en la distribución regional de estudiantes, brechas de género, carreras más demandadas, riesgo académico y modalidades de estudio, entre otros aspectos.

El análisis fue desarrollado de forma individual como proyecto personal de práctica en ciencia de datos aplicada al contexto educativo peruano.

## Contenido del repositorio

```
├── analisis_educacion_superior_peru_2023.ipynb   # Notebook principal con todo el análisis
├── peru_student_enrollment_data_2023.csv          # Dataset fuente
├── Informe_Educacion_Superior_Peru_2023.pdf       # Informe final en PDF
├── graficos/
│   ├── Grafico_01_Estudiantes_por_Departamento.png
│   ├── Grafico_02_Genero_por_Departamento.png
│   ├── Grafico_03_Top_Carreras.png
│   ├── grafico_04_riesgo_departamento.png
│   ├── Grafico_05_Rango_Edad.png
│   ├── Grafico_06_Estatal_vs_Privada.png
│   ├── Grafico_07_Modalidad_Estudio.png
│   ├── Grafico_08_Pago_Matricula.png
│   └── Grafico_09_Lima_vs_Resto.png
└── README.md
```

## Temas analizados

El notebook cubre nueve ejes de análisis:

1. Distribución de estudiantes por departamento
2. Brecha de género por departamento
3. Top 15 carreras más demandadas
4. Riesgo académico por departamento
5. Perfil etario de los estudiantes
6. Instituciones estatales vs privadas
7. Distribución por modalidad de estudio (presencial, virtual, remoto)
8. Comparación de pago de matrícula 2022 vs 2023
9. Lima vs resto del país

## Principales hallazgos

Lima concentra el 54.6% de la matrícula universitaria nacional, con una brecha de 3.3x respecto a Arequipa, la segunda región con más estudiantes. A nivel de género, los hombres superan a las mujeres en un 22.6% a nivel nacional. Derecho es la carrera más demandada sumando sus modalidades presencial y virtual, con 3,724 matriculados. El 35.5% de los estudiantes estudia de forma virtual, lo que confirma la consolidación de esa modalidad. El riesgo académico es más alto en departamentos amazónicos: Loreto lidera con 25.58%. El perfil etario muestra que el 46.1% de los estudiantes tiene 24 años o más, evidenciando una demanda creciente de programas flexibles.

## Tecnologías utilizadas

- Python 3
- Pandas — manipulación y limpieza de datos
- NumPy — operaciones numéricas
- Matplotlib — visualizaciones estáticas

## Cómo ejecutar el proyecto

1. Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/analisis-educacion-superior-peru-2023.git
cd analisis-educacion-superior-peru-2023
```

2. Instala las dependencias necesarias:

```bash
pip install pandas numpy matplotlib
```

3. Abre el notebook:

```bash
jupyter notebook analisis_educacion_superior_peru_2023.ipynb
```

El notebook está estructurado de forma secuencial. Puedes ejecutarlo completo desde el inicio para reproducir todos los gráficos y resultados.

## Fuente de datos

- Dataset: [Peru Student Enrollment Data 2023 — Kaggle](https://www.kaggle.com/)
- Fuente original: MINEDU ESCALE (Estadística de la Calidad Educativa del Ministerio de Educación del Perú)
- Año de referencia: 2023

## Autor

Jean Paul Moncada Nateros  
Carrera: Diseño y Desarrollo de Software  
Certus Instituto Superior Tecnológico  
Lima, Perú — Junio 2026
