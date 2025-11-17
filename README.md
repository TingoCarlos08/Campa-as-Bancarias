# Análisis de Campañas Bancarias
## Contexto del Proyecto

El objetivo principal de este análisis es **evaluar el comportamiento de los clientes** frente a las **campañas bancarias** y descubrir los **factores clave** que influyen en la **aceptación de productos financieros**. A través del análisis de datos, buscamos identificar patrones y características específicas de los clientes que los hacen más **propensos a aceptar una oferta bancaria**, y también comprender cómo ciertos **aspectos de las llamadas** (como duración, tipo de contacto, número de intentos) afectan directamente la **probabilidad de aceptación**.

### Preguntas clave:
- **¿Quién es el cliente más propenso a aceptar la oferta?**
- **¿Qué características de las llamadas influyen en la aceptación?**

A continuación, se detalla el análisis realizado para responder a estas preguntas y optimizar las futuras campañas.

![Contexto del Proyecto](/Imagenes/contexto.png)

## ¿Qué hay en el dataset?

El dataset proporcionado contiene información sobre las **campañas bancarias**, con el objetivo de analizar el comportamiento de los clientes y su disposición para aceptar ofertas. Las características más relevantes del dataset son:

- **Retroalimentación de la campaña** realizada por el banco.
- **41,188 registros** y **20 columnas** que incluyen datos como: tipo de trabajo, nivel educativo, duración de la llamada, entre otras.
- El dataset no tiene **datos duplicados**.
- Los **valores nulos son bajos**, lo que facilita el análisis sin necesidad de una imputación extensa.

### Número de valores nulos por columna

A continuación, se muestra la distribución de **valores nulos** en cada columna del dataset.

![Número de Valores Nulos por Columna](/Imagenes/Dataset.png)

## Limpieza y Preparación de Datos

En este paso, se **eliminaron o imputaron los valores nulos** en el dataset y se aplicaron **transformaciones** tanto a las **variables numéricas** como a las **categóricas** para preparar los datos para el análisis.

### Variables del cliente:
- **edad**, **trabajo**, **educación**, **estado civil**

### Variables de las llamadas:
- **duración**, **número de intentos**, **contactos previos**, **tipo de contacto**

![Limpieza y Preparación de Datos](/Imagenes/Limpieza.png)

## Perfil del Cliente que Acepta la Oferta

El análisis se enfoca en identificar las **características demográficas** y **laborales** de los clientes que tienen mayor **probabilidad de aceptar la oferta**. A través de este análisis, buscamos responder a las siguientes preguntas clave:

### Preguntas clave:
- **¿Quiénes son los clientes más propensos a aceptar la oferta?**
    - Analizamos factores como **edad**, **tipo de trabajo** y **nivel educativo** para entender qué características hacen que un cliente sea más propenso a aceptar.
- **¿Qué factores influyen en la decisión?**
    - Evaluamos cómo la **duración de las llamadas**, el **número de intentos** y el **canal de contacto** (teléfono fijo vs celular) impactan la **aceptación**.

![Perfil del Cliente que Acepta la Oferta](/Imagenes/analisis_cliente.png)

## Tasa de Aceptación por Edad

El gráfico muestra la distribución de edad de los **clientes que aceptaron la oferta** (`y='yes'`). Como se puede observar, los clientes entre **30 y 35 años** tienen la **mayor tasa de aceptación**, lo que sugiere que este grupo es el más **dispuesto a considerar productos financieros**.

### ¿Hay un rango de edad que tiene mayor aceptación?
- Los **clientes de 30 a 35 años** tienen la **mayor tasa de aceptación**.
- A partir de los **50 años**, la tasa de aceptación **disminuye**.
- Este grupo tiene **más probabilidades** de estar en una **etapa laboral activa**.
- Son **más dispuestos a considerar productos financieros**.

![Tasa de Aceptación por Edad](/Imagenes/imagen1.png)

