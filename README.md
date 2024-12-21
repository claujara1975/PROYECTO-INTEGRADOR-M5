# PROYECTO INTEGRADOR M5

![Portada del Proyecto](https://github.com/claujara1975/PROYECTO-INTEGRADOR-M5/blob/main/PORTADA.png)

---

## 📖 INTRODUCCIÓN
En el presente informe, se lleva a cabo un análisis exploratorio de un conjunto de datos recopilados en un período de 12 meses, desde el 01/01/99 hasta el 31/12/99, correspondientes a las llamadas gestionadas por el call center de "Anonymous Bank".

---

## 🎯 OBJETIVO GENERAL DEL PROYECTO
Aplicar los conceptos y técnicas aprendidos en el módulo 5 para realizar un análisis exploratorio y descriptivo de un conjunto de datos reales.

Para este proyecto integrador se presentaron tres opciones de dataset: 
- Call Center
- Gaming
- Airbnb

**Elección:** *Call Center*.

---

## 📊 ANÁLISIS EXPLORATORIO Y DESCRIPTIVO DEL CALL CENTER

El objetivo de este análisis es examinar las operaciones del Call Center y proponer mejoras en tres áreas clave:
1. **Eficiencia Operativa:** Identificar y sugerir mejoras operativas para aumentar la eficiencia.
2. **Satisfacción del Cliente:** Asegurar el cumplimiento de los SLA comprometidos y mejorar la satisfacción del cliente.
3. **Herramienta de Gestión y Toma de Decisiones:** Proveer a los managers del Call Center con una herramienta efectiva para la gestión y la toma de decisiones.

---

## 🌟 OBJETIVO DEL PROYECTO
Se propone:

- Definir, construir y presentar un **Dashboard** que permita medir los niveles de calidad de servicio, eficiencia y productividad del Call Center.
- Establecer los **KPIs** adecuados para medir los objetivos propuestos y definir nuevos niveles de SLA.
- Ofrecer estos niveles de servicio a terceros o generar un nuevo servicio Premium para los clientes más importantes del banco.

### ❓ Preguntas Clave
Para orientar el análisis y el diseño del Dashboard, se deben responder las siguientes preguntas:
- ¿Cuál es el nivel de servicio para los clientes prioritarios?
- ¿Proporcionamos un mejor servicio a los clientes prioritarios en comparación con los clientes normales?
- ¿Qué volumen de llamadas atendemos diariamente?
- ¿Cuáles son los cuellos de botella en el servicio? ¿En qué días y bandas horarias se presentan?
- ¿Cómo es la eficiencia y productividad de nuestros agentes?
- ¿Existen clientes recurrentes en el uso del servicio?
- ¿Cuáles son los tipos de servicio más solicitados?
- ¿Podemos estimar la dotación necesaria para cumplir con una calidad de servicio determinada, por ejemplo, mantener un tiempo promedio de espera menor a 60 segundos?

---

## 🗂️ IDENTIFICACIÓN DE DATOS
Se identificaron y descargaron los datos necesarios para el análisis.

### 📁 Archivos Utilizados
- `Call_Center_1999_DataSet.csv`
- Documentación: *Ejercicio Call Center - Descripción del DataSet*

### 🗄️ Descripción del Conjunto de Datos
El conjunto de datos contiene **444,448 filas**, cada una representando una llamada. Estas llamadas se dividen en tres etapas principales:

- **VRU:** Respuesta de voz automatizada que maneja las llamadas antes de ser atendidas por un agente.
- **Q:** Cola de espera para que las llamadas sean atendidas por un agente.
- **SER:** Servicio proporcionado por un agente del Call Center.

Se excluyen las llamadas con resultado *"PHANTOM"* y aquellas donde el tiempo en VRU era negativo, reduciendo el conjunto de datos a **440,517 filas**.

### 🗃️ Tablas Principales
1. **Calendar:** Gestión de fechas para análisis temporal.
2. **Outcome:** Clasificación de resultados (Agent, Hang, Phantom).
3. **Priority:** Niveles de prioridad de llamadas (Regular, Alta Prioridad).
4. **Type:** Tipos de servicio solicitados (PS, PE, IN, NE, etc.).
5. **CallCenter:** Tabla principal con los atributos necesarios para el análisis.

---

## 🔄 ETL - LIMPIEZA, TRANSFORMACIÓN Y CARGA DE DATOS

En esta fase se realizó un análisis exploratorio y descriptivo utilizando herramientas como Power BI y técnicas estadísticas. 

- **Power Query:** Limpieza y transformación de los datos.
- **DAX:** Cálculo de medidas necesarias para los KPIs.
- **Modelo Estrella:** Creación de tablas de soporte y dimensiones para el análisis.

---

## 📞 ANÁLISIS GENERAL DE LLAMADAS

### 📌 Resumen:
- Total de llamadas: **440,517 al año**
- Clientes de Alta Prioridad: **31%**
- Clientes Regulares: **69%**
- Promedio de llamadas diarias: **1,200**

### 📈 Distribución de Tipos de Servicio
- **Actividad Regular:** 304,668 llamadas
- **Clientes Potenciales:** 135,849 llamadas

### ⏱️ Tiempos de Espera en Cola
- Clientes Regulares: **46 segundos** promedio
- Clientes de Alta Prioridad: **87 segundos** promedio

---

## 🏆 CONCLUSIONES
El Call Center de Anonymous Bank presenta ineficiencias en la atención a clientes de Alta Prioridad debido a:

- Problemas en la configuración del sistema.
- Dotación insuficiente de personal.

**Propuestas:**
- Mejorar la asignación de clientes a las colas.
- Aumentar la dotación de agentes durante las horas pico.

---

## 📂 Referencia
Para acceder al trabajo completo y a todos los detalles del análisis, visita la siguiente URL:
[📂 Trabajo Completo](https://drive.google.com/drive/folders/13yS0WFrS5dTh1EBqw5q33pJONhvK1zGJ)
