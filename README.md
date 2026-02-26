# Data Science Challenge - Alura Latam: Análisis de Ventas de Sucursales


## Descripción del Proyecto
Este proyecto es la solución al **Challenge 1 de Data Science de Alura Latam**. Consiste en la ingesta, limpieza y Análisis Exploratorio de Datos (EDA) del historial de ventas de cuatro sucursales de una empresa de retail. 

El objetivo de negocio es evaluar el rendimiento operativo, logístico y financiero de cada tienda para proporcionar una recomendación basada en datos empíricos al dueño (Sr. Juan) sobre **qué sucursal debe ser vendida o desinvertida** y cuál debe ser priorizada para maximizar la rentabilidad global.

## Objetivos del Análisis
- **Limpieza y consolidación:** Unir 4 bases de datos (archivos CSV) provenientes de un repositorio remoto.
- **Métricas Financieras:** Calcular y comparar los ingresos totales por tienda.
- **Rendimiento de Productos:** Identificar los productos y categorías más y menos vendidos.
- **Satisfacción y Logística:** Analizar la relación entre la calificación de los clientes y los costos de envío.
- **Análisis Geográfico (Extra):** Mapear la distribución de las ventas en el territorio utilizando coordenadas (latitud y longitud).

## Tecnologías Utilizadas
* **Python 3**
* **Pandas:** Manipulación, agrupación y limpieza de datos.
* **Matplotlib / Seaborn:** Creación de visualizaciones estáticas (gráficos de barras, pastel y dispersión).

## Cómo ejecutar el proyecto

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)

2. Asegúrate de tener instaladas las dependencias necesarias. Puedes instalarlas ejecutando:
  
  ```bash
  pip install pandas matplotlib seaborn


## Resultados Clave (Insights)
El Motor Financiero: La Tienda 1 lidera indiscutiblemente la facturación global con más de $1.15 mil millones en ingresos.

El Eslabón Débil: La Tienda 4 presenta los ingresos más bajos ($1.03 mil millones), a pesar de contar con los costos de envío más económicos para el cliente.

Área de Oportunidad: Paradójicamente, la Tienda 1 (la que más vende) posee la calificación de satisfacción del cliente más baja (3.98/5) y los envíos más caros, lo que representa un riesgo de retención a largo plazo.

## Conclusión y Recomendación
La recomendación analítica es vender la Tienda 4 debido a su incapacidad de apalancar sus bajos costos logísticos para generar un volumen de ingresos competitivo. Los recursos obtenidos deben reinvertirse en la Tienda 1 para optimizar urgentemente su cadena de distribución y atención al cliente, protegiendo así la principal fuente de ingresos de la compañía.