## Tasa de Aceptación por Tipo de Trabajo

El gráfico muestra la tasa de aceptación de la oferta según el **tipo de trabajo** de los clientes. Los **trabajadores operativos (blue-collar)** y **administrativos** tienen la **mayor tasa de aceptación**. Esto sugiere que los clientes en estos sectores son los más **dispuestos a aceptar productos financieros** debido a su **estabilidad laboral**.

### ¿Qué tipos de trabajo tienen más éxito?
- **blue-collar** (trabajadores operativos) y **administrativos** tienen la **mayor tasa de aceptación**.
- Los **trabajos técnicos** también muestran una tasa de aceptación **considerablemente alta**.
- Los **sectores más estables** como **administrativos** y **técnicos** tienen **mayor disponibilidad** y capacidad para **invertir en productos bancarios**.
- Los **trabajos menos estables** o con **menos ingresos** (como **estudiantes** o **desempleados**) tienden a tener una **tasa de aceptación más baja**.

![Tasa de Aceptación por Tipo de Trabajo](/Imagenes/imagen2.png)

## Tasa de Aceptación por Nivel Educativo

El gráfico muestra la tasa de aceptación de la oferta según el **nivel educativo** de los clientes. Los **clientes con educación secundaria** y **universitaria** son los más **propensos a aceptar** la oferta, lo que sugiere que estos grupos tienen **mayor capacidad** para entender y valorar los productos financieros.

### ¿Qué nivel educativo tiene más aceptación?
- **Clientes con educación secundaria** y **universitaria** son los más **propensos a aceptar** la oferta.
- Los **clientes con educación básica** también tienen una **alta tasa de aceptación**, aunque no tan alta como los grupos anteriores.
- La **educación** juega un papel importante en la **aceptación** de la oferta.

