# Análisis de Campañas Bancarias

## Contexto del Proyecto

### Objetivo

El propósito de este análisis es evaluar el **comportamiento de los clientes** frente a las **campañas bancarias** y descubrir los **factores clave** que influyen en la **aceptación de productos financieros**.

#### Preguntas clave:
- **¿Quién es el cliente más propenso a aceptar la oferta?**
- **¿Qué características de las llamadas influyen en la aceptación?**

---

## 1. Limpieza y Preparación de Datos

Se eliminaron o imputaron los **valores nulos** y se aplicaron **transformaciones** a las **variables numéricas** y **categóricas**.

**Variables del cliente**:  
`age`, `job`, `education`, `marital`, `loan`.

**Variables de las llamadas**:  
`duration`, `campaign`, `previous`, `pdays`, `contact`.

---

## 2. Distribución de Edad de los Clientes que Aceptaron la Oferta

![Distribución de Edad](ruta/a/tu/imagen1.png)

**Análisis**:  
La mayoría de los **clientes que aceptaron la oferta** tienen entre **30 y 40 años**, lo que indica que este grupo está en una etapa **laboral activa** y tiene **más disposición** para aceptar productos financieros.

---

## 3. Tasa de Aceptación de la Oferta por Tipo de Trabajo

![Tasa de Aceptación por Tipo de Trabajo](ruta/a/tu/imagen2.png)

**Análisis**:  
Los **trabajadores operativos (blue-collar)** y **administrativos** son los más **propensos a aceptar** la oferta, ya que tienen mayor **estabilidad laboral**.  
Los **trabajos técnicos** también tienen una **tasa de aceptación considerablemente alta**.

---

## 4. Tasa de Aceptación de la Oferta por Nivel Educativo

![Tasa de Aceptación por Nivel Educativo](ruta/a/tu/imagen3.png)

**Análisis**:  
Los clientes con **educación secundaria** y **universitaria** tienen una **alta tasa de aceptación**. Las **personas con educación básica** (como **`basic.9y`**) tienen una tasa de aceptación moderada, pero no tan alta como los grupos anteriores.

---

## 5. Duración de Llamadas Según Aceptación de la Oferta

![Duración de Llamadas Según Aceptación de la Oferta](ruta/a/tu/imagen4.png)

**Análisis**:  
Las **llamadas exitosas** (`y='yes'`) son generalmente **más largas** que las no exitosas (`y='no'`), lo que sugiere que **más tiempo de conversación** se asocia con una mayor probabilidad de aceptación.

---

## 6. Número de Intentos de Contacto Según Aceptación de la Oferta

![Número de Intentos de Contacto](ruta/a/tu/imagen5.png)

**Análisis**:  
**Menos intentos** de contacto resultan en **mayor efectividad**. Los **clientes que aceptan la oferta** suelen ser contactados con **menos insistencia**.

---

## 7. Tipo de Contacto Según Aceptación de la Oferta

![Tipo de Contacto](ruta/a/tu/imagen6.png)

**Análisis**:  
El **contacto por celular** tiene una **tasa de aceptación más alta** comparado con el contacto por **teléfono fijo**, lo que indica que los clientes están más **disponibles** y **receptivos** al ser contactados por móvil.

---

## 8. Tasa de Aceptación de la Oferta Según Mes

![Mes de Contacto](ruta/a/tu/imagen7.png)

**Análisis**:  
**Mayo y julio** son los meses con una mayor **tasa de aceptación**. **Agosto** muestra una **baja tasa de aceptación**, probablemente debido a factores **estacionales**, como las **vacaciones de verano**.

---

## 9. Conclusiones y Recomendaciones

### Hallazgos Clave:
1. **Clientes de 30–40 años**, con **trabajos estables** y **educación secundaria o universitaria** son los más **propensos a aceptar** la oferta.
2. **Llamadas exitosas** son generalmente **más largas** y se realizan principalmente **por celular**.
3. **Menos intentos de contacto** son más **efectivos**.

### Recomendaciones:
1. **Focalizar las campañas** en **clientes de 30–40 años**, con **trabajos estables** y **educación secundaria o universitaria**.
2. **Priorizar el contacto por celular**, ya que es **más efectivo** que el teléfono fijo.
3. **Reducir el número de intentos de contacto**, manteniendo un máximo de 2–3 intentos.
4. **Aumentar la duración de las llamadas**, ya que las llamadas más largas están asociadas con una mayor tasa de aceptación.

---

## 10. Cierre

Este análisis proporciona una **visión clara del perfil del cliente ideal** y cómo podemos **optimizar las campañas** para aumentar la **eficacia** de las ofertas bancarias. Gracias a estos **hallazgos** podemos tomar **decisiones informadas** para **mejorar las tasas de aceptación**.

---

### **Instrucciones para incluir las imágenes:**

1. **Sube todas las imágenes a tu repositorio de GitHub.**
2. **Copia las URLs de las imágenes** (puedes hacerlo en la vista previa de GitHub).
3. **Reemplaza `ruta/a/tu/imagenX.png`** en cada sección por la **URL de la imagen**.

---

Con este formato de **Markdown**, tu proyecto será **claro, bien estructurado y visualmente atractivo**. Te permitirá **explicar el análisis de manera efectiva**, mostrando tanto los **gráficos** como las **conclusiones** de cada análisis.

Si necesitas algún ajuste o más detalles para agregar, ¡avísame!
