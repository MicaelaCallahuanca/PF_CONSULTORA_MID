# <h1 align=center>**`🏨Millennium Insights Data (MID)🏨`**</h1>

Proyecto de ciencia de datos (Data Science) que analiza y procesa información extraida de las plataformas GOOGLE y YELP,  cuyo  objeto es apoyar los procesos de toma de decisiones, fundamentados en el estudio detallado de las reseñas realizadas por clientes y usuarios de diferentes negocios comerciales. Para tal fin se proyecta la utilización de una pila tecnológica (Tech Stack) que incluye servicios en la nube de alojamiento, limpieza y proceso (Google Cloud Platform), así como aprendizaje automático (Machine Learning), y automatización de flujos de información.


## Rol a desarrollar

Millennium Insights Data (MID) ha sido contratada por la cadena hotelera latinoamericana GHL, como parte integral del equipo estratégico que busca expandir las marcas de GHL hacia los Estados Unidos. Luego de cumplir el cronograma de mesas técnicas de trabajo, GHL y MID acordaron realizar un primer ejercicio de ingeniería informática que cubrirá dos (2) objetivos básicos.


## Contexto


### Sector Hotelero y Turismo en la costa oeste (USA)

La costa oeste de los Estados Unidos es un destino turístico de renombre mundial, conocido por sus impresionantes paisajes naturales, su rica historia y cultura, y su vibrante vida nocturna. El sector hotelero y turístico de la región es un importante motor económico, que genera millones de dólares en ingresos y crea miles de puestos de trabajo.

En los últimos años, el sector hotelero y turístico de la costa oeste ha experimentado un crecimiento positivo. En 2022, la región recibió un récord de 150 millones de visitantes, lo que supuso un aumento del 10% respecto al año anterior. Este crecimiento se debe a una serie de factores, entre los que se incluyen:

- El aumento de la demanda de viajes internacionales
- La creciente popularidad de las vacaciones de naturaleza
- La expansión de las aerolíneas de bajo coste
  
El sector hotelero y turístico de la costa oeste es un sector importante y en crecimiento. El sector seguirá desempeñando un papel importante en la economía de la región en los próximos años. Una de las principales razones del crecimiento del sector hotelero y turístico de la costa oeste es el aumento de la demanda de viajes internacionales. La región es un destino popular para los viajeros de todo el mundo, que acuden a ella atraídos por sus paisajes naturales, su rica historia y cultura, y su vibrante vida nocturna.

El sector hotelero y turístico de la costa oeste también se ha beneficiado de la creciente popularidad de las vacaciones de naturaleza. La región ofrece una amplia gama de actividades al aire libre, como senderismo, ciclismo, surf y pesca. Estas actividades son cada vez más populares entre los viajeros, que buscan experiencias únicas y memorables.


### Sobre la influencia de las reseñas

En la era digital, las reseñas de hoteles son una fuente de información fundamental para los viajeros. Antes de reservar una habitación, la mayoría de los clientes potenciales consultan las opiniones de otros usuarios para conocer sus experiencias y tomar una decisión informada. Las reseñas de hoteles pueden influir en la experiencia del cliente de varias maneras: 

- Pueden ayudar a los viajeros a elegir el hotel adecuado para sus necesidades. Las reseñas pueden proporcionar información sobre la ubicación, las instalaciones, el servicio y el precio del hotel. Esto puede ayudar a los viajeros a encontrar un hotel que satisfaga sus expectativas y presupuesto.

- Las reseñas pueden influir en la satisfacción del cliente. Las reseñas positivas pueden generar expectativas positivas en los clientes, mientras que las reseñas negativas pueden generar expectativas negativas. Esto puede tener un impacto en la satisfacción del cliente con su estancia.

- Las reseñas influyen en la lealtad del cliente. Los clientes que tienen una experiencia positiva con un hotel son más propensos a reservarlo de nuevo en el futuro. Por el contrario, los clientes que tienen una experiencia negativa son menos propensos a reservar el hotel de nuevo.


### La importancia de las reseñas de hoteles para el desempeño del hotel

Las reseñas son una herramienta valiosa para los hoteles ya que pueden utilizar las reseñas para mejorar su servicio y satisfacción del cliente:

- Las reseñas pueden ayudar a los hoteles a identificar áreas de mejora. Las reseñas negativas pueden proporcionar información sobre los problemas que los clientes están experimentando. Los hoteles pueden utilizar esta información para tomar medidas para mejorar su servicio.

- Las reseñas pueden ayudar a los hoteles a promocionarse. Las reseñas positivas pueden atraer nuevos clientes y aumentar las reservas. Los hoteles pueden destacar las reseñas positivas en su sitio web y en las redes sociales.

- Las reseñas pueden ayudar a los hoteles a gestionar su reputación. Las reseñas negativas pueden dañar la reputación de un hotel. Los hoteles pueden responder a las reseñas negativas de manera oportuna y profesional para minimizar el daño a su reputación.


