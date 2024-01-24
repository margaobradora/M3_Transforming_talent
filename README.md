# Transformando el Talento: Análisis de Datos para Retener y Potenciar Empleados en ABC Corporation

# Proyecto: Mejora de Retención y Satisfacción de Empleados

En el entorno empresarial altamente competitivo de hoy en día, la toma de decisiones informadas es esencial para el éxito a largo plazo. La retención de empleados y la satisfacción en el trabajo son cuestiones críticas para cualquier organización, ya que afectan directamente a la productividad, la moral y la rentabilidad.

## Descripción del Proyecto

Con el objetivo de reducir la rotación de empleados y mejorar la satisfacción en el trabajo, la empresa ABC Corporation nos ha contratado para desarrollar un proyecto de análisis de datos y experimentación A/B de gran alcance. Nuestra misión es identificar factores clave que influyen en la satisfacción en el trabajo y, en última instancia, en la retención de empleados.

En este proyecto, presentaremos los resultados de nuestro análisis exploratorio de datos, diseñaremos un experimento A/B para probar hipótesis críticas y analizaremos los resultados para proporcionar a ABC Corporation información valiosa que informe sus decisiones estratégicas.

## Acerca de ABC Corporation

**ABC Corporation**, fundada en 1980 en California, es una consultora tecnológica especializada en ofrecer soluciones de inteligencia artificial (IA) y aprendizaje automático (machine learning) a empresas de diversos sectores. Su enfoque principal radica en automatizar y optimizar procesos empresariales mediante tecnologías de vanguardia.

La empresa se distingue por tener un equipo multidisciplinario que abarca expertos en UX/UI, marketing, analistas, científicos de datos y otros campos relevantes. Esta diversidad permite una sinergia única entre conocimientos técnicos especializados y perspectivas variadas, lo que les permite ofrecer soluciones personalizadas adaptadas a las necesidades individuales de cada cliente.

## Último Proyecto Destacado

El último proyecto donde ha estado implicada la empresa ha sido la optimización de procesos de selección de personal. Para ello, la empresa ha desarrollado una plataforma de selección inteligente donde los empleados pueden analizar automáticamente los CV de posibles candidatas, identificar sus habilidades clave y, finalmente, clasificar los candidatos según su idoneidad para determinados roles. Además, han creado un sistema de recomendación para sugerir a los reclutadores los mejores candidatos.

---

### Fase 1: Exploración y Limpieza

#### Exploración Inicial:
Realiza una exploración inicial de los datos para identificar posibles problemas, como valores nulos, atípicos o datos faltantes en las columnas relevantes. Utiliza funciones de Pandas para obtener información sobre la estructura de los datos, la presencia de valores nulos y estadísticas básicas de las columnas involucradas. Une los dos conjuntos de datos de la forma más eficiente.

#### Limpieza de Datos:
Elimina o trata los valores nulos, si los hay, en las columnas clave para asegurar que los datos estén completos. Verifica la consistencia y corrección de los datos para asegurarte de que los datos se presenten de forma coherente. Realiza cualquier ajuste o conversión necesaria en las columnas (por ejemplo, cambiar tipos de datos) para garantizar la adecuación de los datos para el análisis estadístico.

### Fase 2: Visualización

Usando las herramientas de visualización que has aprendido durante este módulo, contesta a las siguientes gráficas usando la mejor gráfica que consideres:

- ¿Cómo se distribuye la cantidad de vuelos reservados por mes durante el año?
- ¿Existe una relación entre la distancia de los vuelos y los puntos acumulados por los clientes?
- ¿Cuál es la distribución de los clientes por provincia o estado?
- ¿Cómo se compara el salario promedio entre los diferentes niveles educativos de los clientes?
- ¿Cuál es la proporción de clientes con diferentes tipos de tarjetas de fidelidad?
- ¿Cómo se distribuyen los clientes según su estado civil y género?

### Fase 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo

#### Objetivo del Ejercicio:

Utilizando un conjunto de datos que hemos compartido, se busca evaluar si existen diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes. Para ello, los pasos que deberás seguir son:

#### Preparación de Datos:

Filtra el conjunto de datos para incluir únicamente las columnas relevantes: 'Flights Booked' y 'Education'.

#### Análisis Descriptivo:

Agrupa los datos por nivel educativo y calcula estadísticas descriptivas básicas (como el promedio, la desviación estándar, los percentiles) del número de vuelos reservados para cada grupo.

#### Prueba Estadística:

Realiza una prueba de A/B testing para determinar si existe una diferencia significativa en el número de vuelos reservados entre los diferentes niveles educativos.