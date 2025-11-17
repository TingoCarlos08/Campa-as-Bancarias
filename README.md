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

