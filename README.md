
# Proyecto de Analítica: Tendencias de Videos de YouTube en México
Proyecto de Ciencia de Datos: Trending YouTube Video Statistics 

## Objetivo del Proyecto
El objetivo de este proyecto es analizar las tendencias de videos en YouTube en México utilizando un enfoque basado en la metodología **CRISP-DM**.  
Este análisis busca identificar patrones y generar información estratégica que permita a una importante empresa de marketing digital tomar decisiones informadas sobre las preferencias de los usuarios y las tendencias actuales en la plataforma.


## Nombre de los Alumnos Participantes
- **Marcos Aaron Bedia Torres**  - U202118582  
  - Rol: Business Project Sponsor y Data Engineer  
- **Ricardo Martin Tejada Ramirez**  - U202113697   
  - Rol: Data Scientist  
- **Ysela Evelyn Rojas Ruiz**  - U202317656
  - Rol: Data Analyst  


## Breve Descripción del Conjunto de Datos
El conjunto de datos contiene información sobre videos en tendencia en YouTube en México, recopilados a través de la API de la plataforma.  

| **Variable**              | **Descripción**                                      |
|---------------------------|----------------------------------------------------|
| `video_id`                | Identificador único del vídeo                      |
| `trending_date`           | Fecha de cuando el vídeo fue tendencia             |
| `title`                   | Título del vídeo                                   |
| `channel_title`           | Nombre del canal                                   |
| `category_id`             | Identificador único para categoría                 |
| `publish_time`            | Fecha y hora de publicación del vídeo              |
| `tags`                    | Etiquetas del vídeo                                |
| `views`                   | Número de visitas del vídeo                        |
| `likes`                   | Número de likes del vídeo                          |
| `dislikes`                | Número de dislikes del vídeo                       |
| `comment_count`           | Número de comentarios del vídeo                    |
| `thumbnail_link`          | Enlace hacia la miniatura del vídeo                |
| `comments_disabled`       | Indicador para comentarios desactivados            |
| `ratings_disabled`        | Indicador para valorizaciones desactivadas         |
| `video_error_or_removed`  | Indicador si el vídeo fue borrado o tiene un error |
| `description`             | Descripción del vídeo                              |
| `state`                   | Estado geográfico                                  |
| `lat`                     | Latitud espacial                                   |
| `lon`                     | Longitud espacial                                  |
| `geometry`                | Información espacial                               |


## Conclusiones
1. **Adecuación de la Regresión Lineal Múltiple**:
   - La regresión lineal múltiple es adecuada para este análisis, aunque se identificaron oportunidades de mejora.

2. **Mejoras Posibles**:
   - **Incluir más variables predictoras**: Por ejemplo, duración del video, categoría y fecha de publicación.
   - **Usar modelos más complejos**: Transformaciones no lineales (como regresión polinómica) o algoritmos como árboles de decisión para capturar relaciones más complejas.

3. **Interpretación del Modelo**:
   - Los coeficientes del modelo ayudan a identificar qué factores tienen mayor impacto en las vistas.
   - Aunque el modelo tiene una precisión moderada (R² = 0.53), permite identificar tendencias útiles para predecir visitas en función de las métricas disponibles.

4. **Importancia de la Gestión de Outliers**:
   - Dentro de la metodología **CRISP-DM**, la detección y tratamiento de outliers es una decisión crítica. La elección de la técnica para manejarlos afecta significativamente el rendimiento del modelo.


## Licencia de Uso
Este proyecto está bajo la licencia **MIT**, lo que permite su uso, modificación y distribución con atribución adecuada a los autores.  

Para más detalles, consulta el archivo `LICENSE`.


