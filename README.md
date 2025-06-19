# 📈 Caso de Estudio: Dashboard de Tendencias de Videos en YouTube

## 🇪🇸 Español

### Descripción del proyecto

Como analista de videos publicitarios en la agencia Sterling & Draper, era responsable de detectar qué categorías de videos en YouTube marcaban tendencia para enfocar estrategias de mercadotecnia. Las consultas semanales sobre tendencias por parte de mis colegas motivaron la automatización de este proceso mediante la creación de un dashboard interactivo en Tableau Public.

### Objetivos del proyecto

- Identificar categorías de videos en tendencia cada semana.
- Visualizar la distribución de estas categorías por país.
- Detectar qué contenidos fueron particularmente populares en los Estados Unidos.
- Crear un dashboard intuitivo y dinámico para uso diario por parte del equipo de planificación de marketing.

### Fuente de datos

- **Archivo:** `trending_by_time.csv`
- **Ubicación:** Base de datos YouTube

**Estructura de la tabla:**

- `record_id`: ID único del registro  
- `region`: país o región  
- `trending_date`: fecha del evento  
- `category_title`: categoría del video  
- `videos_count`: número de videos en tendencia  

### Frecuencia de actualización

- Datos actualizados cada 24 horas, a la medianoche UTC.

### Usuarios del dashboard

- **Usuarios objetivo:** gerentes de planificación de campañas publicitarias  
- **Frecuencia de uso esperada:** al menos una vez al día  

### Contenido y visualizaciones del dashboard

| Visualización                                       | Filtro de fecha/hora | Filtro de país |
|-----------------------------------------------------|----------------------|----------------|
| Historial de tendencias (valores absolutos)         | ✅                   | ✅             |
| Historial de tendencias (%)                         | ✅                   | ✅             |
| Tendencias por país (gráfico de pastel)             | ✅                   | ✅ (si hay múltiples países) |
| Tendencias por país y categoría (tabla)             | ✅                   | ✅ (con celdas resaltadas)  |

### Herramientas utilizadas

- Tableau Public (visualización y dashboard)
- Python (pandas) para el procesamiento previo de datos
- PostgreSQL (simulado localmente)
- Publicado con acceso abierto en Tableau Public

🔗 [Ver Dashboard en Tableau Public](https://public.tableau.com/views/Libro1_17212954380800/Dashboard1?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### Análisis realizado con el dashboard

**¿Qué categorías estuvieron más en tendencia?**  
- Música y entretenimiento dominaron durante la mayoría de las semanas.

**¿Cómo se distribuyeron por país?**  
- En India y México, música representó más del 60% de los videos en tendencia.  
- En EE. UU., la categoría Noticias y Política creció notablemente.

**¿Qué categorías fueron especialmente populares en EE. UU.?**  
- Noticias y Política, seguido de Entretenimiento.  
- En Latinoamérica y Asia, la Música predominó.

### Insights clave

- Las categorías más virales varían significativamente por región.
- Hay patrones estacionales en ciertas categorías (e.g., más noticias en épocas electorales).
- EE. UU. presenta mayor diversidad de categorías comparado con otros países.

### Resultados y beneficios

- Automatización del análisis semanal, eliminando consultas repetitivas.
- Segmentación de tendencias en tiempo real.
- Mejora en la planificación de campañas publicitarias orientadas por datos.

---

# 📈 Case Study: YouTube Video Trends Dashboard

## 🇺🇸 English

### Project description

As an advertising video analyst at Sterling & Draper, I was responsible for identifying trending video categories on YouTube to inform marketing strategies. Weekly requests from colleagues motivated me to automate the process by building an interactive dashboard in Tableau Public.

### Project objectives

- Identify trending video categories each week.
- Visualize the distribution of these categories by country.
- Detect which content was particularly popular in the United States.
- Create an intuitive, dynamic dashboard for daily use by the marketing planning team.

### Data source

- **File:** `trending_by_time.csv`  
- **Location:** YouTube database

**Table structure:**

- `record_id`: Unique record ID  
- `region`: Country or region  
- `trending_date`: Event date  
- `category_title`: Video category  
- `videos_count`: Number of trending videos  

### Update frequency

- Data updated every 24 hours at midnight UTC.

### Dashboard users

- **Target users:** campaign planning managers  
- **Expected use frequency:** at least once a day  

### Dashboard content and visualizations

| Visualization                                       | Date/Time Filter | Country Filter |
|-----------------------------------------------------|------------------|----------------|
| Trend History (absolute values, area chart)         | ✅               | ✅             |
| Trend History (%) (proportional area chart)         | ✅               | ✅             |
| Trends by Country (pie chart)                       | ✅               | ✅ (if multiple countries) |
| Trends by Country & Category (highlighted table)    | ✅               | ✅ (cell intensity shading) |

### Tools used

- Tableau Public (dashboard & visualization)
- Python (pandas) for preprocessing
- PostgreSQL (simulated locally)
- Shared publicly via Tableau Public

🔗 [View Dashboard on Tableau Public](https://public.tableau.com/views/Libro1_17212954380800/Dashboard1?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### Analysis performed with the dashboard

**Which categories were most popular?**  
- Music and entertainment dominated most weeks.

**How were they distributed by country?**  
- In India and Mexico, music made up over 60% of trending videos.  
- In the U.S., News and Politics showed notable growth.

**Which categories were especially popular in the U.S.?**  
- News and Politics, followed by Entertainment.  
- Music dominated in Latin America and Asia.

### Key insights

- Trending categories vary significantly by region.
- There are seasonal trends (e.g., more news during elections).
- The U.S. shows more diversity in category trends than other countries.

### Results and benefits

- Weekly analysis automated, removing repetitive queries.
- Real-time trend segmentation.
- Improved campaign planning through data-driven insights.


















