# 🚴‍♂️ **BikeBuyer – Data Wrangling & EDA**  

Este repositorio contiene un notebook enfocado en la **limpieza**, **transformación** y **análisis exploratorio de datos (EDA)** del dataset *Bike Buyers*. También incluye un conjunto de preguntas exploratorias orientadas a comprender mejor el perfil de los compradores de bicicletas.

## 📁 **Contenido del Notebook**  

- Carga del dataset y exploración inicial  
- Limpieza profunda de datos (valores faltantes, columnas irrelevantes)  
- Transformación de variables categóricas y derivadas  
- Análisis estadístico y visual de variables clave  
- Respuestas a preguntas orientadas al comportamiento de compra  

## 🎯 **Objetivo del Análisis**  

El objetivo de este notebook es **preparar y explorar el dataset BikeBuyers** para dejarlo en condiciones óptimas para análisis posteriores o modelos de machine learning. Esto incluye:

- Eliminar columnas irrelevantes o con valores nulos excesivos  
- Unificar columnas multilingües y generar nuevas variables  
- Explorar relaciones entre ingreso, hijos, autos y compra de bicicletas  
- Guiar el análisis mediante preguntas clave que ayuden a perfilar a los compradores  

## 🧰 **Tecnologías Utilizadas**  

- Python 3  
- Pandas  
- Seaborn  
- Matplotlib  
- Jupyter Notebook  

## 📁 **Dataset Utilizado**  

- Fuente: Dataset Bike Buyers  
- Formato: Excel
- Columnas originales: 31 (tras limpieza: 13)  
- Variable objetivo: `BikeBuyer` (0 = No compró bicicleta, 1 = Sí compró bicicleta)  

## 📌 **Principales acciones realizadas**  

### 🧹 **Limpieza y Transformación de Datos**  

- Eliminación de columnas con datos irrelevantes o redundantes  
- Unificación de columnas en diferentes idiomas (`Education`, `Occupation`)  
- Cálculo de edad estimada a partir de la fecha de nacimiento  
- Revisión y tratamiento de valores nulos  

### 📊 **Análisis Exploratorio de Datos (EDA)**  

Se analizaron variables clave a través de visualizaciones y estadísticas:

- **Ingreso Anual**: La mayoría se concentra entre $20,000 y $70,000, con una distribución sesgada hacia ingresos más altos.  
- **Total de Hijos**: La mayoría no tiene hijos. A mayor número de hijos, menor frecuencia.  
- **Cantidad de Autos Propios**: Lo más común es tener entre 1 y 2 autos.  
- **Distancia al trabajo**: Predominan distancias cortas (0–1 milla).  

### ❓ **Análisis Dirigido por Preguntas**  

1. **¿Cuál es la edad promedio de los compradores y no compradores?**  
   - Compradores: ~42.4 años | No compradores: ~39.9 años  
   - → Los compradores tienden a ser ligeramente mayores.  

2. **¿Qué relación hay entre ingreso anual y compra de bicicleta?**  
   - No hay diferencia drástica, aunque los ingresos de compradores muestran más variabilidad.  

3. **¿Hay alguna tendencia entre cantidad de hijos y ser comprador?**  
   - Clientes con 0 o 1 hijo son más propensos a comprar bicicletas.  

4. **¿Los compradores tienen más autos que los no compradores?**  
   - En promedio, sí. Podría estar relacionado con mayor poder adquisitivo.  

### ✅ **Conclusiones Clave**  

- El dataset fue limpiado y transformado para análisis futuro o modelado predictivo  
- Se identificaron patrones relevantes: la edad, cantidad de hijos y posesión de autos pueden influir en la decisión de compra  
- Aunque el ingreso no muestra diferencias marcadas, sí lo hacen variables como hijos y autos  
- El análisis revela perfiles potenciales de clientes compradores que pueden ser útiles en campañas dirigidas  

## 🔜 **Próximos Pasos**  

- Escalado de variables y codificación adecuada para modelos de machine learning  
- Entrenamiento de modelos supervisados de clasificación  
- Evaluación de métricas como F1-score, AUC y matriz de confusión  

## 📩 **Contacto**  

Si tienes alguna pregunta o sugerencia, no dudes en contactar a:

- **Nombre:** Roberto Edmundo Eustaquio Jiménez  
- **Email:** [reusjimenez2002@gmail.com](mailto:reusjimenez2002@gmail.com)  
- **GitHub:** [https://github.com/ReusJimenez](https://github.com/ReusJimenez)  
- **LinkedIn:** [https://linkedin.com/in/roberto-eustaquio/](https://linkedin.com/in/roberto-eustaquio/)  

## 📜 **Licencia**  

Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo [LICENSE](./LICENSE) para más información.
