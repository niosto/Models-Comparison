# Introducción
Este proyecto utiliza el dataset de Alzheimer disponible en Kaggle, el cual contiene información clínica, demográfica y de estilo de vida de pacientes.  
El objetivo es aplicar técnicas de Machine Learning y Deep Learning para predecir el diagnóstico del paciente a partir de sus características.  

### Integrantes ###

- Emanuel Quintero
- Nicolas Ospina
- Martin Valencia

---

### Modelos ###

- KNN
- Random Forest
- DNN

---

### Información en la Wiki ###

https://github.com/niosto/Models-Comparison/wiki

---

### Ejecución ###

Antes de ejecutar los notebooks, instala las dependencias:

`pip install -r requirements.txt`

luego puedes ejecutar cada notebook correspondiente a cada modelo directamente o de a una celda a la vez manteniendo el orden de arriba hacia abajo.

Las ultimas celdas van a generar un reporte de desempeño frente a la base de datos dada la configuración de cada modelo en formato csv.

Esos resultados son los que se necesitan luego para ejecutar `Comparative_table.ipynb` donde podrás visualizar una tabla comparativa final teniendo en cuenta el desempeño de cada modelo con cada particion del dataframe.