![Tasa de Aceptación por Nivel Educativo](/Imagenes//imagen3.png)

## Características de las Llamadas Exitosas

Este análisis se enfoca en identificar las **características clave** de las **llamadas** que tienen **mayor probabilidad de éxito**. Las principales variables analizadas incluyen la **duración de la llamada**, el **número de intentos** y el **tipo de contacto**.

### Preguntas clave:
- **¿Qué características de las llamadas tienen mayor probabilidad de éxito?**
    - Las **llamadas más largas** suelen ser más exitosas, ya que indican mayor **interés** y **compromiso** del cliente.
- **¿Influye la duración de la llamada, el número de intentos o el tipo de contacto?**
    - **Más intentos** y una **mayor duración de las llamadas** están generalmente asociadas con un mayor **interés del cliente**, lo que aumenta la **probabilidad de aceptación**.

![Características de las Llamadas Exitosas](/Imagenes/analisis_llamada.png)


## Duración de Llamada

Este gráfico muestra la **duración promedio de las llamadas** según la **aceptación de la oferta**. Los clientes que **aceptan la oferta** (`y='yes'`) tienden a tener **llamadas más largas**.

### ¿Qué nos indica la duración de la llamada?
- **Clientes que aceptan la oferta** tienden a tener **llamadas más largas**, lo que puede reflejar un **mayor interés** y **compromiso** por parte del cliente.
- Las **llamadas más largas** podrían indicar un **mayor interés** y **compromiso** del cliente, lo que **aumenta la probabilidad de aceptación**.
- Las **llamadas breves** pueden reflejar un **interés bajo** o **pocos convencidos** de la oferta.

![Duración de Llamada Según Aceptación](/Imagenes/imagen4.png)

## Número de Intentos de Contacto

El gráfico muestra la relación entre el **número de intentos de contacto** y la **duración de las llamadas**. Se observa una **relación positiva**: a mayor número de intentos, **mayor duración de la llamada**.

### ¿Qué nos indica esto?
- Las **llamadas exitosas** (`y='yes'`) suelen tener **más intentos** y **mayor duración**, lo que sugiere que los **clientes interesados** pasan más tiempo en la conversación.
- Por otro lado, **menos intentos** pueden ser **más efectivos**, ya que las **llamadas rápidas** a menudo son **rechazadas**.

![Relación entre Número de Intentos y Duración de la Llamada](/Imagenes/imagen5.png)

## Hallazgos

### Edad y Tipo de Trabajo
- **Clientes de 30 a 40 años**, con **trabajos estables**, son más propensos a **aceptar la oferta**.
- Los **más jóvenes** (20-30 años) también muestran **interés**, pero su tasa de aceptación es más baja debido a una **menor estabilidad laboral**.

### Nivel Educativo
- **Clientes con educación secundaria y universitaria** tienen una **alta probabilidad de aceptar** la oferta debido a su **mejor capacidad para entender y valorar los productos financieros**.
![Hallazgos1](/Imagenes/Hallazgo1.png)

## Hallazgos

### Duración de la Llamada
- **Las llamadas exitosas** suelen ser **más largas**, lo que indica que los **clientes comprometidos** tienden a dedicar más tiempo al contacto, mostrando un **mayor interés** en la oferta.
### Número de Intentos de Contacto
- **Menos intentos de contacto** tienden a ser **más efectivos**. Los **intentos excesivos** no aumentan la aceptación y **pueden hacer la campaña menos eficiente**.
### Tipo de Contacto
- **El contacto por celular** tiene una **tasa de aceptación más alta** en comparación con el teléfono fijo, ya que los clientes son **más receptivos** en su móvil.
![Hallazgos1](/Imagenes/Hallazgo2.png)

## ¿Qué puede hacer el banco?

El análisis realizado permite al banco **optimizar sus campañas** al conocer mejor el **perfil del cliente** y los **factores que afectan la aceptación de la oferta**. Basado en los **hallazgos** obtenidos, el banco puede tomar decisiones informadas sobre cómo **segmentar sus clientes**, mejorar la **calidad del contacto** y **focalizar sus esfuerzos** en los clientes más **dispuestos a aceptar la oferta**.

## Recomendaciones

### Dirigir la campaña a clientes de 30–40 años, con trabajos estables
- **Son los que muestran mayor tasa de aceptación** y **mayor interés real** en el producto. Este grupo es más **propenso a aceptar la oferta** debido a su **estabilidad laboral**.

### Priorizar clientes con educación secundaria o universitaria
- **Más propensos a aceptar la oferta** y suelen tener **mayor comprensión** de los productos financieros, lo que aumenta la **probabilidad de aceptación**.
![Recomendaciones](/Imagenes/recomendaciones1.png)

### Reducir el número de intentos

- **Reducir recursos en llamadas por teléfono fijo**, ya que son **mucho menos efectivas** en comparación con el **contacto por celular**. La **calidad de la llamada** es más importante que la **cantidad de intentos**.

### Aumentar la calidad de la llamada

- **Capacitar a los asesores** para **mantener conversaciones más efectivas y detalladas** sin **prolongarlas innecesariamente**, lo que aumenta la **probabilidad de aceptación** sin generar **saturación**.

![Recomendaciones](/Imagenes/recomendaciones2.png)

## Conclusion
El dataset está en buen estado, no tiene duplicados, casi no hay nulos y los outliers se explican por el comportamiento normal de las campañas. Las gráficas muestran patrones claros en edad, tipo de trabajo y duración de llamadas, lo que ayuda a entender mejor el perfil de los clientes y cómo responden a las ofertas del banco. La campaña funciona mejor con clientes entre 30 y 40 años, con trabajos estables y educación media o alta. Además las llamadas más largas hechas por celular y con pocos intentos, tienen más probabilidades de terminar en un “sí”. En conjunto, estos factores ayudan a definir con claridad a qué tipo de cliente conviene dirigir la campaña y cómo hacerlo de forma más efectiva.
