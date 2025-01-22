# segundo_Proyecto_Individual

## Análisis de Acceso a Internet en Argentina 🌐

### Introducción  
En este proyecto, analizo datos del Ente Nacional de Comunicaciones (ENACOM) de Argentina sobre accesos a internet, velocidades, tecnologías de conexión y su impacto en la población.

### Selección de las hojas 📊  
He seleccionado las siguientes hojas del archivo original porque considero que son las más relevantes para alcanzar los objetivos planteados:

1. **Acc_vel_loc_sinrangos**  
   - Contiene datos detallados de accesos a internet por localidad y velocidad de conexión.  
   - Es fundamental para analizar desigualdades regionales y la calidad de las conexiones.

2. **Velocidad % por prov**  
   - Presenta la distribución porcentual de las velocidades de conexión por provincia.  
   - Permite identificar patrones y comparar regiones.

3. **Totales Accesos por velocidad**  
   - Resume los accesos totales según la velocidad de conexión.  
   - Sirve para evaluar tendencias en la adopción de velocidades mayores.

4. **Accesos_tecnologia_localidad**  
   - Desglosa los accesos por tipo de tecnología en cada localidad.  
   - Ayuda a estudiar la distribución tecnológica y brechas existentes.

5. **Penetración-hogares / Penetración-población**  
   - Proporcionan datos esenciales sobre el impacto social del acceso a internet.

6. **Ingresos**  
   - Relaciona el crecimiento de los ingresos con los accesos a internet.

### Objetivo 🎯  
Mis objetivos en este proyecto son:
1. Identificar tendencias en el acceso a internet según velocidad, tecnología y región.
2. Analizar desigualdades en el acceso y penetración en diferentes provincias.
3. Evaluar cómo el acceso a internet ha impactado económicamente.

### Análisis de Correlaciones 🔍  
En el análisis de correlaciones, se estudian las relaciones entre las variables numéricas del dataset. A continuación, se visualizan los resultados utilizando un mapa de calor (heatmap) para observar las correlaciones entre las variables de acceso a internet, velocidades y otros indicadores numéricos.

### Estructura del repo

.
├── README.md
├── data
│   ├── Internet.xlsx
│   ├── Portabilidad.xlsx
│   ├── Telefonia_movil.xlsx
│   ├── Television.xlsx
│   ├── mapa_conectividad.xlsx
│   ├── servicios_postales.xlsx
│   └── telefonia_fija.xlsx
├── estructura_proyecto.md
├── notebooks
│   └── ETL.ipynb
└── proyectoIndividual2
    ├── bin
    ├── include
    ├── lib
    ├── pyvenv.cfg
    └── share

8 directories, 11 files

### Librerías utilizadas:
1. **Pandas**: Para la manipulación y análisis de los datos. Nos ayuda a cargar, limpiar, transformar y realizar análisis descriptivos.
2. **Seaborn**: Utilizada para crear visualizaciones estadísticas como el mapa de calor para analizar correlaciones.
3. **Matplotlib**: Usada para la visualización de gráficos, específicamente para mostrar el mapa de calor generado con Seaborn.

### Proceso de limpieza de la data:
1. **Selección de columnas relevantes**: Filtramos las columnas que son numéricas para centrarnos solo en las variables que pueden tener correlación (por ejemplo, accesos a internet, velocidad de conexión).
2. **Eliminación de valores nulos**: Si hay columnas con valores faltantes, se eliminan o se imputa esos valores, dependiendo de la necesidad.
3. **Eliminación de valores atípicos**: Se identifican y eliminan valores que se desvían demasiado de la distribución normal, ya que pueden afectar los análisis estadísticos.
4. **Conversión de tipos de datos**: Aseguramos que las columnas tengan el tipo de dato correcto (por ejemplo, convertir cadenas a fechas o números cuando sea necesario).
5. **Transformación de datos**: Dependiendo del análisis, se puede realizar normalización o estandarización de los datos para obtener mejores resultados en el análisis.

Este proceso ayuda a asegurar que la información que utilizamos para crear gráficos, como los mapas de calor, sea de calidad y coherente.

# Conclusión ✨

El análisis revela tendencias importantes en la adopción de internet y las diferencias entre provincias. Estas métricas son esenciales para identificar áreas de mejora en la infraestructura de internet y cómo esto impacta económicamente en la sociedad. A través de visualizaciones y análisis de correlaciones, podemos obtener una visión más clara de los patrones de acceso a internet en Argentina.