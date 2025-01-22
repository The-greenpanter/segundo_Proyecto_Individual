# segundo_Proyecto_Individual

# Análisis de Acceso a Internet en Argentina

## Introducción  
En este proyecto, analizo datos del Ente Nacional de Comunicaciones (ENACOM) de Argentina sobre accesos a internet, velocidades, tecnologías de conexión y su impacto en la población.  

## Selección de las hojas  
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

## Objetivo  
Mis objetivos en este proyecto son:  
1. Identificar tendencias en el acceso a internet según velocidad, tecnología y región.  
2. Analizar desigualdades en el acceso y penetración en diferentes provincias.  
3. Evaluar cómo el acceso a internet ha impactado económicamente.  

## Estructura del Proyecto  
```plaintext
project-folder/
├── data/
│   ├── Acc_vel_loc_sinrangos.csv
│   ├── Velocidad_%_por_prov.csv
│   ├── Totales_Accesos_por_velocidad.csv
│   ├── Accesos_tecnologia_localidad.csv
│   ├── Penetración-hogares.csv
│   ├── Penetración-población.csv
│   ├── Ingresos.csv
├── notebooks/
│   ├── analysis.ipynb        # Notebook principal del análisis
│   ├── preprocessing.ipynb   # Opcional, preparación de datos
├── src/
│   ├── utils.py              # Funciones auxiliares
│   ├── analysis.py           # Análisis en formato script
├── README.md
├── requirements.txt          # Dependencias
└── .gitignore
