# Alura Store Challenge

## 📌 Descripción

Este proyecto forma parte del **Challenge Alura Store**, un ejercicio de análisis de datos en Python.  
El propósito es ayudar al **Sr. Juan** a decidir **qué tienda vender** de una cadena de cuatro tiendas, basándose en datos de ventas, ingresos, calificaciones de clientes y costos de envío.

El análisis se realizó con Python usando **Pandas** y **Matplotlib**, generando visualizaciones y métricas clave para una decisión informada.

---

## 🛠️ Tecnologías y Dependencias

Requisitos:

- Python 3.x  
- Pandas  
- Matplotlib  
- Jupyter Notebook o Google Colab

Instalación de dependencias (si usas `pip`):

```bash
pip install pandas matplotlib
```

## 🚀 Estructura del Proyecto
```
alura-store-challenge/
├── data/
│ ├── tienda_1.csv
│ ├── tienda_2.csv
│ ├── tienda_3.csv
│ └── tienda_4.csv
├── visualizations/
│ ├── ingresos_tiendas.png
│ ├── ventas_categoria.png
│ └── envio_promedio.png
├── analysis.ipynb
└── README.md
```
---

## 📌 Análisis

El proyecto comprende los siguientes pasos:

### 1. Ingreso total por tienda
- Calcula el total de dinero generado por cada tienda.

### 2. Ventas por categoría
- Cuenta la cantidad de ventas por cada categoría de producto.

### 3. Valoración media de clientes
- Calcula la calificación promedio de clientes por tienda para medir satisfacción.

### 4. Productos más y menos vendidos
- Identifica los productos con mayor y menor cantidad de ventas por tienda.

### 5. Costo promedio de envío
- Calcula el costo promedio de envío para cada tienda.
---
## 📈 Resultados principales
### Ingresos totales:
- Tienda 1: 1,150,880,400
- Tienda 2: 1,116,343,500
- Tienda 3: 1,098,019,600
- Tienda 4: 1,038,375,700

### Valoración media de clientes:
- Tienda 1: 3.98
- Tienda 2: 4.04
- Tienda 3: 4.05
- Tienda 4: 4.00

### Costo promedio de envío (más bajo → más alto):

- Tienda 4: 23,459.46
- Tienda 3: 24,805.68
- Tienda 2: 25,216.24
- Tienda 1: 26,018.61

### Productos destacados:
- Tienda 1: Microondas (más vendido)
- Tienda 2: Iniciando en programación
- Tienda 3: Kit de bancas
- Tienda 4: Cama box

---
## 📝 Conclusión

Luego de evaluar múltiples métricas (ingresos, ventas por categoría, valoraciones, rendimiento de productos y costo de envío), se recomienda que el Sr. Juan venda la Tienda 4, ya que presenta:

- El menor ingreso total
- Desempeño inferior en varias categorías
- Producto menos rentable
- Valoración de clientes promedio
- Aunque tiene el costo de envío más bajo, esto no compensa su menor desempeño general
---
## 📌 Cómo ejecutar

1. Clona el repositorio.
2. Abre el archivo analysis.ipynb en Colab o Jupyter.
3. Asegúrate de tener instaladas las dependencias.
4. Ejecuta cada celda y revisa gráficos y resultados.
5. Consulta la conclusión para tomar decisiones basadas en datos.
---
H