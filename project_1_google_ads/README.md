# **PROYECTO DE ANÁLISIS Y VISUALIZACIÓN DE GOOGLE ADS**

Bienvenido/a al proyecto de análisis de Google Ads para **DH Marketing**. 
Este documento detalla las fases del proyecto y sus resultados.

---

## **📌 Tabla de Contenidos**

• **Contexto del proyecto**

• **Objetivo del proyecto**

• **Fases del proyecto**  
   * Fase 1. Análisis exploratorio de datos (EDA)  
   * Fase 2. Procesos ETL (Extract, Transform, Load)  
   * Fase 3. Modelado de datos y construcción de relaciones 
   * Fase 4. Análisis y visualización en dashboard  
     * Rendimiento General 
     * Análisis Temporal
     * Perfil de Audiencia
     * Análisis por Canal publicitario 

• **Conclusión del proyecto**  

• **Contacto del equipo técnico** 

---

## **📄 Contexto del proyecto**



## **🎯 Objetivo del proyecto**

---

## **🗂️ Fases del Proyecto**

### **Fase 1. Análisis exploratorio de datos (EDA)**

* Exploración inicial de los datos para identificar patrones, tendencias y anomalías.

### **Fase 2. Procesos ETL (Extract, Transform, Load)**

* Proceso de Extracción, transformación y carga de datos a través de Power Query asegurando la calidad y consistencia necesaria para el análisis.

### **Fase 3. Modelado de datos y construcción de relaciones**

* Creación y relación de las tablas hechos (fact) y dimensiones (dim), facilitando el almacenamiento, acceso  e interacción de los datos.

