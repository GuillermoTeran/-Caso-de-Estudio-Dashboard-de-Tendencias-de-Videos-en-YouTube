# Caso de Estudio: Dashboard de Tendencias de Videos en YouTube
Descripción del Proyecto
Como analista de videos publicitarios en la agencia Sterling & Draper, era responsable de detectar qué categorías de videos en YouTube marcaban tendencia para enfocar estrategias de mercadotecnia. Las consultas semanales sobre tendencias por parte de mis colegas motivaron la automatización de este proceso mediante la creación de un dashboard interactivo en Tableau Public.

## Objetivos del Proyecto
Identificar categorías de videos en tendencia cada semana.

Visualizar la distribución de estas categorías por país.

Detectar qué contenidos fueron particularmente populares en los Estados Unidos.

Crear un dashboard intuitivo y dinámico para uso diario por parte del equipo de planificación de marketing.

## Fuente de Datos
Archivo: trending_by_time.csv

Ubicación: Base de datos youtube

Estructura de la tabla trending_by_time:

record_id: ID único del registro

region: país o región

trending_date: fecha del evento

category_title: categoría del video

videos_count: número de videos en tendencia

## Frecuencia de Actualización
Datos actualizados cada 24 horas, a la medianoche UTC.

## Usuarios del Dashboard
Usuarios objetivo: gerentes de planificación de campañas publicitarias

Frecuencia de uso esperada: al menos una vez al día

## Contenido y Visualizaciones del Dashboard
Título y descripción del dashboard	Filtro de fecha y hora	Filtro de país
Gráfico "Historial de tendencias": tendencias de videos divididas por tiempo y categoría (valores absolutos, gráfico de área)	✅ Se puede ajustar el período de análisis por fecha/hora	✅ El filtro afecta todos los gráficos
Gráfico "Historial de tendencias" (%): proporción de categorías por fecha (gráfico de área con porcentajes)	✅	✅
Gráfico "Tendencias por país": distribución de tendencias por país (gráfico de pastel con valores relativos)	✅	Aplicable solo si se seleccionan múltiples países
Tabla "Tendencias por país y categoría": categorías y países cruzados, resaltado por valores absolutos	✅	✅ (Celdas resaltadas según intensidad de valores)

## Herramientas Utilizadas
Visualización y dashboard: Tableau Public

Procesamiento de datos previos: Python (Pandas)

Base de datos: PostgreSQL (simulada para el caso local)

Compartición: Publicado en Tableau Public con acceso abierto

## Análisis Realizado con el Dashboard
¿Qué categorías estuvieron más en tendencia?

Las categorías de música y entretenimiento dominaron durante la mayoría de las semanas.

¿Cómo se distribuyeron por país?

En países como India y México, música representó más del 60% de los videos en tendencia.

En Estados Unidos, la categoría Noticias y Política tuvo un aumento notable.

¿Qué categorías fueron especialmente populares en EE. UU.?

Noticias y Política, seguido de Entretenimiento.

En contraste, en Latinoamérica y Asia, Música fue más predominante.

## Insights Clave
Las categorías más virales varían significativamente según la región.

Hay patrones estacionales en ciertas categorías (e.g., más noticias en épocas electorales).

Estados Unidos presenta una diversidad mayor de categorías en comparación con otros países.

## Resultados y Beneficios
Automatización del análisis semanal, eliminando consultas repetitivas.

El dashboard permite segmentar tendencias en tiempo real.

Mejora en la capacidad de planificación de campañas publicitarias orientadas por datos.

https://public.tableau.com/views/Libro1_17212954380800/Dashboard1?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
