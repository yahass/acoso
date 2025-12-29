# Análisis de Acoso Laboral

## Descripción del Proyecto
Este proyecto tiene como objetivo analizar datos relacionados con el acoso laboral en México utilizando la Encuesta Nacional de Ocupación y Empleo (ENOE) para la población de 15 años y más. El análisis se centrará en identificar tendencias, prevalencia y factores asociados al acoso laboral.

## Fuentes de Datos
- **Encuesta Nacional de Ocupación y Empleo (ENOE)**
  - [Descripción y acceso a los datos](https://www.inegi.org.mx/)
  
## Diccionario de Datos
A continuación se detalla el diccionario de datos utilizado en el análisis:

| Nombre del Campo                          | Longitud | Tipo | Némónico | Catálogo | Rango de Claves                     |
|-------------------------------------------|----------|------|----------|----------|-------------------------------------|
| Número de la localidad                    | 4        | C    | cve_loc  |          | 0001-9998                          |
| Número de municipio según entidad         | 3        | C    | cve_mun  | cve_mun  | 001-575                             |
| Estrato nacional y estatal                | 2        | C    | est      |          | Primer dígito 1-4, Segundo dígito 0-4 |
| ...                                       | ...      | ...  | ...      | ...      | ...                                 |

_(Completa el resto de los campos según lo proporcionado)_

## Preguntas de Investigación
- ¿Cuál es la prevalencia del acoso laboral en diferentes sectores?
- ¿Existen diferencias significativas en la experiencia de acoso laboral según el género y la edad?
- ¿Cómo se relaciona el tipo de entrevista con la denuncia de acoso laboral?

## Proceso de Limpieza y Transformación de Datos
1. **Recopilación de Datos:**
   - Descargar los datos de la ENOE.
   
2. **Limpieza de Datos:**
   - Eliminar duplicados y registros incompletos.
   - Corregir errores de tipeo y formatear variables.

3. **Transformación:**
   - Crear variables derivadas para el análisis del acoso laboral, como tasas de acoso por sector.
   - Categorizar variables relevantes para facilitar la visualización.

## Decisiones de Diseño del Panel
- **Visualizaciones Clave:**
  - Gráficos de barras para comparar incidencia de acoso por sector.
  - Mapas para visualizar geográficamente las tasas de acoso.
  
- **Interactividad:**
  - Incluir filtros por edad, género y tipo de trabajo.

- **Claridad Visual:**
  - Utilizar una paleta de colores coherente y elementos gráficos eficientes para contar la historia de los datos.

## Conclusiones
Este análisis se realizará en un entorno de Looker Studio, permitiendo una visualización clara y efectiva de los problemas asociados al acoso laboral en México.