![BBDD relación tablas](https://github.com/Paulamc1695/powerbi_projects/blob/main/project_1_google_ads/google_ads_relaciones.png)

### **Fase 4. Análisis y visualización en dashboard**


* Visualización de los resultados a través de un dashboard interactivo que permite un fácil acceso y análisis de la información.


#### **1. Rendimiento General**

Analiza el rendimiento global de las campañas publicitarias en términos de interacción (clics e impresiones), resultados obtenidos (conversiones) y costes asociados (gasto total, CPC, CPM y CPV); para comparar la eficacia de cada campaña para identificar las más rentables y optimizar futuras inversiones.

* **Gráficos:**

  * **KPI’s:**

    - Total de clicks

      Objetivo → Medir el volumen total de interacción del público con los anuncios.
      Formato → Número entero porque es un conteo.

    - Total de conversiones

      Objetivo → Mostrar el número total de acciones valiosas logradas (ventas, registros, etc.). Es el resultado final del esfuerzo publicitario.
      Formato →Número entero porque es un conteo.

    - Gasto total

      Objetivo → Indicar cuánto se ha invertido en total en los distintos canales. Permite contrastar con conversiones o CPA para ver si se está gastando bien.
      Formato → Moneda (porque es un coste)

    - Total de impresiones

      Objetivo → Medir cuántas veces se han mostrado los anuncios al público para evaluar el alcance y visibilidad de las campañas.
      Formato → Número entero porque es un conteo.

    - CTR (Click Through Rate)

      Objetivo → Cuántas personas hicieron clic en un anuncio respecto al número de veces que se mostró (impresiones).
      Formato →  Porcentaje porque es una tasa.

    - CPC (Coste por Clic)

      Objetivo → Saber cuánto cuesta, de media, cada clic. Ayuda a evaluar la eficiencia de atraer tráfico a través de un canal.
      Formato → Moneda porque es un coste unitario.

  * **Gráfico Interacción y conversión por campaña**

    Objetivo → Visualizar el alcance (impresiones), la interacción (clics) y los resultados obtenidos (conversiones) de cada campaña individual, para identificar cuáles han tenido mejor rendimiento global.

     - Eje X:
       Nombre de Campaña (Black Friday, Reactivación, Nuevos Clientes, Promo Verano). 
       Formato dato → texto.

     - Eje Y barras apiladas:
       Total clicks
       Formato dato → Número entero porque es un conteo.
       Total Impresiones
       Formato dato → Número entero porque es un conteo.

      - Eje Y línea:
        Total Conversiones
        Formato dato → Número entero porque es un conteo.

  * **Gráfico Distribución del gasto por campaña**

  * **Gráfico Comparativa de costes publicitarios por campaña**

  * **Comparativa de rendimiento por campaña**

* **Filtros disponibles:** año y mes, país, canal publicitario, campaña, canal convsersión.

#### **2. Análisis Temporal**

Analiza la evolución temporal del rendimiento de las campañas publicitarias en términos de clics, gasto, conversiones y eficiencia (CPC y CTR). A través de los distintos gráficos, se identifican patrones estacionales y momentos de mayor o menor efectividad para optimizar la planificación de futuras acciones.

* **Gráficos:**

  * **KPI’s:**

    - Total de clicks

      Objetivo → Medir el volumen total de interacción del público con los anuncios.
      Formato → Número entero porque es un conteo.

    - Total de conversiones

      Objetivo → Mostrar el número total de acciones valiosas logradas (ventas, registros, etc.). Es el resultado final del esfuerzo publicitario.
      Formato →Número entero porque es un conteo.

    - Gasto total

      Objetivo → Indicar cuánto se ha invertido en total en los distintos canales. Permite contrastar con conversiones o CPA para ver si se está gastando bien.
      Formato → Moneda (porque es un coste)

    - Gasto medio

      Objetivo → Mostrar el coste promedio invertido en publicidad durante el periodo analizado, útil para entender la intensidad del gasto diario, semanal o mensual.
      Formato → Moneda (porque es un coste).

    - CTR (Click Through Rate)

      Objetivo → Cuántas personas hicieron clic en un anuncio respecto al número de veces que se mostró (impresiones).
      Formato →  Porcentaje porque es una tasa.

    - CPC (Coste por Clic)

      Objetivo → Saber cuánto cuesta, de media, cada clic. Ayuda a evaluar la eficiencia de atraer tráfico a través de un canal.
      Formato → Moneda porque es un coste unitario.

  * **Gráfico Evolución de clicks por campaña a lo largo del tiempo**

  * **Gráfico Evolución mensual de gasto y conversiones**

  * **Gráfico Evolución mensual del CTR**

* **Filtros disponibles:** año y mes, país, canal publicitario, campaña, canal convsersión.

#### **3. Perfil de Audiencia**

Analiza cómo se comporta la audiencia segmentada por edad, género, país y tipo de dispositivo, identificando los perfiles que generan mayor interacción y conversión. A través de este análisis se optimizan las decisiones estratégicas de segmentación y asignación de presupuesto publicitario en Google Ads.

* **Gráficos:**

  * **KPI’s:**

    - Total de clicks

      Objetivo → Medir el volumen total de interacción del público con los anuncios.
      Formato → Número entero porque es un conteo.

    - Total de conversiones

      Objetivo → Mostrar el número total de acciones valiosas logradas (ventas, registros, etc.). Es el resultado final del esfuerzo publicitario.
      Formato → Número sin decimales (Ej: 1.235) No se necesita porcentaje ni moneda, es un conteo.

    - Gasto total

      Objetivo → Indicar cuánto se ha invertido en total en los distintos canales. Permite contrastar con conversiones o CPA para ver si se está gastando bien.
      Formato → Moneda (porque es un coste).

    - CPC (Coste por Clic)

      Objetivo → Saber cuánto cuesta, de media, cada clic. Ayuda a evaluar la eficiencia de atraer tráfico a través de un canal.
      Formato → Moneda porque es un coste unitario.

  * **Gráfico Gasto publicitario por país con desglose por dispositivo**

  * **Gráfico Tasa de conversión por tipo de dispositivo**

  * **Gráfico Clicks por segmento demográfico: edad y género**

* **Filtros disponibles:** año y mes, país, canal publicitario, campaña, canal convsersión, edad por rango y género.

#### **4. Análisis por Canal publicitario**

Evalúa el rendimiento de cada canal publicitario (Google, Facebook, Instagram, YouTube) en términos de inversión, clics y conversiones; para  identificar qué fuentes generan un mejor retorno, optimizar la asignación de presupuesto y entender la eficiencia de cada canal en la estrategia de Google Ads.

* **Gráficos:**

  * **KPI’s:**

    - CPA (Coste por Adquisición o Coste por Conversión)

      Objetivo → Saber cuánto nos cuesta, de media, conseguir una conversión. Cuanto más bajo, mejor. Es clave para medir la eficiencia del gasto por canal.
      Formato →  Moneda (porque es un coste).

    - Total de conversiones

      Objetivo → Mostrar el número total de acciones valiosas logradas (ventas, registros, etc.). Es el resultado final del esfuerzo publicitario.
      Formato → Número sin decimales (Ej: 1.235) No se necesita porcentaje ni moneda, es un conteo.

    - Gasto total

      Objetivo → Indicar cuánto se ha invertido en total en los distintos canales. Permite contrastar con conversiones o CPA para ver si se está gastando bien.
      Formato → Moneda (porque es un coste).

    - CPC (Coste por Clic)

      Objetivo → Saber cuánto cuesta, de media, cada clic. Ayuda a evaluar la eficiencia de atraer tráfico a través de un canal.
      Formato → Moneda porque es un coste unitario.

  * **Gráfico Rendimiento de campañas por canal publicitario**

  * **Gráfico Conversión total por canal publicitario**

  * **Gráfico Comparativa de rendimiento por canal publicitario**

* **Filtros disponibles:** año y mes, país, canal publicitario, campaña, canal convsersión.


## **📈 Conclusión del proyecto**

Este proyecto proporciona un marco sólido para entender y optimizar las operaciones de **DH Marketing** a través del análisis de datos. La implementación de visualizaciones efectivas en Power BI permite una mejor toma de decisiones estratégicas y operativas.

---

## 📱 **Contacto del equipo técnico**
Si deseas conectar o aprender más sobre este proyecto, no dudes en visitar el perfil de **LinkedIn**: 

[Paula Martínez](https://www.linkedin.com/in/paulamartinezcantero/)

**¡Gracias por explorar este proyecto!**  
Si tienes alguna pregunta o sugerencia, no dudes en contactarnos.