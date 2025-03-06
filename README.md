### **A2.1 Regresión Logística y Validación Cruzada**

### Índice del proyecto
<p><b>Archivo de base de datos: <a href="nissan-dataset.csv">Base de datos</a></b></p>
<p><b>Reporte en formato ipynb: <a href="Salida Binaria Para Precio de Autos Usados.ipynb">Archivo IPYNB</a></b></p>
<p><b>Reporte en formato HTML: <a href="Salida Binaria Para Precio de Autos Usados.html">Archivo HTML</a></b></p>

### Descripción general
<p>Haciendo uso de una base de datos que contiene información de diversos modelos de autos de la marca NISSAN se busca realizar un modelo de regresión logística y que también ayude en la práctica y comprensión de validación cruzada.</p>
<p><b>Objetivo:</b> Realizar un modelo predictivo para la variable precio (que expresa a cuánto se puede revender un carro basado en sus caracteristicas) que describa cómo las varibales numéricas afectarían a esta variable si fuera categórica binaria.</p>

### Caracteristicas de la base de datos
1. id: Unique identifier for each individual.
2. full_name: The complete name of the car owner, formatted as "Last Name, First Name."
3. age: The age of the car owner.
4. gender: The gender of the car owner, categorized as Male, Female, or Non-Binary (amongst others).
5. model: The specific Nissan car model.
6. color: The color of the car owned by the individual.
7. performance: The horsepower of the car, measured in kilometers per hour (km/h), following European standards.
9. km: The total kilometers the car has been driven.
10. condition: The condition of the car, ranging from Old to New, which significantly influences its price.
11. price: The target price of the car, expressed in dollars with two decimal places for precision.