## Objetivos

1. Completar el producto mínimo viable de una solución de ciencia de datos, que permita a los clientes de GHL ingresar una ciudad destino en los Estados Unidos, y realizar consultas para conocer la calificación (ranking) de los hoteles de la localidad, fundamentando el análisis en las reseñas generales que previamente han hecho los visitantes a dichos establecimientos.

2. Agregar una interfase (integrada a la solución descrita en el punto 1), que ofrezca a los clientes de GHL, una vez escogido el hotel , la información y visualización sobre potenciales sitios de interés circundantes bajo cinco (5) categorías principales: parques de atracciones, arte y entretenimiento, servicios financieros, 'shopping', y lugares históricos. 


## Alcance

- El área geográfica cubierta que en principio asumirá el proyecto es la Costa Oeste de los Estados Unidos: California, Oregon, Washington, Nevada y Arizona.
- La temporalidad que en principio ha sido estandarizada para el análisis de la información extraída de las fuentes de datos es entre 2015 y 2023.
- Las escalas que en principio serán utilizadas en la cualificación de los hoteles y sitios de interés es: Excelente, Bueno, Regular, Malo.
   

## Propuesta de KPIs

1. Determinar la satisfacción con la calidad del servicio de los hoteles analizados, midiendo el aumento o la disminución porcentual de aquellas reseñas que son categorizadas como ‘buenas’ por parte de clientes y usuarios de dichos establecimientos. Se sugiere una medición con periodicidad anual como marco temporal del indicador. % satisfacción calidad de servicio = | cantidad reviews 'buenas' año actual | / | cantidad reviews 'buenas' año anterior |

2. Determinar el flujo de visitantes que tienen los estados que conforman la costa oeste de los Estados Unidos, durante las diferentes estaciones del año, midiendo el aumento o la disminución porcentual del total de reseñas realizadas por parte de clientes y usuarios de dichos establecimientos. Se sugiere una medición con periodicidad trimestral como marco temporal del indicador.  % popularidad segun época del año = | número total de reviews trimestre actual | / | número total de reviews trimestre anterior |

3. Determinar el potencial turístico poblacional de la zona aledaña a los hoteles analizados, midiendo el aumento o la disminución porcentual del total de reseñas hechas por parte de clientes y usuarios que visitan establecimientos circundantes categorizados como de interés turístico; parques de atracciones, arte y entretenimiento, servicios financieros, ‘shopping', y lugares históricos. Se sugiere una medición con periodicidad anual como marco temporal del indicador. % potencial turístico = | Sumatoria total reviews por cada categoría año actual | / | Sumatoria total reviews por cada categoría año anterior | 


## Herramientas

- 💻 &nbsp;
  ![Python](https://img.shields.io/badge/-Python-333333?style=flat&logo=python)
  ![Markdown](https://img.shields.io/badge/-Markdown-333333?style=flat&logo=markdown)
- 📚 &nbsp;
  ![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
  ![Numpy](https://img.shields.io/badge/-Numpy-333333?style=flat&logo=numpy)
  ![Matplotlib](https://img.shields.io/badge/-Matplotlib-333333?style=flat&logo=matplotlib)
  ![Seaborn](https://img.shields.io/badge/-Seaborn-333333?style=flat&logo=seaborn)
  ![Scikitlearn](https://img.shields.io/badge/-Scikitlearn-333333?style=flat&logo=scikitlearn)
- 🛢 &nbsp;
  ![BigQuery](https://img.shields.io/badge/-BigQuery-333333?style=flat&logo=bigquery)
  [![Google Cloud Platform](https://img.shields.io/badge/GoogleCloudPlatform-Up-<COLOR>.svg)](https://shields.io/)
- 📊 &nbsp;
  ![Power BI](https://img.shields.io/badge/-Power%20BI-333333?style=flat&logo=powerbi)
- ⚙ &nbsp;
  ![Git](https://img.shields.io/badge/-Git-333333?style=flat&logo=git)
  ![GitHub](https://img.shields.io/badge/-GitHub-333333?style=flat&logo=github)
  ![Jupyter](https://img.shields.io/badge/-Jupyter-333333?style=flat&logo=jupyter)
  ![Colab](https://img.shields.io/badge/-colab-333333?style=flat&logo=colabbadge)
  ![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-333333?style=flat&logo=visual-studio-code&logoColor=007ACC)


## Etapas del proyecto
  

![PF_stages.png](https://github.com/ConsultoraAnalisisDeMercado/PF_CONSULTORA_DATA/raw/main/images/PF_stages.png)


## Áreas de desempeño del equipo 

- Arquitectura de datos --> Mateo, Mica, Jairo

- Ingeniería de datos --> Gerardo, Mateo

- Problemática(s) y línea(s) de negocio --> Micaela, Santiago, Jairo

- Visualización y StoryTelling -->  Micaela, Gerardo, Mateo, Santiago, Jairo