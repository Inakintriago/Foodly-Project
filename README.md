# 🍔 Foodly: Análisis del Comportamiento de Usuarios

## 📝 Contexto
Foodly es una empresa emergente que ofrece productos alimenticios a través de una aplicación móvil. El objetivo de este proyecto es analizar el comportamiento de los usuarios dentro de la aplicación para optimizar el embudo de ventas y evaluar el impacto de un cambio en el diseño de la interfaz (fuentes).

### 🎯 Objetivos
1. **Estudiar el embudo de ventas**: Analizar cómo los usuarios llegan a la etapa de compra, identificar en qué etapas se pierden más usuarios y mejorar la conversión.
2. **Evaluar un test A/A/B**: Medir el impacto de un cambio en el diseño (fuentes) en la interacción de los usuarios.

## 🛠️ Herramientas Utilizadas
- **Python**: Análisis de datos y modelado estadístico.
- **Pandas** y **NumPy**: Limpieza y transformación de datos.
- **Matplotlib** y **Seaborn**: Visualización de patrones y tendencias.
- **SciPy**: Pruebas estadísticas para evaluar el impacto de las diferencias entre grupos.
- **Jupyter Notebook**: Documentación y análisis interactivo.

## 📂 Descripción de los Datos
El dataset contiene registros de eventos de los usuarios en la aplicación. Las columnas principales son:

- **EventName**: Nombre del evento realizado.
- **DeviceIDHash**: Identificador único de usuario.
- **EventTimestamp**: Marca de tiempo del evento.
- **ExpId**: Número de experimento (246 y 247 son los grupos de control, 248 es el grupo de prueba).

## 📊 Análisis de Resultados

### 1. **Preprocesamiento de Datos**:
   - Carga y exploración del dataset.
   - Limpieza de valores ausentes y manejo de tipos de datos.
   - Agregación de columnas de fecha y hora para facilitar el análisis temporal.

### 2. **Análisis del Embudo de Ventas**:
   - Estudio de los eventos registrados y su frecuencia.
   - Cálculo de la proporción de usuarios que realizan cada acción y su avance en el embudo.
   - Identificación de la etapa donde se pierde más usuarios.

### 3. **Análisis del Test A/A/B**:
   - Comparación entre los dos grupos de control (246 y 247) para validar la consistencia de los datos.
   - Evaluación de la diferencia estadística en el comportamiento de los usuarios entre los grupos de control y el grupo de prueba (248).
   - Análisis del impacto de las nuevas fuentes en la conversión de usuarios, comparando los resultados entre grupos.

### 4. **Pruebas de Hipótesis**:
   - Determinación de la significancia estadística para las diferencias entre los grupos de control y el grupo de prueba.
   - Cálculo de p-valores para cada evento clave para validar los resultados.

## 📋 Conclusiones
- **Embudo de Ventas**: Se identificaron etapas críticas donde se pierde una gran cantidad de usuarios. Las mejoras en estas etapas podrían aumentar significativamente la tasa de conversión.
- **Test A/A/B**: No se encontraron diferencias significativas entre los grupos de control, lo que valida la correcta asignación de los usuarios a los grupos. Sin embargo, se observó un pequeño impacto positivo de las nuevas fuentes en la interacción de los usuarios.
- **Decisiones basadas en datos**: Las conclusiones del análisis ayudarán al equipo de diseño y marketing a tomar decisiones informadas sobre los cambios en el diseño de la aplicación.

## 📝 Siguientes Pasos
- Mejorar las etapas del embudo donde se pierden más usuarios.
- Realizar pruebas adicionales con otras modificaciones en el diseño para evaluar su impacto.
- Continuar monitoreando los datos para asegurarse de que los cambios implementados sean efectivos a largo plazo.
